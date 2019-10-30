app\controllers\FeedbackController
===============

Base class for controllers housing common functions.




* Class name: FeedbackController
* Namespace: app\controllers
* Parent class: [app\controllers\Rest](app-controllers-Rest.md)





Properties
----------


### $skills

    public mixed $skills = array()





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




### leaderboard

    mixed app\controllers\FeedbackController::leaderboard()





* Visibility: **public**




### export

    mixed app\controllers\FeedbackController::export()





* Visibility: **public**




### overallStats

    mixed app\controllers\FeedbackController::overallStats()





* Visibility: **public**




### stats

    mixed app\controllers\FeedbackController::stats($allGyms)





* Visibility: **public**


#### Arguments
* $allGyms **mixed**



### questions_list

    mixed app\controllers\FeedbackController::questions_list()





* Visibility: **public**




### fetch_feedbackAnswers_hours

    mixed app\controllers\FeedbackController::fetch_feedbackAnswers_hours($user_id)





* Visibility: **public**


#### Arguments
* $user_id **mixed**



### api_format

    mixed app\controllers\FeedbackController::api_format($feedback_data, $format, $allGyms)





* Visibility: **public**


#### Arguments
* $feedback_data **mixed**
* $format **mixed**
* $allGyms **mixed**



### feedback_report

    mixed app\controllers\FeedbackController::feedback_report()





* Visibility: **public**




### array_average

    mixed app\controllers\FeedbackController::array_average($array, $filter, $round)





* Visibility: **public**


#### Arguments
* $array **mixed**
* $filter **mixed**
* $round **mixed**



### fetch_feedbackAnswers_days

    mixed app\controllers\FeedbackController::fetch_feedbackAnswers_days($user_id, $no_of_days, $allGyms)





* Visibility: **public**


#### Arguments
* $user_id **mixed**
* $no_of_days **mixed**
* $allGyms **mixed**



### fetch_feedbackAnswers_all_time

    mixed app\controllers\FeedbackController::fetch_feedbackAnswers_all_time($user_id)





* Visibility: **public**


#### Arguments
* $user_id **mixed**



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



