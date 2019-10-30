app\controllers\UsersController
===============

Base class for controllers housing common functions.




* Class name: UsersController
* Namespace: app\controllers
* Parent class: [app\controllers\Rest](app-controllers-Rest.md)





Properties
----------


### $disAllowed

    public mixed $disAllowed = array()





* Visibility: **public**


### $dataExclude

    public mixed $dataExclude = array()





* Visibility: **public**


### $sendbird_token

    private mixed $sendbird_token = '780815c9df6641889cb816857dcf8490afd78e50'





* Visibility: **private**
* This property is **static**.


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


### index

    mixed app\controllers\Rest::index()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### add

    mixed app\controllers\Rest::add()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### update

    array app\controllers\Rest::update()

Update details of the specific controller extending Rest class



* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### checkEmailEnvSupport

    mixed app\controllers\UsersController::checkEmailEnvSupport()





* Visibility: **public**




### edit

    mixed app\controllers\Rest::edit()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### get

    mixed app\controllers\UsersController::get()





* Visibility: **public**




### types

    mixed app\controllers\UsersController::types()





* Visibility: **public**




### by_user

    mixed app\controllers\UsersController::by_user()





* Visibility: **public**




### by_franchisee

    mixed app\controllers\UsersController::by_franchisee()





* Visibility: **public**




### campaign

    array app\controllers\UsersController::campaign(integer $page, integer $total, array $data)

Sync Campaign Monitor
v1/users/campaign



* Visibility: **public**


#### Arguments
* $page **integer**
* $total **integer**
* $data **array**



### campaignActive

    \app\controllers\(array) app\controllers\UsersController::campaignActive(\app\controllers\(array) $result, $list_id, $emails)

Set campaing monitor users to active



* Visibility: **public**


#### Arguments
* $result **app\controllers\(array)**
* $list_id **mixed**
* $emails **mixed**



### delete

    mixed app\controllers\Rest::delete()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### checkSendBirdUser

    mixed app\controllers\UsersController::checkSendBirdUser()





* Visibility: **public**




### getStudioUserData

    mixed app\controllers\UsersController::getStudioUserData()





* Visibility: **public**




### getChannel

    mixed app\controllers\UsersController::getChannel($id_channel)





* Visibility: **public**


#### Arguments
* $id_channel **mixed**



### viewUserInformation

    mixed app\controllers\UsersController::viewUserInformation()





* Visibility: **public**




### viewChannelInformation

    mixed app\controllers\UsersController::viewChannelInformation()





* Visibility: **public**




### viewMessagingInformation

    mixed app\controllers\UsersController::viewMessagingInformation()





* Visibility: **public**




### channelList

    mixed app\controllers\UsersController::channelList()





* Visibility: **public**




### getChannelStudios

    mixed app\controllers\UsersController::getChannelStudios()





* Visibility: **public**




### createChannel

    mixed app\controllers\UsersController::createChannel()





* Visibility: **public**




### createMessaging

    mixed app\controllers\UsersController::createMessaging()





* Visibility: **public**




### createUser

    mixed app\controllers\UsersController::createUser()





* Visibility: **public**




### inviteUsers

    mixed app\controllers\UsersController::inviteUsers()





* Visibility: **public**




### leaveUsers

    mixed app\controllers\UsersController::leaveUsers()





* Visibility: **public**




### getUserDivisionInformation

    mixed app\controllers\UsersController::getUserDivisionInformation()

Division Tab in Playbook
v1/sendbird/user_division/{user_id}
METHOD: GET



* Visibility: **public**




### update_user_password

    mixed app\controllers\UsersController::update_user_password()





* Visibility: **public**




### is_authenticated

    mixed app\controllers\UsersController::is_authenticated()

/v2/users/is_authenticated



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



