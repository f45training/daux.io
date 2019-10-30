app\controllers\QuickBloxController
===============

Base class for controllers housing common functions.




* Class name: QuickBloxController
* Namespace: app\controllers
* Parent class: [app\controllers\Rest](app-controllers-Rest.md)





Properties
----------


### $authSecret

    private mixed $authSecret = 'P7KdGVEAvpzyKgk'





* Visibility: **private**
* This property is **static**.


### $auth_key

    private mixed $auth_key = 'XjPukjwC8u3HQLK'





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




### getSignature

    mixed app\controllers\QuickBloxController::getSignature()





* Visibility: **private**
* This method is **static**.




### account

    mixed app\controllers\QuickBloxController::account()





* Visibility: **public**




### authenticate

    mixed app\controllers\QuickBloxController::authenticate()





* Visibility: **public**




### getStudioUserData

    mixed app\controllers\QuickBloxController::getStudioUserData($id)





* Visibility: **public**


#### Arguments
* $id **mixed**



### add_user

    mixed app\controllers\QuickBloxController::add_user()





* Visibility: **public**




### get_user

    mixed app\controllers\QuickBloxController::get_user()





* Visibility: **public**




### getChannels

    mixed app\controllers\QuickBloxController::getChannels($id_channels)





* Visibility: **public**


#### Arguments
* $id_channels **mixed**



### save_channel

    mixed app\controllers\QuickBloxController::save_channel($entry_data)





* Visibility: **public**


#### Arguments
* $entry_data **mixed**



### update_studio

    mixed app\controllers\QuickBloxController::update_studio($gym_id, $fields)





* Visibility: **public**


#### Arguments
* $gym_id **mixed**
* $fields **mixed**



### create_qb_user

    mixed app\controllers\QuickBloxController::create_qb_user($post_data)





* Visibility: **public**


#### Arguments
* $post_data **mixed**



### create_chat

    mixed app\controllers\QuickBloxController::create_chat($name, $occupants_ids)





* Visibility: **public**


#### Arguments
* $name **mixed**
* $occupants_ids **mixed**



### retrieve_dialog

    mixed app\controllers\QuickBloxController::retrieve_dialog()





* Visibility: **public**




### update_dialog

    mixed app\controllers\QuickBloxController::update_dialog($dialog_id, $occupants_id)





* Visibility: **public**


#### Arguments
* $dialog_id **mixed**
* $occupants_id **mixed**



### show_dialog

    mixed app\controllers\QuickBloxController::show_dialog()





* Visibility: **public**




### delete_users

    mixed app\controllers\QuickBloxController::delete_users()





* Visibility: **public**




### delete_dialog

    mixed app\controllers\QuickBloxController::delete_dialog()





* Visibility: **public**




### login_api_user

    mixed app\controllers\QuickBloxController::login_api_user()





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




### edit

    mixed app\controllers\Rest::edit()





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



