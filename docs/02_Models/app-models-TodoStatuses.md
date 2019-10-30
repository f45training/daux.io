app\models\TodoStatuses
===============






* Class name: TodoStatuses
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'user_id' => 'integer', 'todo_id' => 'integer', 'upload_status' => 'boolean', 'status' => 'boolean', 'is_pending' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $hasMany

    public mixed $hasMany = array('Todos' => array('key' => array('todo_id' => 'id')), 'TodoStatutesCompletedImages' => array('key' => array('id' => 'todo_statuses_id')))





* Visibility: **public**


### $belongsTo

    public mixed $belongsTo = array('Users' => array('to' => 'Users', 'key' => 'user_id'))





* Visibility: **public**


### $validates

    public mixed $validates = array('user_id' => array(array('notEmpty', 'message' => 'You must include user id.'), array('numeric', 'message' => 'User id should be numeric.')), 'todo_id' => array(array('notEmpty', 'message' => 'You must include todo id.'), array('numeric', 'message' => 'Todo id should be numeric.')), 'status' => array(array('notEmpty', 'message' => 'You must include status.'), array('numeric', 'message' => 'Status should be numeric.')))





* Visibility: **public**



