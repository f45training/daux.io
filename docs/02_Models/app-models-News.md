app\models\News
===============






* Class name: News
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'title' => 'string', 'content' => 'text', 'author' => 'string', 'criteria' => 'text', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $validates

    public mixed $validates = array('title' => array(array('notEmpty', 'message' => 'You must include a title.')), 'content' => array(array('notEmpty', 'message' => 'You must include content.')), 'author' => array(array('notEmpty', 'message' => 'You must include author.')))





* Visibility: **public**


Methods
-------


### getWeeklyNews

    \app\models\[type] app\models\News::getWeeklyNews()

Returns newly added news this week



* Visibility: **public**



