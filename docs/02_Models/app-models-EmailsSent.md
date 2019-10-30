app\models\EmailsSent
===============






* Class name: EmailsSent
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'email_from' => 'string', 'email_to' => 'string', 'message_id' => 'string', 'franchisee_id' => 'string', 'tranmission_id' => 'string', 'template_id' => 'string', 'email_subject' => 'string', 'email_status' => 'string', 'date_created' => 'timestamp', 'date_updated' => 'timestamp')





* Visibility: **protected**


### $hasOne

    public mixed $hasOne = array('EmailLogs' => array('key' => array('transmission_id' => 'transmission_id')))





* Visibility: **public**


Methods
-------


### findAll

    mixed app\models\EmailsSent::findAll()





* Visibility: **public**
* This method is **static**.



