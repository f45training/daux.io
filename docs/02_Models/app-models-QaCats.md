app\models\QaCats
===============






* Class name: QaCats
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'name' => 'string', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $hasMany

    public mixed $hasMany = array('Qa' => array('key' => array('id' => 'cat_id')))





* Visibility: **public**


### $validates

    public mixed $validates = array('name' => array(array('notEmpty', 'message' => 'You must include a name.')))





* Visibility: **public**



