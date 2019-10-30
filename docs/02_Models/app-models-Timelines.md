app\models\Timelines
===============






* Class name: Timelines
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'title' => 'string', 'data' => 'text', 'expected_heartrate_percentage' => 'float', 'session_type_id' => 'integer', 'timestamp' => 'timestamp', 'stations' => 'text', 'stations_per_pod' => 'integer')





* Visibility: **protected**


### $validates

    public mixed $validates = array('title' => array(array('notEmpty', 'message' => 'You must include a name.')), 'data' => array(array('isValidActivity', 'message' => 'You must include a valid activity.')))





* Visibility: **public**


### $hasMany

    public mixed $hasMany = array('ExerciseRelations' => array('key' => array('id' => 'workout_id')))





* Visibility: **public**


Methods
-------


### getSchedulesDaysAhead

    mixed app\models\Timelines::getSchedulesDaysAhead($weekday)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $weekday **mixed**


