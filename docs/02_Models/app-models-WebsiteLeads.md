app\models\WebsiteLeads
===============






* Class name: WebsiteLeads
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $sortKey

    public mixed $sortKey = ""





* Visibility: **public**
* This property is **static**.


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'app' => 'string', 'url' => 'string', 'ip' => 'string', 'device' => 'string', 'priority_leads' => 'integer', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $validates

    public mixed $validates = array('priority_leads' => array(array('notEmpty', 'message' => 'Priority value 1 to 10.')))





* Visibility: **public**


Methods
-------


### playbook_leads

    mixed app\models\WebsiteLeads::playbook_leads()





* Visibility: **public**
* This method is **static**.




### curlRequest

    mixed app\models\WebsiteLeads::curlRequest($url, $key)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $url **mixed**
* $key **mixed**



### getReportMonths

    mixed app\models\WebsiteLeads::getReportMonths()





* Visibility: **public**
* This method is **static**.




### setLeadsObject

    mixed app\models\WebsiteLeads::setLeadsObject()





* Visibility: **public**
* This method is **static**.




### getWebsiteLeads

    mixed app\models\WebsiteLeads::getWebsiteLeads()





* Visibility: **public**
* This method is **static**.




### getPreviousLeads

    mixed app\models\WebsiteLeads::getPreviousLeads($data_object)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $data_object **mixed**



### sortByKeyValue

    mixed app\models\WebsiteLeads::sortByKeyValue($data)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **mixed**



### getAllDaysMonthly

    mixed app\models\WebsiteLeads::getAllDaysMonthly()





* Visibility: **public**
* This method is **static**.




### setLeadsPerDayObject

    mixed app\models\WebsiteLeads::setLeadsPerDayObject($data)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **mixed**



### getLeadsPerSite

    mixed app\models\WebsiteLeads::getLeadsPerSite()





* Visibility: **public**
* This method is **static**.




### getLeadsPerDay

    mixed app\models\WebsiteLeads::getLeadsPerDay()





* Visibility: **public**
* This method is **static**.




### getFranchiseeLeads

    mixed app\models\WebsiteLeads::getFranchiseeLeads()





* Visibility: **public**
* This method is **static**.



