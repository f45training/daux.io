app\models\Fmlikes
===============






* Class name: Fmlikes
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'track' => 'string', 'ip' => 'string', 'location' => 'string', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $validates

    public mixed $validates = array('track' => array(array('notEmpty', 'message' => 'You must include a track.')), 'ip' => array(array('notEmpty', 'message' => 'You must include a IP.')))





* Visibility: **public**



