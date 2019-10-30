app\models\Qa
===============






* Class name: Qa
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'subject' => 'string', 'question' => 'string', 'cat_id' => 'integer', 'franchisee_id' => 'integer', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $hasMany

    public mixed $hasMany = array('QaResponses' => array('key' => array('id' => 'qa_id')))





* Visibility: **public**


### $belongsTo

    public mixed $belongsTo = array('Franchisees' => array('key' => array('franchisee_id' => 'id')), 'QaCats' => array('key' => array('cat_id' => 'id')))





* Visibility: **public**


### $validates

    public mixed $validates = array('subject' => array(array('notEmpty', 'message' => 'You must include subject.')), 'question' => array(array('notEmpty', 'message' => 'You must include a question.')), 'cat_id' => array(array('notEmpty', 'message' => 'You must include a category id.'), array('catExist', 'message' => 'Invalid category id used')), 'franchisee_id' => array(array('notEmpty', 'message' => 'You must include a franchisee id.'), array('franchiseeExist', 'message' => 'Invalid franchisee id used')))





* Visibility: **public**


Methods
-------


### responses

    mixed app\models\Qa::responses($qa_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $qa_id **mixed**


