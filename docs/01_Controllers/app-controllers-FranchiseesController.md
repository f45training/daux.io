app\controllers\FranchiseesController
===============

Base class for controllers housing common functions.




* Class name: FranchiseesController
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


### $sortKey

    public mixed $sortKey = ""





* Visibility: **public**


### $geocodeData

    private mixed $geocodeData = array()





* Visibility: **private**


### $isShow

    private mixed $isShow = false





* Visibility: **private**


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


### _init

    mixed app\controllers\Rest::_init()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### get_equipments

    mixed app\controllers\FranchiseesController::get_equipments()

Will get list of equipments per franchisee
Will also see if the franchisee has ordered already



* Visibility: **public**




### franchiseStatus

    mixed app\controllers\FranchiseesController::franchiseStatus(\app\controllers\equipment_id $equipment_id, \app\controllers\status_id $status_id, \app\controllers\franchisee_id $franchisee_name, \app\controllers\franchisee_name $franchisee_email)

Franchise Status send email.



* Visibility: **public**


#### Arguments
* $equipment_id **app\controllers\equipment_id** - &lt;p&gt;(string) equipment id&lt;/p&gt;
* $status_id **app\controllers\status_id** - &lt;p&gt;(string) status id&lt;/p&gt;
* $franchisee_name **app\controllers\franchisee_id** - &lt;p&gt;(string) franchisee id&lt;/p&gt;
* $franchisee_email **app\controllers\franchisee_name** - &lt;p&gt;(string) studio name&lt;/p&gt;



### franchisePaid

    mixed app\controllers\FranchiseesController::franchisePaid($equipment_id, $franchisee_name, $franchisee_id)

Franchise Paid send email



* Visibility: **public**


#### Arguments
* $equipment_id **mixed** - &lt;p&gt;(string) equipment id&lt;/p&gt;
* $franchisee_name **mixed** - &lt;p&gt;(string) franchise&lt;/p&gt;
* $franchisee_id **mixed**



### lists

    mixed app\controllers\FranchiseesController::lists()





* Visibility: **public**




### save_equipments

    mixed app\controllers\FranchiseesController::save_equipments()





* Visibility: **public**




### sendSupplierEmail

    mixed app\controllers\FranchiseesController::sendSupplierEmail($id)

Send Supplier Email



* Visibility: **public**


#### Arguments
* $id **mixed**



### uploadInvoice

    mixed app\controllers\FranchiseesController::uploadInvoice()

Save Uploaded Invoices



* Visibility: **public**




### search

    mixed app\controllers\Rest::search()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### quickList

    mixed app\controllers\FranchiseesController::quickList()





* Visibility: **public**




### getTvInfo

    mixed app\controllers\FranchiseesController::getTvInfo()





* Visibility: **public**




### index

    mixed app\controllers\Rest::index()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### getTimeAgo

    mixed app\controllers\FranchiseesController::getTimeAgo($ptime)





* Visibility: **private**


#### Arguments
* $ptime **mixed**



### reports

    mixed app\controllers\FranchiseesController::reports()





* Visibility: **public**




### view

    mixed app\controllers\Rest::view()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### setExportAllSelectedQuery

    mixed app\controllers\FranchiseesController::setExportAllSelectedQuery($selectedItem)





* Visibility: **public**


#### Arguments
* $selectedItem **mixed**



### export

    \app\controllers\[type] app\controllers\FranchiseesController::export()

Handles export feature



* Visibility: **public**




### export_backup_orig

    mixed app\controllers\FranchiseesController::export_backup_orig()





* Visibility: **public**




### export_page

    mixed app\controllers\FranchiseesController::export_page()





* Visibility: **public**




### add

    mixed app\controllers\Rest::add()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### delete

    mixed app\controllers\Rest::delete()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### terminate

    mixed app\controllers\FranchiseesController::terminate()





* Visibility: **public**




### settings

    mixed app\controllers\FranchiseesController::settings()





* Visibility: **public**




### licenses_old

    mixed app\controllers\FranchiseesController::licenses_old()

Licenses Page



