app\controllers\LionheartController
===============

Contains actions used for Lionheart, including APIs




* Class name: LionheartController
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


### _init

    mixed app\controllers\Rest::_init()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### index

    mixed app\controllers\Rest::index()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### lionheart_studios

    \app\controllers\[type] app\controllers\LionheartController::lionheart_studios()

List of studios



* Visibility: **public**




### sessions_per_week

    \app\controllers\[type] app\controllers\LionheartController::sessions_per_week()

Sessions per week graph



* Visibility: **public**




### studios_per_week

    \app\controllers\[type] app\controllers\LionheartController::studios_per_week()

Studios per week graph



* Visibility: **public**




### users_per_week

    \app\controllers\[type] app\controllers\LionheartController::users_per_week()

Users per week graph



* Visibility: **public**




### users_per_month

    mixed app\controllers\LionheartController::users_per_month()





* Visibility: **public**




### user_sessions_per_week

    \app\controllers\[JSON] app\controllers\LionheartController::user_sessions_per_week()

User sessions per week graph



* Visibility: **public**




### users

    mixed app\controllers\LionheartController::users()

For Lionheart Users



* Visibility: **public**




### export_users

    mixed app\controllers\LionheartController::export_users()

Export users



* Visibility: **public**




### calculateAge

    mixed app\controllers\LionheartController::calculateAge($date)

Get age from the User Collection



* Visibility: **private**


#### Arguments
* $date **mixed**



### createCarbonDateFromMongoId

    \app\controllers\[Carbon app\controllers\LionheartController::createCarbonDateFromMongoId($id)

Create date from MongoID to Carbon Date



* Visibility: **private**


#### Arguments
* $id **mixed**



### createMongoId

    \app\controllers\[MongoObjectID] app\controllers\LionheartController::createMongoId($yourTimestamp)

Create Mongo ID from timestamp



* Visibility: **private**


#### Arguments
* $yourTimestamp **mixed**



### getActiveFranchisees

    \app\controllers\[type] app\controllers\LionheartController::getActiveFranchisees()

Get active franchisees



* Visibility: **private**




### getMongoConnection

    \app\controllers\[type] app\controllers\LionheartController::getMongoConnection()

Get mongo connection



* Visibility: **private**




### getLionheartPercentage

    mixed app\controllers\LionheartController::getLionheartPercentage()





* Visibility: **public**




### computeAge

    mixed app\controllers\LionheartController::computeAge($dob)





* Visibility: **private**


#### Arguments
* $dob **mixed**



### computeMaxHeartRate

    mixed app\controllers\LionheartController::computeMaxHeartRate($dob)





* Visibility: **private**


#### Arguments
* $dob **mixed**



### convertMongoDatesToString

    mixed app\controllers\LionheartController::convertMongoDatesToString($date, $format)





* Visibility: **private**


#### Arguments
* $date **mixed**
* $format **mixed**



### getLionheartStudioUsers

    array app\controllers\LionheartController::getLionheartStudioUsers()

Gets the list of studio users from mongodb



* Visibility: **public**




### getLionheartUserDetails

    mixed app\controllers\LionheartController::getLionheartUserDetails()





* Visibility: **public**




### updateLionheartUser

    mixed app\controllers\LionheartController::updateLionheartUser()





* Visibility: **public**




### getUserAnalytics

    array app\controllers\LionheartController::getUserAnalytics()

Gets the analytics for a specific user, filtered by the frachisees of the current logged in



* Visibility: **public**




### updateFranchiseeObject

    mixed app\controllers\LionheartController::updateFranchiseeObject()





* Visibility: **public**




### export_collection

    mixed app\controllers\LionheartController::export_collection()





* Visibility: **public**




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



