app\models\AcademyModules
===============






* Class name: AcademyModules
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    public mixed $_schema = array('id' => 'integer', 'course_id' => 'integer', 'name' => 'string', 'description' => 'text', 'photo_url' => 'text', 'video_url' => 'text', 'is_deleted' => 'integer', 'created_by' => 'string', 'updated_by' => 'string', 'created_dt' => 'date', 'updated_dt' => 'date')





* Visibility: **public**


### $belongsTo

    public mixed $belongsTo = array('AcademyCourses' => array('class' => '\app\models\AcademyCourses', 'key' => 'course_id'))





* Visibility: **public**


Methods
-------


### getModulesByCourseIdWithSections

    mixed app\models\AcademyModules::getModulesByCourseIdWithSections($courseId)





* Visibility: **public**


#### Arguments
* $courseId **mixed**



### getModulesByModuleId

    mixed app\models\AcademyModules::getModulesByModuleId($modId)





* Visibility: **public**


#### Arguments
* $modId **mixed**


