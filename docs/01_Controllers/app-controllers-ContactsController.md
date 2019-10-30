app\controllers\ContactsController
===============

Base class for controllers housing common functions.




* Class name: ContactsController
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


### syncContacts

    \app\controllers\data app\controllers\ContactsController::syncContacts()

get all categories from freshdesk



* Visibility: **public**




### snycCompanyId

    mixed app\controllers\ContactsController::snycCompanyId()





* Visibility: **public**




### checkCompany

    mixed app\controllers\ContactsController::checkCompany($id, $c_id)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $c_id **mixed**



### lookUpFranchisees

    mixed app\controllers\ContactsController::lookUpFranchisees($franchisee_name)





* Visibility: **public**


#### Arguments
* $franchisee_name **mixed**



### checkContactExist

    mixed app\controllers\ContactsController::checkContactExist($email)





* Visibility: **public**


#### Arguments
* $email **mixed**



### freshdeskCompanies

    mixed app\controllers\ContactsController::freshdeskCompanies()





* Visibility: **public**




### allCategories

    mixed app\controllers\ContactsController::allCategories()





* Visibility: **public**




### allSolutions

    \app\controllers\data app\controllers\ContactsController::allSolutions()

get all solution articles



* Visibility: **public**




### createTicket

    \app\controllers\success app\controllers\ContactsController::createTicket()

create a ticket to freshdesk
save logs



* Visibility: **public**




### customersByName

    \app\controllers\customer app\controllers\ContactsController::customersByName($data)

Search customers by name



* Visibility: **public**


#### Arguments
* $data **mixed**



### addCustomer

    \app\controllers\response app\controllers\ContactsController::addCustomer($data)

Add new customer



* Visibility: **public**


#### Arguments
* $data **mixed**



### usersByName

    \app\controllers\id app\controllers\ContactsController::usersByName(\app\controllers\data $data)

Search contacts



* Visibility: **public**


#### Arguments
* $data **app\controllers\data** - &lt;p&gt;array&lt;/p&gt;



### createUser

     app\controllers\ContactsController::createUser(\app\controllers\data $data)

Create user in freshdesk



* Visibility: **public**


#### Arguments
* $data **app\controllers\data** - &lt;p&gt;array&lt;/p&gt;



### updateUser

    mixed app\controllers\ContactsController::updateUser($data)

Update contact customer id info



* Visibility: **public**


#### Arguments
* $data **mixed**



### getUser

    \app\controllers\data app\controllers\ContactsController::getUser(\app\controllers\id $id)

Get Contact info



* Visibility: **public**


#### Arguments
* $id **app\controllers\id** - &lt;p&gt;(float) id of user in freshdesk&lt;/p&gt;



### getFreshDeskTickets

    \app\controllers\data app\controllers\ContactsController::getFreshDeskTickets()

Get tickets



* Visibility: **public**




### hookToZapier

    mixed app\controllers\ContactsController::hookToZapier($data)





* Visibility: **private**


#### Arguments
* $data **mixed**



### pageArchive

    mixed app\controllers\ContactsController::pageArchive()





* Visibility: **public**




### getArchive

    mixed app\controllers\ContactsController::getArchive()





* Visibility: **public**




### getArchivesSummary

    mixed app\controllers\ContactsController::getArchivesSummary()





* Visibility: **public**




### getTicketData

    mixed app\controllers\ContactsController::getTicketData($mime_boundary, $tickets)





* Visibility: **private**


#### Arguments
* $mime_boundary **mixed**
* $tickets **mixed**



### user_synced

    boolean app\controllers\ContactsController::user_synced($id)

Update franchisee users if success sync api



* Visibility: **public**


#### Arguments
* $id **mixed**



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