* Visibility: **public**




### f45tv

    mixed app\controllers\FranchiseesController::f45tv()

F45TV Page



* Visibility: **public**




### gym_schedules

    mixed app\controllers\FranchiseesController::gym_schedules()

F45TV Schedule Page



* Visibility: **public**




### equipment_order_logs

    mixed app\controllers\FranchiseesController::equipment_order_logs()

F45 Equipment Logs



* Visibility: **public**




### f4tv_permission_trigger

    mixed app\controllers\FranchiseesController::f4tv_permission_trigger()





* Visibility: **public**




### pusherClearFilesTV

    mixed app\controllers\FranchiseesController::pusherClearFilesTV()





* Visibility: **public**




### pusherTV

    mixed app\controllers\FranchiseesController::pusherTV()





* Visibility: **public**




### pusherGetLogsTv

    mixed app\controllers\FranchiseesController::pusherGetLogsTv()





* Visibility: **public**




### androidLogs

    mixed app\controllers\FranchiseesController::androidLogs()





* Visibility: **public**




### website

    mixed app\controllers\FranchiseesController::website()

Website Page



* Visibility: **public**




### franchisee_type_access

    mixed app\controllers\FranchiseesController::franchisee_type_access()





* Visibility: **public**




### update_schedule_google_business

    mixed app\controllers\FranchiseesController::update_schedule_google_business()





* Visibility: **public**




### set_google_business

    mixed app\controllers\FranchiseesController::set_google_business()





* Visibility: **public**




### leads

    mixed app\controllers\FranchiseesController::leads()

Leads Section (Old: Trial Signups)



* Visibility: **public**




### website_pending

    mixed app\controllers\FranchiseesController::website_pending()

Website Page



* Visibility: **public**




### logistics

    mixed app\controllers\FranchiseesController::logistics()

Logistics Page



* Visibility: **public**




### status

    mixed app\controllers\FranchiseesController::status()

Status Page



* Visibility: **public**




### status_checklist_logs_new

    mixed app\controllers\FranchiseesController::status_checklist_logs_new($limit)

Status Checklist Logs



* Visibility: **public**


#### Arguments
* $limit **mixed**



### users

    mixed app\controllers\FranchiseesController::users()

Users Page



* Visibility: **public**




### notes

    mixed app\controllers\FranchiseesController::notes()

Notes Page



* Visibility: **public**




### compliance

    mixed app\controllers\FranchiseesController::compliance()

Compliance Page



* Visibility: **public**




### equipment

    mixed app\controllers\FranchiseesController::equipment()

Equipments Page



* Visibility: **public**




### equipment_warnings

    mixed app\controllers\FranchiseesController::equipment_warnings()

Equipment Warnings Report



* Visibility: **public**




### payment

    mixed app\controllers\FranchiseesController::payment()

Payment Page



* Visibility: **public**




### studio_files

    mixed app\controllers\FranchiseesController::studio_files()

Studio Page



* Visibility: **public**




### photo_approvals

    \app\controllers\[type] app\controllers\FranchiseesController::photo_approvals()

Pending Photo Approvals Page



* Visibility: **public**




### injury_logs

    \app\controllers\[type] app\controllers\FranchiseesController::injury_logs()

Digital injury logs



* Visibility: **public**




### edit

    mixed app\controllers\Rest::edit()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### checkEmailEnv

    mixed app\controllers\FranchiseesController::checkEmailEnv($email_sent, $user_email)





* Visibility: **public**


#### Arguments
* $email_sent **mixed**
* $user_email **mixed**



### setOpeningDateExtend

    mixed app\controllers\FranchiseesController::setOpeningDateExtend()





* Visibility: **public**




### updateFranchiseeWeekWeekday

    \app\controllers\response app\controllers\FranchiseesController::updateFranchiseeWeekWeekday(object $franchisee)

This is the summary for a DocBlock.



* Visibility: **private**


#### Arguments
* $franchisee **object** - &lt;p&gt;franchisee&lt;/p&gt;



