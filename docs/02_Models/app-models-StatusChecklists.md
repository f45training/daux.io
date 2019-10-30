app\models\StatusChecklists
===============






* Class name: StatusChecklists
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'index' => 'string', 'name' => 'string', 'description' => 'string', 'text_desc' => 'text', 'order' => 'integer', 'status' => 'integer', 'video' => 'string', 'excluded' => 'boolean', 'pb_buttons' => 'text', 'condition' => 'text')





* Visibility: **protected**


### $PRE_OPEN_INSPECTION_INDEX

    public mixed $PRE_OPEN_INSPECTION_INDEX = 5





* Visibility: **public**
* This property is **static**.


### $RE_OPEN_PROCESS_INDEX

    public mixed $RE_OPEN_PROCESS_INDEX = 7





* Visibility: **public**
* This property is **static**.


### $PREMISE_LOCATION_LEASE_INDEX

    public mixed $PREMISE_LOCATION_LEASE_INDEX = 1





* Visibility: **public**
* This property is **static**.


### $FLOORPLAN_INDEX

    public mixed $FLOORPLAN_INDEX = 3





* Visibility: **public**
* This property is **static**.


### $PRE_OPEN_OLD_NAME

    public mixed $PRE_OPEN_OLD_NAME = 'Pre-Open Inspection'





* Visibility: **public**
* This property is **static**.


### $RE_OPEN__NAME

    public mixed $RE_OPEN__NAME = 'Re-Open Inspection'





* Visibility: **public**
* This property is **static**.


### $PRE_OPEN_OLD_DESC

    public mixed $PRE_OPEN_OLD_DESC = 'F45TV Access'





* Visibility: **public**
* This property is **static**.


### $statusChecklistStatus

    public mixed $statusChecklistStatus = array('NO TRANSACTION', 'SUCCESS', 'PENDING', 'COMING SOON')





* Visibility: **public**
* This property is **static**.


Methods
-------


### getEmailRecipientPerEnv

    mixed app\models\StatusChecklists::getEmailRecipientPerEnv($franchisee_id, $status_id)

this is for status checklist emails per status and environment



* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchisee_id **mixed**
* $status_id **mixed**



### checkEnv

    mixed app\models\StatusChecklists::checkEnv()





* Visibility: **public**
* This method is **static**.



