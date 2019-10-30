app\models\StatusChecklistSettings
===============






* Class name: StatusChecklistSettings
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'recipients' => 'string', 'status_id' => 'integer', 'environment' => 'string', 'franchisee_id' => 'integer')





* Visibility: **protected**


### $statusChecklistEmailTemplate

    public mixed $statusChecklistEmailTemplate = array(array('0' => 'InductionApprovedRequest'), array('1' => 'ApprovedRequest'), array('2' => 'EquipmentOrdered'), array('3' => 'FloorPlanApprovedRequest'), array('4' => 'SignagePlanApprovedRequest'), array('5' => 'ApprovedRequest'))





* Visibility: **public**
* This property is **static**.


### $envList

    public mixed $envList = array('Development', 'Staging', 'Production')





* Visibility: **public**
* This property is **static**.


### $emailType

    public mixed $emailType = array('Outbound', 'Inbound')





* Visibility: **public**
* This property is **static**.


Methods
-------


### getEmailRecipientPerEnv

    mixed app\models\StatusChecklistSettings::getEmailRecipientPerEnv($franchisee_id, $status_id, $type)

this is for status checklist emails per status and environment



* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchisee_id **mixed**
* $status_id **mixed**
* $type **mixed**



### sendEmailNotification

    mixed app\models\StatusChecklistSettings::sendEmailNotification()





* Visibility: **public**
* This method is **static**.




### checkEnv

    mixed app\models\StatusChecklistSettings::checkEnv()





* Visibility: **public**
* This method is **static**.