### saveFranchiseeSettings

    mixed app\controllers\FranchiseesController::saveFranchiseeSettings($data, $franchiseeId)





* Visibility: **public**


#### Arguments
* $data **mixed**
* $franchiseeId **mixed**



### update

    array app\controllers\Rest::update()

Update details of the specific controller extending Rest class



* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### sendOutboundEmail

    mixed app\controllers\FranchiseesController::sendOutboundEmail($template, $data, $subject, $email_sent)





* Visibility: **public**


#### Arguments
* $template **mixed**
* $data **mixed**
* $subject **mixed**
* $email_sent **mixed**



### completedReOpenProcess

    array app\controllers\FranchiseesController::completedReOpenProcess(\app\controllers\[$status_id] $status_id, \app\controllers\[$franchisee] $franchisee)

Completion of required items for Re-open process
Note: Re-open inspection mandatory this becomes back to Pre-open Inspection



* Visibility: **public**


#### Arguments
* $status_id **app\controllers\[$status_id]** - &lt;p&gt;[Pre-open Inspection status checklist ID]&lt;/p&gt;
* $franchisee **app\controllers\[$franchisee]** - &lt;p&gt;[list of franchisee details]&lt;/p&gt;



### startReOpenProccess

    array app\controllers\FranchiseesController::startReOpenProccess(\app\controllers\[$status_id] $status_id, \app\controllers\[$franchisee] $franchisee, \app\controllers\[$date_re_open] $date_re_open, \app\controllers\[$checklist] $checklist, \app\controllers\[$sub_checklists] $sub_checklists)

RE-Open Process (see definition in DB `status_cheklists`)
Pre-open Inspection becomes Re-Open Inspection, some selected checklists to be re processed again
based on user desired to re processed will be unticked and files will go as an archived.



* Visibility: **public**


#### Arguments
* $status_id **app\controllers\[$status_id]** - &lt;p&gt;[Start Re-Open Process status checklist ID]&lt;/p&gt;
* $franchisee **app\controllers\[$franchisee]** - &lt;p&gt;[list of franchisee details]&lt;/p&gt;
* $date_re_open **app\controllers\[$date_re_open]** - &lt;p&gt;[Re-Open date value]&lt;/p&gt;
* $checklist **app\controllers\[$checklist]** - &lt;p&gt;[list of all ticked checklist]&lt;/p&gt;
* $sub_checklists **app\controllers\[$sub_checklists]** - &lt;p&gt;[list of all ticked sub checklist]&lt;/p&gt;



### archivedStatusChecklistFiles

    boolean app\controllers\FranchiseesController::archivedStatusChecklistFiles(\app\controllers\[$date_re_open] $date_re_open, \app\controllers\[$exclude_checklists] $exclude_checklists, \app\controllers\[$franchisee_id] $franchisee_id)

Archived Status Checklist files (for referrence) and to be able to do process again.



* Visibility: **public**


#### Arguments
* $date_re_open **app\controllers\[$date_re_open]** - &lt;p&gt;[Re-Open date value based on franchisee re-open]&lt;/p&gt;
* $exclude_checklists **app\controllers\[$exclude_checklists]** - &lt;p&gt;[ list of checklists to be re-proccessed]&lt;/p&gt;
* $franchisee_id **app\controllers\[$franchisee_id]**



### archivedStudioFiles

    boolean app\controllers\FranchiseesController::archivedStudioFiles(\app\controllers\[$date_re_open] $date_re_open, \app\controllers\[$franchisee_id] $franchisee_id)

Archived Studio files (for referrence) and to be able to do process again.



* Visibility: **public**


#### Arguments
* $date_re_open **app\controllers\[$date_re_open]** - &lt;p&gt;[Re-Open date value based on franchisee re-open]&lt;/p&gt;
* $franchisee_id **app\controllers\[$franchisee_id]**



### isInArray

    boolean app\controllers\FranchiseesController::isInArray(\app\controllers\[$needle] $needle, \app\controllers\[$haystack] $haystack)

check if element is in array



* Visibility: **public**


