app\models\QaResponses
===============






* Class name: QaResponses
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'response' => 'string', 'qa_id' => 'integer', 'franchisee_id' => 'integer', 'parent' => 'integer', 'correct' => 'boolean', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $hasOne

    public mixed $hasOne = array('Qa', 'Franchisees' => array('key' => array('franchisee_id' => 'id')))





* Visibility: **public**


### $validates

    public mixed $validates = array('response' => array(array('notEmpty', 'message' => 'You must include a response')), 'qa_id' => array(array('notEmpty', 'message' => 'You must include a qa id.'), array('qaExist', 'message' => 'Invalid qa id used')), 'franchisee_id' => array(array('notEmpty', 'message' => 'You must include a franchisee id.'), array('franchiseeExist', 'message' => 'Invalid franchisee id used')))





* Visibility: **public**



