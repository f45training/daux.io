app\models\Checklists
===============






* Class name: Checklists
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'task' => 'string', 'days' => 'integer', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $hasOne

    public mixed $hasOne = array('ChecklistRelations' => array('key' => array('id' => 'checklist_id')))





* Visibility: **public**


### $validates

    public mixed $validates = array('task' => array(array('notEmpty', 'message' => 'You must include a task.')), 'days' => array(array('notEmpty', 'message' => 'You must include days.'), array('numeric', 'message' => 'Days should be numeric.')))





* Visibility: **public**



