app\models\Todos
===============






* Class name: Todos
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'checklist_id' => 'integer', 'todo_title' => 'string', 'todo_description' => 'text', 'todo_attached_file' => 'string', 'todo_attached_vid' => 'string', 'todo_priority' => 'integer', 'validation_type' => 'integer', 'status' => 'integer', 'is_email_notif' => 'boolean', 'is_approval_feature' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $hasMany

    public mixed $hasMany = array('TodoStatuses' => array('key' => array('id' => 'todo_id')))





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('TodoChecklists' => array('key' => array('checklist_id' => 'id')))





* Visibility: **public**



