app\models\Tokens
===============






* Class name: Tokens
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'token' => 'string', 'user_id' => 'integer', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $validates

    public mixed $validates = array('token' => array(array('notEmpty', 'message' => 'You must include a token.')), 'user_id' => array(array('notEmpty', 'message' => 'You must include a user_id.')))





* Visibility: **public**


Methods
-------


### checkToken

    mixed app\models\Tokens::checkToken()





* Visibility: **public**
* This method is **static**.



