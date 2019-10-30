app\models\ExercisesEquipment
===============






* Class name: ExercisesEquipment
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $validates

    public mixed $validates = array('max_per_workout' => array(array('notEmpty', 'message' => 'You must include a Max Per Workout.'), array('numeric', 'message' => 'Max Per Workout should be numeric.')), 'equipment_name' => array(array('notEmpty', 'message' => 'You must include a Equipment name.')))





* Visibility: **public**


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'equipment_name' => 'string', 'max_per_workout' => 'integer', 'units' => 'string', 'status' => 'integer', 'franchisee_type' => 'string', 'franchisee_type_id' => 'integer', 'timestamp' => 'timestamp')





* Visibility: **protected**


Methods
-------


### dropdown

    mixed app\models\ExercisesEquipment::dropdown()





* Visibility: **public**
* This method is **static**.




### getEquipmentByExercises

    \app\models\[type] app\models\ExercisesEquipment::getEquipmentByExercises(\app\models\[type] $exercises_id)

Returns equipment by `exercises_id`



* Visibility: **public**


#### Arguments
* $exercises_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### getAllEquipmentMaxCountPerWorkout

    \app\models\[type] app\models\ExercisesEquipment::getAllEquipmentMaxCountPerWorkout()

Returns all ExercisesEquipment



* Visibility: **public**



