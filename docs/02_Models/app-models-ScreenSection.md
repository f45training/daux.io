app\models\ScreenSection
===============






* Class name: ScreenSection
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'section' => 'string', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $hasMany

    public mixed $hasMany = array('Screens' => array('key' => array('id' => 'section_id')))





* Visibility: **public**


### $validates

    public mixed $validates = array('section' => array(array('notEmpty', 'message' => 'You must include a section.')))





* Visibility: **public**



