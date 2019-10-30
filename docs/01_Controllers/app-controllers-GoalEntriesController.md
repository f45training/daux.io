app\controllers\GoalEntriesController
===============

Base class for controllers housing common functions.




* Class name: GoalEntriesController
* Namespace: app\controllers
* Parent class: [app\controllers\Rest](app-controllers-Rest.md)





Properties
----------


### $disabled_api_update_items

    public mixed $disabled_api_update_items = array('goal_id', 'date', 'targetdate', 'facebooklikes', 'averagefeedbackscore')





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




### edit

    mixed app\controllers\Rest::edit()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### update

    array app\controllers\Rest::update()

Update details of the specific controller extending Rest class



* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### update_fb_likes

    mixed app\controllers\GoalEntriesController::update_fb_likes()





* Visibility: **public**




### updateLikes

    mixed app\controllers\GoalEntriesController::updateLikes($goal)





* Visibility: **public**


#### Arguments
* $goal **mixed**



### check_goal_entry

    mixed app\controllers\GoalEntriesController::check_goal_entry($goal_id)





* Visibility: **public**


#### Arguments
* $goal_id **mixed**



### get_facebook_page_likes

    mixed app\controllers\GoalEntriesController::get_facebook_page_likes($page_url)





* Visibility: **public**


#### Arguments
* $page_url **mixed**



### by_goal

    mixed app\controllers\GoalEntriesController::by_goal()





* Visibility: **public**




### create_goal_entries

    mixed app\controllers\GoalEntriesController::create_goal_entries($goal_id)





* Visibility: **public**


#### Arguments
* $goal_id **mixed**



### check_entry

    mixed app\controllers\GoalEntriesController::check_entry($goal_id, $start_date, $gym_id)





* Visibility: **public**


#### Arguments
* $goal_id **mixed**
* $start_date **mixed**
* $gym_id **mixed**



### create_next_sunday

    mixed app\controllers\GoalEntriesController::create_next_sunday($goal_id, $date)





* Visibility: **public**


#### Arguments
* $goal_id **mixed**
* $date **mixed**



### create_entry

    mixed app\controllers\GoalEntriesController::create_entry($goal_id, $start_date)





* Visibility: **public**


#### Arguments
* $goal_id **mixed**
* $start_date **mixed**



### fetch_goal_setting

    mixed app\controllers\GoalEntriesController::fetch_goal_setting($goal_id)





* Visibility: **public**


#### Arguments
* $goal_id **mixed**



### by_range

    mixed app\controllers\GoalEntriesController::by_range()





* Visibility: **public**




### index

    mixed app\controllers\Rest::index()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### view

    mixed app\controllers\Rest::view()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### search

    mixed app\controllers\Rest::search()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### add

    mixed app\controllers\Rest::add()





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



