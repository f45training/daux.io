app\models\RevenueSummaries
===============






* Class name: RevenueSummaries
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'studio_id' => 'integer', 'studio_name' => 'string', 'division_number' => 'integer', 'country' => 'string', 'region' => 'string', 'state' => 'string', 'classes_per_week' => 'string', 'currency' => 'string', 'opening_date' => 'datetime', 'year' => 'string', 'jan' => 'integer', 'feb' => 'integer', 'mar' => 'integer', 'apr' => 'integer', 'may' => 'integer', 'jun' => 'integer', 'jul' => 'integer', 'aug' => 'integer', 'sep' => 'integer', 'oct' => 'integer', 'nov' => 'integer', 'dec' => 'integer', 'total' => 'integer')





* Visibility: **protected**


Methods
-------


### getSummaries

    mixed app\models\RevenueSummaries::getSummaries($opt)





* Visibility: **public**


#### Arguments
* $opt **mixed**



### getAllSummaryByYear

    mixed app\models\RevenueSummaries::getAllSummaryByYear($year)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $year **mixed**