#### Arguments
* $needle **app\controllers\[$needle]** - &lt;p&gt;[ character or element you want to search in sequence]&lt;/p&gt;
* $haystack **app\controllers\[$haystack]** - &lt;p&gt;[ search array or the char sequence ]&lt;/p&gt;



### saveStatusChecklistsLogs

    boolean app\controllers\FranchiseesController::saveStatusChecklistsLogs(\app\controllers\[$status_id] $status_id, \app\controllers\[$userData] $username, \app\controllers\[$franchisee_id] $franchisee_id)

Save status checklists logs



* Visibility: **public**


#### Arguments
* $status_id **app\controllers\[$status_id]** - &lt;p&gt;[ status checklist id ]&lt;/p&gt;
* $username **app\controllers\[$userData]** - &lt;p&gt;[ user login data ]&lt;/p&gt;
* $franchisee_id **app\controllers\[$franchisee_id]** - &lt;p&gt;[ franchisee id ]&lt;/p&gt;



### pgl_upload_files

    mixed app\controllers\FranchiseesController::pgl_upload_files()





* Visibility: **public**




### getActionUrl

    mixed app\controllers\FranchiseesController::getActionUrl($franchise_id, $status_id, $user_id, $is_approved, $sub)





* Visibility: **public**


#### Arguments
* $franchise_id **mixed**
* $status_id **mixed**
* $user_id **mixed**
* $is_approved **mixed**
* $sub **mixed**



### emailApprovalNotification

    mixed app\controllers\FranchiseesController::emailApprovalNotification($franchisee, $approval_name)





* Visibility: **public**


#### Arguments
* $franchisee **mixed**
* $approval_name **mixed**



### getNearestLocation

    mixed app\controllers\FranchiseesController::getNearestLocation($latitude, $longitude, $franchisee_id)





* Visibility: **public**


#### Arguments
* $latitude **mixed**
* $longitude **mixed**
* $franchisee_id **mixed**



### getFacebookLikes

    mixed app\controllers\FranchiseesController::getFacebookLikes($facebookurl)





* Visibility: **private**


#### Arguments
* $facebookurl **mixed**



### getInstagramFollowers

    mixed app\controllers\FranchiseesController::getInstagramFollowers($instagramname, $studio_id)





* Visibility: **private**


#### Arguments
* $instagramname **mixed**
* $studio_id **mixed**



### login

    mixed app\controllers\FranchiseesController::login()





* Visibility: **public**




### playbook_logout

    mixed app\controllers\FranchiseesController::playbook_logout()





* Visibility: **public**




### playbook_login

    mixed app\controllers\FranchiseesController::playbook_login()





* Visibility: **public**




### forgot_password

    mixed app\controllers\FranchiseesController::forgot_password()





* Visibility: **public**




### reset_password

    mixed app\controllers\FranchiseesController::reset_password()





* Visibility: **public**




### update_password

    mixed app\controllers\FranchiseesController::update_password()





* Visibility: **public**




### get

    mixed app\controllers\FranchiseesController::get()





* Visibility: **public**




### update_gym_day

    mixed app\controllers\FranchiseesController::update_gym_day()





* Visibility: **public**




### updateWeekAndDay

    mixed app\controllers\FranchiseesController::updateWeekAndDay($franchisee)





* Visibility: **public**


#### Arguments
* $franchisee **mixed**



### update_fb_likes

    mixed app\controllers\FranchiseesController::update_fb_likes()





* Visibility: **public**




### updateLikes

    mixed app\controllers\FranchiseesController::updateLikes($franchisee)





* Visibility: **public**


#### Arguments
* $franchisee **mixed**



### get_facebook_page_likes

    mixed app\controllers\FranchiseesController::get_facebook_page_likes($page_url)





* Visibility: **public**


#### Arguments
* $page_url **mixed**



### live

    mixed app\controllers\FranchiseesController::live()





* Visibility: **public**




### getMindbodySite

    mixed app\controllers\FranchiseesController::getMindbodySite()





* Visibility: **public**




### getMindbodyActivation

    mixed app\controllers\FranchiseesController::getMindbodyActivation()





