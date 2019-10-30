app\controllers\DivisionsController
===============

Base class for controllers housing common functions.




* Class name: DivisionsController
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




### pricing

    mixed app\controllers\DivisionsController::pricing()

Save Pricing
Method: POST
v1/divisions/pricing



* Visibility: **public**




### captainManager

    mixed app\controllers\DivisionsController::captainManager()

Save Captain and Manager
Method: POST
v1/divisions/captainManager



* Visibility: **public**




### search

    mixed app\controllers\Rest::search()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### create

    \app\controllers\$success app\controllers\DivisionsController::create($data)

Create Divisions



* Visibility: **public**


#### Arguments
* $data **mixed** - &lt;p&gt;(array)&lt;/p&gt;



### updateData

    \app\controllers\$success app\controllers\DivisionsController::updateData($conditions, $data)

Update Division



* Visibility: **public**


#### Arguments
* $conditions **mixed** - &lt;p&gt;(arraay)&lt;/p&gt;
* $data **mixed** - &lt;p&gt;(array)&lt;/p&gt;



### meetings

    mixed app\controllers\DivisionsController::meetings()

Feedback Forms

List of all feedback forms for divisions

* Visibility: **public**




### meetings_klip

    mixed app\controllers\DivisionsController::meetings_klip()

Klipfolio Division Report

List of all divisions report ready for Klipfolio

* Visibility: **public**




### validateDate

    mixed app\controllers\DivisionsController::validateDate($date)





* Visibility: **private**


#### Arguments
* $date **mixed**



### meetingsCreate

    mixed app\controllers\DivisionsController::meetingsCreate()

Feedback Forms Create

Create new fillable forms

* Visibility: **public**




### meetingsAdd

    mixed app\controllers\DivisionsController::meetingsAdd()

Feedback Forms Add or Update

Insert new fillable forms, if id is set, make this as update action.

* Visibility: **public**




### saveFormAnswers

    mixed app\controllers\DivisionsController::saveFormAnswers()

Division captain feedback forms answers

v1/divisions/forms/answers/{:id:[0-9]+}/{:respondent:}

* Visibility: **public**




### getMeetings

    mixed app\controllers\DivisionsController::getMeetings()

Division meeting most recent

v1/divisions/{:status:}(recent, next)/meetings/{:division_number:[0-9]+}

* Visibility: **public**




### saveNotes

    mixed app\controllers\DivisionsController::saveNotes()

Division Meeting Notes

Method: POST
division/meetings/{:meeting_id:[0-9]+}/notes

Save Notes Per Agenda

* Visibility: **public**




### getNotes

    mixed app\controllers\DivisionsController::getNotes()

Division Meeting Notes

Method: GET
division/meetings/{:meeting_id:[0-9]+}/notes/{:franchisee_id:[0-9]+}

Get Notes Per Agenda

* Visibility: **public**




### saveMeetingGoing

    mixed app\controllers\DivisionsController::saveMeetingGoing()

Save MeetingGoing

Method: POST
divisions/meetings/{:meeting_id:}/going

* Visibility: **public**




### meetingsEdit

    mixed app\controllers\DivisionsController::meetingsEdit()

Meetings Edit



* Visibility: **public**




### getFranchisees

    mixed app\controllers\DivisionsController::getFranchisees($id)

Return all franchisees under that division
v1/divisions/{:id:[0-9+]}/franchisees



* Visibility: **public**


#### Arguments
* $id **mixed** - &lt;p&gt;(integer) division number
Method: GET&lt;/p&gt;



### events

    mixed app\controllers\DivisionsController::events()

Get Events Per Division

v1/divisions/:franchisee_id:[0-9]+/meetings/limit/{:limit:[0-9]+}

* Visibility: **public**




### getNotReplied

    mixed app\controllers\DivisionsController::getNotReplied()

Get Users of Gyms who haven't replied for upcoming meetings



* Visibility: **public**




### _init

    mixed app\controllers\Rest::_init()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### view

    mixed app\controllers\Rest::view()





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



