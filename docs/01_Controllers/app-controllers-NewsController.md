app\controllers\NewsController
===============

Base class for controllers housing common functions.




* Class name: NewsController
* Namespace: app\controllers
* Parent class: [app\controllers\Rest](app-controllers-Rest.md)





Properties
----------


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




### get_news

    mixed app\controllers\NewsController::get_news()





* Visibility: **public**




### get_news_read

    mixed app\controllers\NewsController::get_news_read()





* Visibility: **public**




### get_news_add

    mixed app\controllers\NewsController::get_news_add()





* Visibility: **public**




### get_all_news_read

    mixed app\controllers\NewsController::get_all_news_read()





* Visibility: **public**




### get_total_count_recipients

    \app\controllers\[type] app\controllers\NewsController::get_total_count_recipients()

Get Total expected recipients



* Visibility: **public**




### get_recipients_news

    \app\controllers\[type] app\controllers\NewsController::get_recipients_news()

Get user emails by `user_id` default returns
all emails



* Visibility: **public**




### get_news_messages

    \app\controllers\[type] app\controllers\NewsController::get_news_messages()

Retrieve news notification messages



* Visibility: **public**




### news_inbox_reply

    mixed app\controllers\NewsController::news_inbox_reply()

Handles Inbox reply api



* Visibility: **public**




### weekly_unread_news

    \app\controllers\[type] app\controllers\NewsController::weekly_unread_news()

Returns weekly unread news



* Visibility: **public**




### checkEnv

    mixed app\controllers\NewsController::checkEnv()





* Visibility: **public**




### getNewsFromCampaignMonitor

    mixed app\controllers\NewsController::getNewsFromCampaignMonitor()

Get news from Campaign Monitor

Get news directly from campaign monitor API

* Visibility: **public**




### getNewsFromCampaignMonitorByEmail

    mixed app\controllers\NewsController::getNewsFromCampaignMonitorByEmail()

Get news from Campaign Monitor by Email

Get news directly from campaign monitor API

* Visibility: **public**




### getCampaignDetails

    mixed app\controllers\NewsController::getCampaignDetails()

Get Campaign news by campaign ID



* Visibility: **public**




### sendReplyToCampaignMonitor

    mixed app\controllers\NewsController::sendReplyToCampaignMonitor()

Send reply to campaign



* Visibility: **public**




### _init

    mixed app\controllers\Rest::_init()





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



