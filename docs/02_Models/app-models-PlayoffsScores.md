app\models\PlayoffsScores
===============






* Class name: PlayoffsScores
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'name' => 'string', 'email' => 'string', 'gym_id' => 'integer', 'gender' => 'string', 'scores' => 'text', 'total_score' => 'float', 'favorite_workout' => 'string', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $validates

    public mixed $validates = array('name' => array(array('notEmpty', 'message' => 'You must include a name.')), 'email' => array(array('notEmpty', 'message' => 'You must include an email.'), array('email', 'message' => 'email is not valid.')), 'gym_id' => array(array('notEmpty', 'messge' => 'You must include a gym id')), 'scores' => array(array('notEmpty', 'message' => 'You must include scores.')))





* Visibility: **public**


### $belongsTo

    public mixed $belongsTo = array('Franchisees' => array('key' => array('gym_id' => 'id')))





* Visibility: **public**



