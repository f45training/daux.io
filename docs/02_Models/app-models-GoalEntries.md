app\models\GoalEntries
===============






* Class name: GoalEntries
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'goal_id' => 'integer', 'date' => 'date', 'targetdate' => 'date', 'payingmembers' => 'integer', 'facebooklikes' => 'integer', 'attendances' => 'integer', 'averagefeedbackscore' => 'integer', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $belongsTo

    public mixed $belongsTo = array('GoalSettings' => array('key' => array('goal_id' => 'id')))





* Visibility: **public**



