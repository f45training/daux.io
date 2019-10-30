app\models\FreshdeskLogs
===============






* Class name: FreshdeskLogs
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'cc_emails' => 'text', 'fwd_emails' => 'text', 'reply_cc_emails' => 'text', 'fr_escalated' => 'string', 'spam' => 'string', 'email_config_id' => 'string', 'group_id' => 'string', 'priority' => 'string', 'requester_id' => 'string', 'responder_id' => 'string', 'source' => 'string', 'company_id' => 'string', 'status' => 'string', 'subject' => 'string', 'to_emails' => 'text', 'product_id' => 'string', 'freshdesk_id' => 'string', 'type' => 'string', 'due_by' => 'string', 'fr_due_by' => 'string', 'is_escalated' => 'string', 'description' => 'text', 'description_text' => 'text', 'custom_fields' => 'text', 'created_at' => 'string', 'updated_at' => 'string', 'timestamp' => 'timestamp')





* Visibility: **protected**


Methods
-------


### getSchemaFields

    \app\models\[type] app\models\FreshdeskLogs::getSchemaFields()

Return Last Approved on Induction



* Visibility: **public**




### setFreshdeskObject

    mixed app\models\FreshdeskLogs::setFreshdeskObject($data, $dates, $status_labels)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **mixed**
* $dates **mixed**
* $status_labels **mixed**



### getFreshdeskLogs

    mixed app\models\FreshdeskLogs::getFreshdeskLogs($days)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $days **mixed**


