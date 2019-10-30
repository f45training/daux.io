app\models\IncomingLeads
===============

Franchisees Agreements




* Class name: IncomingLeads
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'domain' => 'string', 'time' => 'string', 'source' => 'string', 'name' => 'string', 'email' => 'string', 'mobile_number' => 'string', 'location' => 'string', 'url' => 'string', 'territory_interested_in' => 'string', 'have_capital_to_invest' => 'string', 'have_operated_business_before' => 'string', 'looking_to_work_in_business_or_passive_investment' => 'string', 'deal_month' => 'string', 'person_id_name' => 'string', 'person_owner_id_name' => 'string', 'country_interested' => 'string', 'domain_submitted_form' => 'string', 'country' => 'string', 'created_at' => 'timestamp')





* Visibility: **protected**


Methods
-------


### getLeadsPerDay

    mixed app\models\IncomingLeads::getLeadsPerDay()





* Visibility: **public**
* This method is **static**.




### getWebsiteLeads

    mixed app\models\IncomingLeads::getWebsiteLeads()





* Visibility: **public**
* This method is **static**.




### getLeadsPerMonth

    mixed app\models\IncomingLeads::getLeadsPerMonth()





* Visibility: **public**
* This method is **static**.




### getMonthlyLeadsData

    mixed app\models\IncomingLeads::getMonthlyLeadsData($month, $year)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $month **mixed**
* $year **mixed**



### getDailyLeadsData

    mixed app\models\IncomingLeads::getDailyLeadsData($day, $month, $year)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $day **mixed**
* $month **mixed**
* $year **mixed**



### substrwords

    mixed app\models\IncomingLeads::substrwords($text, $maxchar, $end)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $text **mixed**
* $maxchar **mixed**
* $end **mixed**



### getMonthlyLeadChart

    mixed app\models\IncomingLeads::getMonthlyLeadChart()





* Visibility: **public**
* This method is **static**.




### getThirtyDayChart

    mixed app\models\IncomingLeads::getThirtyDayChart()





* Visibility: **public**
* This method is **static**.




### getChartUrl

    mixed app\models\IncomingLeads::getChartUrl($api_key, $content)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $api_key **mixed**
* $content **mixed**



### getLeadsSource

    mixed app\models\IncomingLeads::getLeadsSource()





* Visibility: **public**
* This method is **static**.




### toKlipFormat

    mixed app\models\IncomingLeads::toKlipFormat($arr, $dates, $add)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $arr **mixed**
* $dates **mixed**
* $add **mixed**



### sortByKeyVal

    mixed app\models\IncomingLeads::sortByKeyVal($arr, $skey, $dir)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $arr **mixed**
* $skey **mixed**
* $dir **mixed**



### groupLeads

    mixed app\models\IncomingLeads::groupLeads($time, $var, $country, $source)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $time **mixed**
* $var **mixed**
* $country **mixed**
* $source **mixed**



### getTotalLeads

    mixed app\models\IncomingLeads::getTotalLeads()





* Visibility: **public**
* This method is **static**.




### getLATime

    string app\models\IncomingLeads::getLATime($format, string $interval)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $format **mixed**
* $interval **string**



### getCountryLeads

    mixed app\models\IncomingLeads::getCountryLeads()





* Visibility: **public**
* This method is **static**.




### getLeadsPerCountryWeekly

    mixed app\models\IncomingLeads::getLeadsPerCountryWeekly()





* Visibility: **public**
* This method is **static**.




### getLeadsPerCountry

    mixed app\models\IncomingLeads::getLeadsPerCountry()





* Visibility: **public**
* This method is **static**.



