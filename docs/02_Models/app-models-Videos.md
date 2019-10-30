app\models\Videos
===============






* Class name: Videos
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'name' => 'string', 'video_url' => 'string', 'thumb_url' => 'string', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $validates

    public mixed $validates = array('name' => array(array('notEmpty', 'message' => 'You must include a name.')), 'video_url' => array(array('notEmpty', 'message' => 'You must include a video URL.')), 'thumb_url' => array(array('notEmpty', 'message' => 'You must include a thumbnail URL.')))





* Visibility: **public**



