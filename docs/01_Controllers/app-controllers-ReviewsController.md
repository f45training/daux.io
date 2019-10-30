app\controllers\ReviewsController
===============

Base class for controllers housing common functions.




* Class name: ReviewsController
* Namespace: app\controllers
* Parent class: [app\controllers\Rest](app-controllers-Rest.md)





Properties
----------


### $skills

    public mixed $skills = array(array("key" => "music", "name" => "Music", "weightage" => 10, "value" => 5), array("key" => "on_time", "name" => "On Time", "weightage" => 9, "value" => 5), array("key" => "uniform_compliance", "name" => "Uniform Compliance", "weightage" => 6, "value" => 5), array("key" => "t10_score", "name" => "T10 Score", "weightage" => 9, "value" => 5), array("key" => "warm_up", "name" => "Warm Up", "weightage" => 4, "value" => 5), array("key" => "trainer_quality_and_likability", "name" => "Trainer Quality and likability", "weightage" => 14, "value" => 5), array("key" => "stereo_system", "name" => "Stereo System", "weightage" => 6, "value" => 5), array("key" => "equip_quality", "name" => "Equip Quality", "weightage" => 4, "value" => 5), array("key" => "training_program_compliance", "name" => "Training Program Compliance", "weightage" => 8, "value" => 5), array("key" => "exercise_explanation", "name" => "Exercise Explanation", "weightage" => 4, "value" => 5), array("key" => "pre_post_session_welcomes", "name" => "Pre + Post Session welcomes", "weightage" => 3, "value" => 5), array("key" => "technology", "name" => "Technology", "weightage" => 10, "value" => 5), array("key" => "station_numbering", "name" => "Station Numbering", "weightage" => 5, "value" => 5), array("key" => "free_towels", "name" => "Free Towels", "weightage" => 5, "value" => 5), array("key" => "branding_and_banners", "name" => "Branding and Banners", "weightage" => 3, "value" => 5))





* Visibility: **public**


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


### $dataExclude

    public mixed $dataExclude = array()





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




### update

    array app\controllers\Rest::update()

Update details of the specific controller extending Rest class



* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### leaderboard

    mixed app\controllers\ReviewsController::leaderboard()





* Visibility: **public**




### fill_from_array

    mixed app\controllers\ReviewsController::fill_from_array($required_fields, $data)





* Visibility: **private**


#### Arguments
* $required_fields **mixed**
* $data **mixed**



### view

    mixed app\controllers\Rest::view()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### search

    mixed app\controllers\Rest::search()





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



