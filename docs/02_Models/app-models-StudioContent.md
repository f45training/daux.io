app\models\StudioContent
===============






* Class name: StudioContent
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'key' => 'string', 'value' => 'text')





* Visibility: **protected**


### $validates

    public mixed $validates = array('franchisee_id' => array(array('notEmpty', 'message' => 'You must include a Gym ID.')), 'key' => array(array('notEmpty', 'message' => 'You must include a key.'), array('isUniqueKey', 'message' => 'key is already used for the Gym ID.')), 'value' => array(array('notEmpty', 'message' => 'You must include a value.')))





* Visibility: **public**



