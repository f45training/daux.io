app\models\Workouts
===============






* Class name: Workouts
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $imageBaseUrl

    private mixed $imageBaseUrl = 'http://f45tv.s3.amazonaws.com/class-logos/'





* Visibility: **private**
* This property is **static**.


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'workout_name' => 'string', 'week' => 'integer', 'weekday' => 'integer', 'year' => 'integer', 'timeline' => 'integer', 'work' => 'integer', 'rest' => 'integer', 'sets' => 'integer', 'rounds' => 'integer', 'notes' => 'string', 'private_notes' => 'string', 'circuit_movement' => 'string', 'approved_by_name' => 'string', 'status' => 'boolean', 'timestamp' => 'timestamp', 'workoutrounds' => 'integer', 'session_vid_id' => 'integer', 'movement_vid_id' => 'integer', 'program_id' => 'integer', 'session_video_thumbnail' => 'string', 'session_video_mp4' => 'string', 'workout_information_video_thumbnail' => 'string', 'workout_information_video_mp4' => 'string', 'franchisee_type' => 'string', 'franchisee_type_id' => 'integer')





* Visibility: **protected**


### $hasMany

    public mixed $hasMany = array('ExerciseRelations' => array('key' => array('id' => 'workout_id')), 'Timelines' => array('key' => array('timeline' => 'id')))





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('Timelines' => array('key' => array('id' => 'timeline')))





* Visibility: **public**


### $validates

    public mixed $validates = array('workout_name' => array(array('notEmpty', 'message' => 'You must include workout_name')), 'work' => array(array('notEmpty', 'message' => 'You must include work')), 'rest' => array(array('notEmpty', 'message' => 'You must include rest')), 'sets' => array(array('notEmpty', 'message' => 'You must include sets')))





* Visibility: **public**


Methods
-------


### getImageName

    mixed app\models\Workouts::getImageName()





* Visibility: **private**




### __get

    mixed app\models\Workouts::__get($name)





* Visibility: **public**


#### Arguments
* $name **mixed**



### findByWeekWeekday

    \app\models\lithium\data\Entity|null app\models\Workouts::findByWeekWeekday($week, $weekday, $year, $options)

Gets workouts by week, weekday, and year if sepcified



* Visibility: **public**
* This method is **static**.


#### Arguments
* $week **mixed** - &lt;p&gt;number the week&lt;/p&gt;
* $weekday **mixed** - &lt;p&gt;number the weekday&lt;/p&gt;
* $year **mixed** - &lt;p&gt;number the year workout belongs to, defaults to the current week
but is set to 0 as years doesn&#039;t work on workouts right now&lt;/p&gt;
* $options **mixed** - &lt;p&gt;array list of other options, week and weekday will be overriden&lt;/p&gt;



### get201Week

    mixed app\models\Workouts::get201Week(\DateTime $opening_date)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $opening_date **DateTime**



### duplicate

    mixed app\models\Workouts::duplicate($workout_id, $franchisee_type_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $workout_id **mixed**
* $franchisee_type_id **mixed**


