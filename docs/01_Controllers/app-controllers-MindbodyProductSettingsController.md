app\controllers\MindbodyProductSettingsController
===============

Base class for controllers housing common functions.




* Class name: MindbodyProductSettingsController
* Namespace: app\controllers
* Parent class: [app\controllers\Rest](app-controllers-Rest.md)



Constants
----------


### F45TRAINING_SMS_FROM_NUMBER

    const F45TRAINING_SMS_FROM_NUMBER = 14582073084





### TEST_STUDIOS

    const TEST_STUDIOS = array(200, 1002)





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


### send_email_lead_notif

    mixed app\controllers\MindbodyProductSettingsController::send_email_lead_notif()

Send Email Lead Notification



* Visibility: **public**




### trigger_email_lead_notif

    mixed app\controllers\MindbodyProductSettingsController::trigger_email_lead_notif()

Trigger Email Lead Notification



* Visibility: **public**




### trigger_send_email_lead_notif

    mixed app\controllers\MindbodyProductSettingsController::trigger_send_email_lead_notif($data, $is_send_email)

Trigger Send Email Lead Notification



* Visibility: **public**


#### Arguments
* $data **mixed**
* $is_send_email **mixed**



### check_lead_status

    mixed app\controllers\MindbodyProductSettingsController::check_lead_status()

Check Lead Status
/v1/mindbody_product/check_lead_status/{:id:[0-9]+}



* Visibility: **public**




### setBaseAPIUrl

    mixed app\controllers\MindbodyProductSettingsController::setBaseAPIUrl()





* Visibility: **public**




### send_email_mindbody_notif

    mixed app\controllers\MindbodyProductSettingsController::send_email_mindbody_notif()

Send Email Mindbody Notification



* Visibility: **public**




### set_email_notification

    mixed app\controllers\MindbodyProductSettingsController::set_email_notification()

Set Email Notification



* Visibility: **public**




### send_dummy_notification

    mixed app\controllers\MindbodyProductSettingsController::send_dummy_notification()

Send dummy email notification



* Visibility: **public**




### test_webhook_url

    mixed app\controllers\MindbodyProductSettingsController::test_webhook_url($url, $_data)





* Visibility: **public**


#### Arguments
* $url **mixed**
* $_data **mixed**



### getMindbodyRequiredFields

    mixed app\controllers\MindbodyProductSettingsController::getMindbodyRequiredFields()





* Visibility: **public**




### get_studio_name

    mixed app\controllers\MindbodyProductSettingsController::get_studio_name($page_id)





* Visibility: **public**


#### Arguments
* $page_id **mixed**



### facebook_webhook

    mixed app\controllers\MindbodyProductSettingsController::facebook_webhook()





* Visibility: **public**




### save_fb_lead

    mixed app\controllers\MindbodyProductSettingsController::save_fb_lead($token, $data)





* Visibility: **public**


#### Arguments
* $token **mixed**
* $data **mixed**



### generate_connect_app_token

    mixed app\controllers\MindbodyProductSettingsController::generate_connect_app_token()





* Visibility: **public**




### set_fb_context_card

    mixed app\controllers\MindbodyProductSettingsController::set_fb_context_card($page_id, $healcode)





* Visibility: **public**


#### Arguments
* $page_id **mixed**
* $healcode **mixed**



### set_fb_legal_content

    mixed app\controllers\MindbodyProductSettingsController::set_fb_legal_content($page_id)





* Visibility: **public**


#### Arguments
* $page_id **mixed**



### set_fb_thank_card

    mixed app\controllers\MindbodyProductSettingsController::set_fb_thank_card($page_id, $slug)





* Visibility: **public**


#### Arguments
* $page_id **mixed**
* $slug **mixed**



### create_fb_lead_form

    mixed app\controllers\MindbodyProductSettingsController::create_fb_lead_form($page_id)





* Visibility: **public**


#### Arguments
* $page_id **mixed**



### getIsMarketingEnabled

    mixed app\controllers\MindbodyProductSettingsController::getIsMarketingEnabled()





* Visibility: **public**




### preopenemailautomation

    mixed app\controllers\MindbodyProductSettingsController::preopenemailautomation($data, $recipient)





* Visibility: **public**


#### Arguments
* $data **mixed**
* $recipient **mixed**



### openemailautomation

    mixed app\controllers\MindbodyProductSettingsController::openemailautomation($data, $recipient)





* Visibility: **public**


#### Arguments
* $data **mixed**
* $recipient **mixed**



### preopensmsautomation

    mixed app\controllers\MindbodyProductSettingsController::preopensmsautomation($data)





* Visibility: **public**


#### Arguments
* $data **mixed**



### opensmsautomation

    mixed app\controllers\MindbodyProductSettingsController::opensmsautomation($data)





* Visibility: **public**


#### Arguments
* $data **mixed**



### isProdigy

    mixed app\controllers\MindbodyProductSettingsController::isProdigy()

Check if Prodigy
/v1/mindbody_product/is_prodigy/{:id:[0-9]+}



* Visibility: **public**




### _init

    mixed app\controllers\Rest::_init()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




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