* Visibility: **public**




### deleteTimelineCache

    mixed app\controllers\FranchiseesController::deleteTimelineCache()

Delete predis cache on one click



* Visibility: **public**




### getChecklist

    \app\controllers\operation app\controllers\FranchiseesController::getChecklist()

Get all status checklist from a franchise through user email (freshdesk widget)
HTTP: GET v1/status-checklist/by-email/$user_email



* Visibility: **public**




### postChecklist

    mixed app\controllers\FranchiseesController::postChecklist()

save checklist from freshdesk widget
v1/status-checklist/by-email/$user_email



* Visibility: **public**




### ordinal_suffix

    mixed app\controllers\FranchiseesController::ordinal_suffix($num)





* Visibility: **public**


#### Arguments
* $num **mixed**



### syncStudio

    mixed app\controllers\FranchiseesController::syncStudio()

Sync none test studios to Algolia
franchisees/sync/studios



* Visibility: **public**




### checkExpiry

    mixed app\controllers\FranchiseesController::checkExpiry()





* Visibility: **public**




### orderedBySocialChecked

    mixed app\controllers\FranchiseesController::orderedBySocialChecked()

Get all franchisees ordered by oldest social checked



* Visibility: **public**




### updateSocialChecked

    mixed app\controllers\FranchiseesController::updateSocialChecked()

Update social checked for franchisee



* Visibility: **public**




### getPublicStudios

    mixed app\controllers\FranchiseesController::getPublicStudios()





* Visibility: **public**




### sortByKeyValue

    mixed app\controllers\FranchiseesController::sortByKeyValue($data)





* Visibility: **public**


#### Arguments
* $data **mixed**



### setSchedule

    mixed app\controllers\FranchiseesController::setSchedule()





* Visibility: **public**




### checkEnv

    mixed app\controllers\FranchiseesController::checkEnv()





* Visibility: **public**




### setPostCardSchedule

    mixed app\controllers\FranchiseesController::setPostCardSchedule()





* Visibility: **public**




### getAddressBreakdown

    mixed app\controllers\FranchiseesController::getAddressBreakdown($address, $array)





* Visibility: **public**


#### Arguments
* $address **mixed**
* $array **mixed**



### get_all_tv_caches

    \app\controllers\[type] app\controllers\FranchiseesController::get_all_tv_caches($redisFlag)

Return all studios tv info



* Visibility: **public**


#### Arguments
* $redisFlag **mixed**



### get_all_tv_caches2

    \app\controllers\[type] app\controllers\FranchiseesController::get_all_tv_caches2()

Requested to separate the new format to be called under
this endpoint



* Visibility: **public**




### getScreenCaches

    mixed app\controllers\FranchiseesController::getScreenCaches()





* Visibility: **public**




### franchisePaidAllEquipmentLines

    \app\controllers\others app\controllers\FranchiseesController::franchisePaidAllEquipmentLines($franchisee_name, $franchisee_email, $send_mail_data)

Franchise Paid All Equipment Lines send email



* Visibility: **private**


#### Arguments
* $franchisee_name **mixed** - &lt;p&gt;(string) franchise&lt;/p&gt;
* $franchisee_email **mixed**
* $send_mail_data **mixed**



### getRequestFingerprint

    mixed app\controllers\FranchiseesController::getRequestFingerprint(string $prefix)

This will get as much as possible a uniqye fingerprint from the current request



* Visibility: **private**


#### Arguments
* $prefix **string** - &lt;p&gt;optional prefix for the cache key defaults to &#039;playbook-login&#039;&lt;/p&gt;



### fullyPaidInvoice

    mixed app\controllers\FranchiseesController::fullyPaidInvoice()

Fully Paid Invoices



* Visibility: **public**




### invoices

    mixed app\controllers\FranchiseesController::invoices($header)





* Visibility: **public**


#### Arguments
* $header **mixed**



### invoices_detailed

    mixed app\controllers\FranchiseesController::invoices_detailed()





* Visibility: **public**




### updateFranchiseeInvoiceStatus

    mixed app\controllers\FranchiseesController::updateFranchiseeInvoiceStatus()





