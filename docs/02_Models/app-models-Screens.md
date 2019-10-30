app\models\Screens
===============






* Class name: Screens
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'exercise' => 'string', 'section_id' => 'integer', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $hasOne

    public mixed $hasOne = array('Exercises' => array('key' => array('exercise' => 'id')))





* Visibility: **public**


### $validates

    public mixed $validates = array('exercise' => array(array('notEmpty', 'message' => 'You must include an exercise.')), 'section_id' => array(array('notEmpty', 'message' => 'You must include a section id.'), array('sectionExist', 'message' => 'Invalid section id used')))





* Visibility: **public**



