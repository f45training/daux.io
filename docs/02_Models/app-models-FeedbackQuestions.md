app\models\FeedbackQuestions
===============






* Class name: FeedbackQuestions
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    public mixed $_schema = array('id' => 'integer', 'question' => 'string', 'weightage' => 'integer', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **public**


### $validates

    public mixed $validates = array('question' => array(array('notEmpty', 'message' => 'You must include a question.')), 'weightage' => array(array('notEmpty', 'message' => 'You must include weightage.')))





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('Franchisees' => array('key' => array('franchisee_id' => 'id')))





* Visibility: **public**


### $hasMany

    public mixed $hasMany = array('FeedbackAnswers')





* Visibility: **public**


Methods
-------


### averageReview

    mixed app\models\FeedbackQuestions::averageReview($franchisee_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchisee_id **mixed**