* Visibility: **public**




### franchiseInvoiceAdvance

    mixed app\controllers\FranchiseesController::franchiseInvoiceAdvance()





* Visibility: **public**




### franchiseInvoiceCurl

    mixed app\controllers\FranchiseesController::franchiseInvoiceCurl($results, $api_base, $date_now, $date_end, $tries)





* Visibility: **private**


#### Arguments
* $results **mixed**
* $api_base **mixed**
* $date_now **mixed**
* $date_end **mixed**
* $tries **mixed**



### franchiseInvoiceAdvanceOne

    mixed app\controllers\FranchiseesController::franchiseInvoiceAdvanceOne()





* Visibility: **public**




### getInvoiceTotal

    mixed app\controllers\FranchiseesController::getInvoiceTotal($invoice_details)





* Visibility: **private**


#### Arguments
* $invoice_details **mixed**



### calcTax

    mixed app\controllers\FranchiseesController::calcTax($price, $qty, $taxRate)





* Visibility: **private**


#### Arguments
* $price **mixed**
* $qty **mixed**
* $taxRate **mixed**



### addLineDetail

    mixed app\controllers\FranchiseesController::addLineDetail($invoice_details, $counter, $data)





* Visibility: **private**


#### Arguments
* $invoice_details **mixed**
* $counter **mixed**
* $data **mixed**



### setInvoiceIDReference

    mixed app\controllers\FranchiseesController::setInvoiceIDReference($franchisee_id, $invoice_id, $whole)





* Visibility: **private**


#### Arguments
* $franchisee_id **mixed**
* $invoice_id **mixed**
* $whole **mixed**



### get_new_studios

    \app\controllers\[type] app\controllers\FranchiseesController::get_new_studios()

This will return newly created studios (weekly)



* Visibility: **public**




### findGeoCodeByType

    \app\controllers\[type] app\controllers\FranchiseesController::findGeoCodeByType(\app\controllers\[type] $type)

Return address data by type



* Visibility: **public**


#### Arguments
* $type **app\controllers\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### getLocationAddress

    \app\controllers\[type] app\controllers\FranchiseesController::getLocationAddress(\app\controllers\[type] $location, \app\controllers\[type] $lat, \app\controllers\[type] $long)

Return geocode



* Visibility: **public**


#### Arguments
* $location **app\controllers\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $lat **app\controllers\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $long **app\controllers\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### send_email_conf

    \app\controllers\[type] app\controllers\FranchiseesController::send_email_conf()

Handles Email Confirmation
This sends out an email that contains all info in the SOLD ticket that are entered into Matrix - sent to key persons



* Visibility: **public**




### billing

    mixed app\controllers\FranchiseesController::billing()

Billing - Chargify



* Visibility: **public**




### get_all_open_studios

    \app\controllers\[type] app\controllers\FranchiseesController::get_all_open_studios()

Handles route for third party company
returns `gym` details



* Visibility: **public**




### get_all_countries

    mixed app\controllers\FranchiseesController::get_all_countries()





* Visibility: **public**




### get_all_regions

    mixed app\controllers\FranchiseesController::get_all_regions()





* Visibility: **public**




### get_all_timezones

    mixed app\controllers\FranchiseesController::get_all_timezones()





* Visibility: **public**




### countries_available

    mixed app\controllers\FranchiseesController::countries_available()





* Visibility: **public**




### equipment_po_list

    mixed app\controllers\FranchiseesController::equipment_po_list()





* Visibility: **public**




### updatePoStatusPaid

    mixed app\controllers\FranchiseesController::updatePoStatusPaid()





* Visibility: **public**




### exportpolist

    mixed app\controllers\FranchiseesController::exportpolist()





* Visibility: **public**




### equipment_billing_export

    mixed app\controllers\FranchiseesController::equipment_billing_export()





* Visibility: **public**




### exportequipmentbilling

    mixed app\controllers\FranchiseesController::exportequipmentbilling()





* Visibility: **public**




