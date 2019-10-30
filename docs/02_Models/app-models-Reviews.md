app\models\Reviews
===============






* Class name: Reviews
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'reviewer' => 'string', 'franchisee_id' => 'integer', 'music' => 'integer', 'on_time' => 'integer', 'uniform_compliance' => 'integer', 't10_score' => 'integer', 'warm_up' => 'integer', 'trainer_quality_and_likability' => 'integer', 'stereo_system' => 'integer', 'equip_quality' => 'integer', 'training_program_compliance' => 'integer', 'exercise_explanation' => 'integer', 'pre_post_session_welcomes' => 'integer', 'technology' => 'integer', 'station_numbering' => 'integer', 'free_towels' => 'integer', 'branding_and_banners' => 'integer', 'total_score' => 'float', 'status' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $validates

    public mixed $validates = array('reviewer' => array(array('notEmpty', 'message' => 'You must include a reviewer.')), 'franchisee_id' => array(array('notEmpty', 'message' => 'You must include a gym.')))





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('Franchisees' => array('key' => array('franchisee_id' => 'id')))





* Visibility: **public**


Methods
-------


### updateAverageReview

    mixed app\models\Reviews::updateAverageReview($franchisee_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchisee_id **mixed**


