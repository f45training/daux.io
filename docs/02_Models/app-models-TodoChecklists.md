app\models\TodoChecklists
===============






* Class name: TodoChecklists
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'chklist_title' => 'string', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $hasMany

    public mixed $hasMany = array('Todos' => array('key' => array('id' => 'checklist_id')))





* Visibility: **public**



