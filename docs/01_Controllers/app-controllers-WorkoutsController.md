app\controllers\WorkoutsController
===============

Base class for controllers housing common functions.




* Class name: WorkoutsController
* Namespace: app\controllers
* Parent class: [app\controllers\Rest](app-controllers-Rest.md)



Constants
----------


### VIDEO_PATH

    const VIDEO_PATH = "http://f45tv.s3-website-ap-southeast-2.amazonaws.com/videos/GYM_LOW_RES/"





Properties
----------


### $dataExclude

    public mixed $dataExclude = array()





* Visibility: **public**


### $videoPath

    public mixed $videoPath = "http://socialstaging.com/xhtml/f45/videos/"





* Visibility: **public**


### $files

    public mixed $files = array()





* Visibility: **public**


### $version

    private mixed $version = '2.5'





* Visibility: **private**


### $workout_name

    private mixed $workout_name = ''





* Visibility: **private**


### $max_people_per_station

    private mixed $max_people_per_station = 1





* Visibility: **private**


### $newVideoPath

    private mixed $newVideoPath = "http://f45tv.s3-website-ap-southeast-2.amazonaws.com/videos/GYM_LOW_RES/"





* Visibility: **private**


### $currentUser

    protected mixed $currentUser = null





* Visibility: **protected**


### $model

    public string $model





* Visibility: **public**


### $fields

    public array $fields





* Visibility: **public**


### $searchConditions

    public mixed $searchConditions





* Visibility: **public**


### $disAllowed

    public mixed $disAllowed = array()





* Visibility: **public**


### $authCheckArray

    public mixed $authCheckArray = array()





* Visibility: **public**


### $auth

    public mixed $auth = true





* Visibility: **public**


### $authEnabled

    public mixed $authEnabled = false





* Visibility: **public**


### $isAdmin

    public mixed $isAdmin = false





* Visibility: **public**


### $isUser

    public mixed $isUser = false





* Visibility: **public**


### $isV3

    public mixed $isV3 = false





* Visibility: **public**


### $isViewStudiosOnly

    public mixed $isViewStudiosOnly = false





* Visibility: **public**


### $updatePassword

    public mixed $updatePassword = false





* Visibility: **public**


### $publicRoutes

    public mixed $publicRoutes = array(array('controller' => 'StatusChecklistFiles', 'action' => 'approveStatus'), array('controller' => 'Timelines', 'action' => 'getGymTimeline'), array('controller' => 'Timelines', 'action' => 'getWeeklyTimeline'))





* Visibility: **public**


### $isPublic

    public mixed $isPublic = false





* Visibility: **public**


Methods
-------


### _init

    mixed app\controllers\Rest::_init()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### index

    mixed app\controllers\Rest::index()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### add

    mixed app\controllers\Rest::add()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### edit

    mixed app\controllers\Rest::edit()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### get_equipments_exercises

    mixed app\controllers\WorkoutsController::get_equipments_exercises()





* Visibility: **public**




### get_franchisee_date

    mixed app\controllers\WorkoutsController::get_franchisee_date()





* Visibility: **public**




### get_workout

    mixed app\controllers\WorkoutsController::get_workout()





* Visibility: **public**




### export

    mixed app\controllers\WorkoutsController::export()





* Visibility: **public**




### get_workout_types

    mixed app\controllers\WorkoutsController::get_workout_types()





* Visibility: **public**




### getExerciseWeekDay

    mixed app\controllers\WorkoutsController::getExerciseWeekDay()





* Visibility: **public**




### weeks

    mixed app\controllers\WorkoutsController::weeks()

Return all workout weeks added
v1/workouts/weeks



* Visibility: **public**




### import

    mixed app\controllers\WorkoutsController::import()





* Visibility: **public**




### importWithCopy

    mixed app\controllers\WorkoutsController::importWithCopy()





* Visibility: **public**




### _exec_import

    mixed app\controllers\WorkoutsController::_exec_import($handle, $copy)





* Visibility: **public**


#### Arguments
* $handle **mixed**
* $copy **mixed**



### getWorkoutsByType

    mixed app\controllers\WorkoutsController::getWorkoutsByType()





* Visibility: **public**




### getWorkoutByDate

    mixed app\controllers\WorkoutsController::getWorkoutByDate()





* Visibility: **public**




### updateWeekDays

    mixed app\controllers\WorkoutsController::updateWeekDays()





* Visibility: **public**




### downloadWorkoutTemplateCsv

    mixed app\controllers\WorkoutsController::downloadWorkoutTemplateCsv()





* Visibility: **public**




### view

    mixed app\controllers\Rest::view()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### search

    mixed app\controllers\Rest::search()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### update

    array app\controllers\Rest::update()

Update details of the specific controller extending Rest class



* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### get_vimeo_data

    mixed app\controllers\Rest::get_vimeo_data($id, $session_vid_id)





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)


#### Arguments
* $id **mixed**
* $session_vid_id **mixed**



### delete

    mixed app\controllers\Rest::delete()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### publish

    mixed app\controllers\Rest::publish()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### unpublish

    mixed app\controllers\Rest::unpublish()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### unset_disabled_items

    mixed app\controllers\Rest::unset_disabled_items($disabled_items)





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)


#### Arguments
* $disabled_items **mixed**



### save_audit_logs

    mixed app\controllers\Rest::save_audit_logs($model, $data, $action)





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)


#### Arguments
* $model **mixed**
* $data **mixed**
* $action **mixed**



### getIP

    mixed app\controllers\Rest::getIP()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)



