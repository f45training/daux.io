app\models\AlternativeExercises
===============






* Class name: AlternativeExercises
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'exercise_id' => 'integer', 'alternative_exercise_id' => 'integer', 'order' => 'integer', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $hasMany

    public mixed $hasMany = array('Exercises' => array('key' => array('alternative_exercise_id' => 'id')))





* Visibility: **public**



