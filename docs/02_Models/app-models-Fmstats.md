app\models\Fmstats
===============






* Class name: Fmstats
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'track' => 'string', 'ip' => 'string', 'track_time' => 'integer', 'location' => 'string', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $validates

    public mixed $validates = array('track' => array(array('notEmpty', 'message' => 'You must include a track.')), 'ip' => array(array('notEmpty', 'message' => 'You must include a IP.')), 'track_time' => array(array('notEmpty', 'message' => 'You must include the current track time.')))





* Visibility: **public**



