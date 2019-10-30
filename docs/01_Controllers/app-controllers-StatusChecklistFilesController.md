app\controllers\StatusChecklistFilesController
===============

Base class for controllers housing common functions.




* Class name: StatusChecklistFilesController
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


### getByFranchisee

    mixed app\controllers\StatusChecklistFilesController::getByFranchisee()





* Visibility: **public**




### add

    mixed app\controllers\Rest::add()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### sendApprovalRequest

    mixed app\controllers\StatusChecklistFilesController::sendApprovalRequest($data)





* Visibility: **public**


#### Arguments
* $data **mixed**



### sendEmail

    mixed app\controllers\StatusChecklistFilesController::sendEmail(\app\controllers\file $data)

Sends email using sparkpost



* Visibility: **public**


#### Arguments
* $data **app\controllers\file** - &lt;p&gt;array&lt;/p&gt;



### getActionUrl

    mixed app\controllers\StatusChecklistFilesController::getActionUrl($franchise_id, $status_id, $user_id, $is_approved, $sub)





* Visibility: **public**


#### Arguments
* $franchise_id **mixed**
* $status_id **mixed**
* $user_id **mixed**
* $is_approved **mixed**
* $sub **mixed**



### approveStatus

    mixed app\controllers\StatusChecklistFilesController::approveStatus()

Approve Checklist
API v1/status-checklist/approve/franchise_id/status_id



* Visibility: **public**




### saveStatusChecklistsLogs

    boolean app\controllers\StatusChecklistFilesController::saveStatusChecklistsLogs(\app\controllers\[$status_id] $status_id, \app\controllers\[$userData] $username, \app\controllers\[$franchisee_id] $franchisee_id)

Save status checklists logs



* Visibility: **public**


#### Arguments
* $status_id **app\controllers\[$status_id]** - &lt;p&gt;[ status checklist id ]&lt;/p&gt;
* $username **app\controllers\[$userData]** - &lt;p&gt;[ user login data ]&lt;/p&gt;
* $franchisee_id **app\controllers\[$franchisee_id]** - &lt;p&gt;[ franchisee id ]&lt;/p&gt;



### chekAllSubChecklist

    mixed app\controllers\StatusChecklistFilesController::chekAllSubChecklist($franchise_id, $status_id, $user_id, $sub_checklist_id)





* Visibility: **public**


#### Arguments
* $franchise_id **mixed**
* $status_id **mixed**
* $user_id **mixed**
* $sub_checklist_id **mixed**



### emailApprovalNotification

    mixed app\controllers\StatusChecklistFilesController::emailApprovalNotification($host, $franchisee, $approval_name)





* Visibility: **public**


#### Arguments
* $host **mixed**
* $franchisee **mixed**
* $approval_name **mixed**



### sendCompletePreOpenEmail

    mixed app\controllers\StatusChecklistFilesController::sendCompletePreOpenEmail()





* Visibility: **public**




### sendCompletePreOpenEmail_v2

    mixed app\controllers\StatusChecklistFilesController::sendCompletePreOpenEmail_v2()





* Visibility: **public**




### downloadPreOpenPdf

    mixed app\controllers\StatusChecklistFilesController::downloadPreOpenPdf()





* Visibility: **public**




### getFacebookLikes

    mixed app\controllers\StatusChecklistFilesController::getFacebookLikes($facebookurl)





* Visibility: **private**


#### Arguments
* $facebookurl **mixed**



### getInstagramFollowers

    mixed app\controllers\StatusChecklistFilesController::getInstagramFollowers($instagramname)





* Visibility: **private**


#### Arguments
* $instagramname **mixed**



### setSchedulePreOpen

    mixed app\controllers\StatusChecklistFilesController::setSchedulePreOpen()





* Visibility: **public**




### cancelApproval

    mixed app\controllers\StatusChecklistFilesController::cancelApproval()





* Visibility: **public**




### checkEmailEnv

    mixed app\controllers\StatusChecklistFilesController::checkEmailEnv($email_sent, $user_email)





* Visibility: **public**


#### Arguments
* $email_sent **mixed**
* $user_email **mixed**



### logs

    mixed app\controllers\StatusChecklistFilesController::logs()





* Visibility: **public**




### statusChecklistReports

    mixed app\controllers\StatusChecklistFilesController::statusChecklistReports()





* Visibility: **public**




### postApprovedSignage

    \app\controllers\[type] app\controllers\StatusChecklistFilesController::postApprovedSignage()

Update Signage Checklist



* Visibility: **public**




### download

    mixed app\controllers\StatusChecklistFilesController::download()





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



