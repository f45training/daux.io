app\controllers\EquipmentsController
===============

Base class for controllers housing common functions.




* Class name: EquipmentsController
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


### outputCSV

    mixed app\controllers\EquipmentsController::outputCSV($data)





* Visibility: **public**


#### Arguments
* $data **mixed**



### create

    mixed app\controllers\EquipmentsController::create()

Create new equipments
POST admin/equipments/create



* Visibility: **public**




### getFranchiseeEquipment

    mixed app\controllers\EquipmentsController::getFranchiseeEquipment()

Get Equipments By Franchisee and Equipment ID
GET v1/equipments/franchisee/{franchisee_id}/equipment/{equipment_id}



* Visibility: **public**




### saveFranchiseeEquipment

    mixed app\controllers\EquipmentsController::saveFranchiseeEquipment()

Save Equipment Changes on Payments
POST v1/equipments/franchisee/{franchisee_id}/equipment/{equipment_id}



* Visibility: **public**




### getAddress

    \app\controllers\($ch) app\controllers\EquipmentsController::getAddress(\app\controllers\($address) $address)

Equipment country



* Visibility: **public**


#### Arguments
* $address **app\controllers\($address)**



### manualEstimate

    mixed app\controllers\EquipmentsController::manualEstimate($district, $country)

Check Manual Estimate



* Visibility: **public**


#### Arguments
* $district **mixed**
* $country **mixed**



### equipmentHeaders

    mixed app\controllers\EquipmentsController::equipmentHeaders($franchisee_id, $data)





* Visibility: **public**


#### Arguments
* $franchisee_id **mixed**
* $data **mixed**



### orderForms

    mixed app\controllers\EquipmentsController::orderForms()

v1/equipments/forms/order/{:franchisee_id:}
method: POST



* Visibility: **public**




### saveEquipments

    mixed app\controllers\EquipmentsController::saveEquipments($items, $data)





* Visibility: **public**


#### Arguments
* $items **mixed**
* $data **mixed**



### insert

    mixed app\controllers\EquipmentsController::insert()





* Visibility: **public**




### getEstimates

    mixed app\controllers\EquipmentsController::getEstimates(array $data, $manual)

Get Estimate



* Visibility: **public**


#### Arguments
* $data **array** - &lt;p&gt;($data)&lt;/p&gt;
* $manual **mixed**



### setSupplier

    mixed app\controllers\EquipmentsController::setSupplier($suppliers, $data)

set supplier
create send quotation to suppliers



* Visibility: **public**


#### Arguments
* $suppliers **mixed**
* $data **mixed**



### sendOrders

    \app\controllers\$success app\controllers\EquipmentsController::sendOrders($data)

Send Email Orders to smai and tech@f45



* Visibility: **public**


#### Arguments
* $data **mixed** - &lt;p&gt;(array)&lt;/p&gt;



### invoicePdf

    mixed app\controllers\EquipmentsController::invoicePdf()





* Visibility: **public**




### changeFranchiseeEquipmentStatus

    mixed app\controllers\EquipmentsController::changeFranchiseeEquipmentStatus()

v1/equipments/franchisee/{:franchisee_id:}/changestatus/{:equipment_id:}/{:status_name:}
method: POST



* Visibility: **public**




### rename

    mixed app\controllers\EquipmentsController::rename()

Rename Existing Equipment



* Visibility: **public**




### purchaseOrder

    mixed app\controllers\EquipmentsController::purchaseOrder()

Get Information



* Visibility: **public**




### getEquipmentDetails

    mixed app\controllers\EquipmentsController::getEquipmentDetails()





* Visibility: **public**




### saveEquipmentDetails

    mixed app\controllers\EquipmentsController::saveEquipmentDetails()





* Visibility: **public**




### saveAllEarliestDate

    mixed app\controllers\EquipmentsController::saveAllEarliestDate()





* Visibility: **public**




### overview

    mixed app\controllers\EquipmentsController::overview()





* Visibility: **public**




### overall_status

    mixed app\controllers\EquipmentsController::overall_status()





* Visibility: **public**




### status

    mixed app\controllers\EquipmentsController::status()





* Visibility: **public**




### franchisees_equipment_details

    mixed app\controllers\EquipmentsController::franchisees_equipment_details()

Get Not Functioning Now Gym Equipment Details



* Visibility: **public**




### details

    mixed app\controllers\EquipmentsController::details()

Get details



* Visibility: **public**




### currencies

    mixed app\controllers\EquipmentsController::currencies()

Get Currencies



* Visibility: **public**




### names

    mixed app\controllers\EquipmentsController::names()

Equipment Names



* Visibility: **public**




### order

    mixed app\controllers\EquipmentsController::order()

Order Form Details



* Visibility: **public**




### is_paid

    mixed app\controllers\EquipmentsController::is_paid()





* Visibility: **public**




### pos

    mixed app\controllers\EquipmentsController::pos()





* Visibility: **public**




### confirmpo

    mixed app\controllers\EquipmentsController::confirmpo()





* Visibility: **public**




### dash_green_light

    mixed app\controllers\EquipmentsController::dash_green_light()





* Visibility: **public**




### dash_table

    mixed app\controllers\EquipmentsController::dash_table()





* Visibility: **public**




### get_studio_no_equipments

    mixed app\controllers\EquipmentsController::get_studio_no_equipments()





* Visibility: **public**




### accounts_payable

    mixed app\controllers\EquipmentsController::accounts_payable()





* Visibility: **public**




### accounts_payable_details

    mixed app\controllers\EquipmentsController::accounts_payable_details()





* Visibility: **public**




### exportaccountspayables

    mixed app\controllers\EquipmentsController::exportaccountspayables()





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



