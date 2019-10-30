app\models\Exercises
===============






* Class name: Exercises
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $explainationTime

    public mixed $explainationTime = array('0' => array('name' => 'Not Set'), '1' => array('name' => 'Simple'), '2' => array('name' => 'Complex'), '3' => array('name' => 'Very Complex'))





* Visibility: **public**
* This property is **static**.


### $exerciseStatus

    public mixed $exerciseStatus = array('1' => 'Approved', '0' => 'Draft')





* Visibility: **public**
* This property is **static**.


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'exercise' => 'string', 'movement_types' => 'string', 'equipments_used' => 'string', 'muscle_groupings_used' => 'string', 'system' => 'string', 'exercises_sections' => 'string', 'equipment' => 'string', 'alternative_exercise' => 'integer', 'muscle_group' => 'string', 'explaination_time' => 'integer', 'notes' => 'string', 'filename' => 'string', 'newvideo' => 'string', 'video_status' => 'boolean', 'status' => 'boolean', 'cue_points' => 'text', 'filename_backup' => 'string', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $validates

    public mixed $validates = array('exercise' => array(array('notEmpty', 'message' => 'You must include exercise name')), 'equipment' => array(array('notEmpty', 'message' => 'You must include equipment name')), 'newvideo' => array(array('notEmpty', 'message' => 'You must include new video')))





* Visibility: **public**


### $hasMany

    public mixed $hasMany = array('ExerciseRelations' => array('exercise_id' => 'id'))





* Visibility: **public**


Methods
-------


### equipment_list

    mixed app\models\Exercises::equipment_list()





* Visibility: **public**
* This method is **static**.




### other_exercises

    mixed app\models\Exercises::other_exercises($id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### getExercises

    mixed app\models\Exercises::getExercises()





* Visibility: **public**
* This method is **static**.




### getExercisesWeekDays

    mixed app\models\Exercises::getExercisesWeekDays($exercise_id, $condition, $week)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $exercise_id **mixed**
* $condition **mixed**
* $week **mixed**



### updateExercises

    mixed app\models\Exercises::updateExercises($datas, $id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $datas **mixed**
* $id **mixed**


