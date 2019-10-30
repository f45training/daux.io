app\models\ExerciseRelations
===============






* Class name: ExerciseRelations
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'exercise_id' => 'integer', 'franchisee_id' => 'integer', 'workout_id' => 'integer', 'station_number' => 'string', 'update_flag' => 'integer', 'status' => 'boolean', 'use_alternative_exercise' => 'boolean', 'alternative_exercise_id' => 'integer', 'timestamp' => 'timestamp', 'order' => 'integer', 'notes' => 'string')





* Visibility: **protected**


### $hasMany

    public mixed $hasMany = array('Exercises' => array('key' => array('exercise_id' => 'id')))





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('Workouts' => array('key' => array('workout_id' => 'id')), 'Franchisees' => array('key' => array('franchisee_id' => 'id')))





* Visibility: **public**


### $validates

    public mixed $validates = array('exercise_id' => array(array('notEmpty', 'message' => 'You must include a exercise id.'), array('exerciseExist', 'message' => 'Invalid exercise id used')), 'franchisee_id' => array(array('notEmpty', 'message' => 'You must include a franchisee id.'), array('franchiseeExist', 'message' => 'Invalid franchisee id used')), 'workout_id' => array(array('notEmpty', 'message' => 'You must include a workout id.'), array('workoutExist', 'message' => 'Invalid workout id used')))





* Visibility: **public**


Methods
-------


### exercise_videos

    mixed app\models\ExerciseRelations::exercise_videos($franchisee_id, $franchisee)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchisee_id **mixed**
* $franchisee **mixed**



### exercise_videos_weekly

    mixed app\models\ExerciseRelations::exercise_videos_weekly($franchisee_id, $period)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchisee_id **mixed**
* $period **mixed**


