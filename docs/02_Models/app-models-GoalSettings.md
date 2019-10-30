app\models\GoalSettings
===============






* Class name: GoalSettings
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'gym_id' => 'integer', 'date' => 'date', 'targetdate' => 'date', 'targetpayingmembers' => 'integer', 'targetfacebooklikes' => 'integer', 'targetattendances' => 'integer', 'targetaveragefeedbackscore' => 'integer', 'status' => 'boolean', 'timestamp' => 'timestamp', 'facebookurl' => 'string')





* Visibility: **protected**


### $validates

    public mixed $validates = array('date' => array(array('notEmpty', 'message' => 'You must include a date.')), 'targetdate' => array(array('notEmpty', 'message' => 'You must include a targetdate.')))





* Visibility: **public**



