app\models\Feedback
===============






* Class name: Feedback
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'reviewer' => 'string', 'franchisee_id' => 'integer', 'total_score' => 'integer', 'datetime' => 'datetime', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $validates

    public mixed $validates = array('franchisee_id' => array(array('notEmpty', 'message' => 'You must include a gym.')))





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('Franchisees' => array('key' => array('franchisee_id' => 'id')))





* Visibility: **public**


Methods
-------


### averageReview

    mixed app\models\Feedback::averageReview($franchisee_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchisee_id **mixed**