### outputCSV

    mixed app\controllers\FranchiseesController::outputCSV($data)





* Visibility: **public**


#### Arguments
* $data **mixed**



### agreements

    mixed app\controllers\FranchiseesController::agreements()





* Visibility: **public**




### redirect_license

    mixed app\controllers\FranchiseesController::redirect_license($id)





* Visibility: **public**


#### Arguments
* $id **mixed**



### licenses

    mixed app\controllers\FranchiseesController::licenses()





* Visibility: **public**




### post_socials_count

    \app\controllers\[type] app\controllers\FranchiseesController::post_socials_count()

Handles Count for Social Media



* Visibility: **public**




### social_user_search

    mixed app\controllers\FranchiseesController::social_user_search()

User search on social



* Visibility: **public**




### revenues

    mixed app\controllers\FranchiseesController::revenues()





* Visibility: **public**




### getActiveFranchisees

    mixed app\controllers\FranchiseesController::getActiveFranchisees()





* Visibility: **public**




### addLandingPage

    mixed app\controllers\FranchiseesController::addLandingPage()





* Visibility: **public**




### getLandingPagesByFranchisee

    mixed app\controllers\FranchiseesController::getLandingPagesByFranchisee()





* Visibility: **public**




### setLandingPageActive

    mixed app\controllers\FranchiseesController::setLandingPageActive()





* Visibility: **public**




### lease

    mixed app\controllers\FranchiseesController::lease()





* Visibility: **public**




### sendMailStudiosNotOpen

    mixed app\controllers\FranchiseesController::sendMailStudiosNotOpen()

Send email to studios that are not currently opened



* Visibility: **public**




### web_analytics

    mixed app\controllers\FranchiseesController::web_analytics()





* Visibility: **public**




### diagnostics

    mixed app\controllers\FranchiseesController::diagnostics()





* Visibility: **public**




### insurance

    mixed app\controllers\FranchiseesController::insurance()





* Visibility: **public**




### music_license

    mixed app\controllers\FranchiseesController::music_license()





* Visibility: **public**




### export_diagnostic

    mixed app\controllers\FranchiseesController::export_diagnostic()





* Visibility: **public**




### export_studios

    mixed app\controllers\FranchiseesController::export_studios()





* Visibility: **public**




### tickets

    mixed app\controllers\FranchiseesController::tickets($franchisee_id)





* Visibility: **public**


#### Arguments
* $franchisee_id **mixed**



### freshdesk_

    mixed app\controllers\FranchiseesController::freshdesk_($email, $page, $total)





* Visibility: **public**


#### Arguments
* $email **mixed**
* $page **mixed**
* $total **mixed**



### get_google_business_locations

    mixed app\controllers\FranchiseesController::get_google_business_locations()





* Visibility: **public**




### update_google_business

    mixed app\controllers\FranchiseesController::update_google_business()





* Visibility: **public**




### get_google_business_token

    mixed app\controllers\FranchiseesController::get_google_business_token($action)





* Visibility: **public**


#### Arguments
* $action **mixed**



### set_redirect_uri

    mixed app\controllers\FranchiseesController::set_redirect_uri()





* Visibility: **public**




### set_studio_google_my_business

    mixed app\controllers\FranchiseesController::set_studio_google_my_business()





* Visibility: **public**




### send_google_business_approval_request

    mixed app\controllers\FranchiseesController::send_google_business_approval_request($data)





* Visibility: **public**


#### Arguments
* $data **mixed**



### update_address

    mixed app\controllers\FranchiseesController::update_address()





* Visibility: **public**




### address_request_change

    mixed app\controllers\FranchiseesController::address_request_change()





* Visibility: **public**




### populate_notes

    mixed app\controllers\FranchiseesController::populate_notes()





* Visibility: **public**




### glofox

    mixed app\controllers\FranchiseesController::glofox()





* Visibility: **public**




### lionheart

    mixed app\controllers\FranchiseesController::lionheart()





* Visibility: **public**




### crondTvDates

    mixed app\controllers\FranchiseesController::crondTvDates()





* Visibility: **public**




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



