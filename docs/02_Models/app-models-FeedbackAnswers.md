app\models\FeedbackAnswers
===============






* Class name: FeedbackAnswers
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'feedback_id' => 'string', 'feedback_question_id' => 'integer', 'feedback_value' => 'integer', 'franchisee_id' => 'integer', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $belongsTo

    public mixed $belongsTo = array('FeedbackQuestions')





* Visibility: **public**


### $validates

    public mixed $validates = array('feedback_question_id' => array(array('notEmpty', 'message' => 'You must include feedback_question_id.'), array('feedbackQuestionExist', 'message' => 'Invalid  feedback_question_id used')), 'feedback_value' => array(array('notEmpty', 'message' => 'You must include feedback_value.')), 'franchisee_id' => array(array('notEmpty', 'message' => 'You must include a franchisee_id.'), array('franchiseeExist', 'message' => 'Invalid franchisee id used')))





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('Franchisees' => array('key' => array('franchisee_id' => 'id')))





* Visibility: **public**


Methods
-------


### averageReview

    mixed app\models\FeedbackAnswers::averageReview($franchisee_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchisee_id **mixed**


