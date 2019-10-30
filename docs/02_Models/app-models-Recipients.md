app\models\Recipients
===============






* Class name: Recipients
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'template_id' => 'string', 'name' => 'string', 'emails' => 'string', 'cc' => 'string', 'is_deleted' => 'integer', 'notes' => 'text', 'timestamp' => 'timestamp', 'trigger' => 'text', 'isscheduler' => 'boolean')





* Visibility: **protected**


### $validates

    public mixed $validates = array('template_id' => array(array('isUniqueTemplateId', 'message' => 'Template ID already exists.')))





* Visibility: **public**



