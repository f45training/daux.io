app\controllers\ReportsController
===============

Base class for controllers housing common functions.




* Class name: ReportsController
* Namespace: app\controllers
* Parent class: [app\controllers\Rest](app-controllers-Rest.md)





Properties
----------


### $dataExclude

    public mixed $dataExclude = array()





* Visibility: **public**


### $total_opened

    public mixed $total_opened





* Visibility: **public**


### $months

    public mixed $months = array('January', 'February', 'March', 'April', 'May', 'June', 'July', 'August', 'September', 'October', 'November', 'December')





* Visibility: **public**
* This property is **static**.


### $report_month

    private mixed $report_month = null





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




### equipment

    mixed app\controllers\ReportsController::equipment()





* Visibility: **public**




### smai_equipment

    mixed app\controllers\ReportsController::smai_equipment()





* Visibility: **public**




### opening

    mixed app\controllers\ReportsController::opening()





* Visibility: **public**




### sold_report

    mixed app\controllers\ReportsController::sold_report()





* Visibility: **public**




### getCountriesFranchisees

    mixed app\controllers\ReportsController::getCountriesFranchisees()





* Visibility: **public**




### getFourMonthsTotal

    mixed app\controllers\ReportsController::getFourMonthsTotal()





* Visibility: **public**




### getMonthOpeningsPerCountry

    mixed app\controllers\ReportsController::getMonthOpeningsPerCountry($country)





* Visibility: **public**


#### Arguments
* $country **mixed**



### reportsJSON

    mixed app\controllers\ReportsController::reportsJSON()





* Visibility: **public**




### getCountryLocation

    mixed app\controllers\ReportsController::getCountryLocation()





* Visibility: **public**




### getAllOpeningStudios

    mixed app\controllers\ReportsController::getAllOpeningStudios()





* Visibility: **public**




### getTopTenOpeningStudios

    mixed app\controllers\ReportsController::getTopTenOpeningStudios()





* Visibility: **public**




### getLastLogin

    mixed app\controllers\ReportsController::getLastLogin($franchise_id)





* Visibility: **public**


#### Arguments
* $franchise_id **mixed**



### getTotalLaunch

    mixed app\controllers\ReportsController::getTotalLaunch($franchise_id)





* Visibility: **public**


#### Arguments
* $franchise_id **mixed**



### getTVReports

    mixed app\controllers\ReportsController::getTVReports()





* Visibility: **public**




### getTvReportsByTvScreens

    array app\controllers\ReportsController::getTvReportsByTvScreens()

Returns for Exec Report studios that have tvScreens:
{3,4,5,6,7,8,9}



* Visibility: **public**




### getFreshDeskTickets

    mixed app\controllers\ReportsController::getFreshDeskTickets($opt)





* Visibility: **public**


#### Arguments
* $opt **mixed**



### getFreshDeskTicketToday

    mixed app\controllers\ReportsController::getFreshDeskTicketToday()





* Visibility: **public**




### save_equipment

    mixed app\controllers\ReportsController::save_equipment()

Save equipments for smai



* Visibility: **public**




### franchiseStatus

    mixed app\controllers\ReportsController::franchiseStatus(\app\controllers\equipment_id $equipment_id, \app\controllers\status_id $status_id, \app\controllers\franchisee_id $franchisee_name, \app\controllers\franchisee_name $franchisee_email)

Franchise Status send email.



* Visibility: **public**


#### Arguments
* $equipment_id **app\controllers\equipment_id** - &lt;p&gt;(string) equipment id&lt;/p&gt;
* $status_id **app\controllers\status_id** - &lt;p&gt;(string) status id&lt;/p&gt;
* $franchisee_name **app\controllers\franchisee_id** - &lt;p&gt;(string) franchisee id&lt;/p&gt;
* $franchisee_email **app\controllers\franchisee_name** - &lt;p&gt;(string) studio name&lt;/p&gt;



### getTimeAgo

    mixed app\controllers\ReportsController::getTimeAgo($ptime)





* Visibility: **private**


#### Arguments
* $ptime **mixed**



### payments

    mixed app\controllers\ReportsController::payments()

Equipment Payments



* Visibility: **public**




### divisions

    mixed app\controllers\ReportsController::divisions()





* Visibility: **public**




### get_divisions_members

    mixed app\controllers\ReportsController::get_divisions_members()





* Visibility: **public**




### get_divisions_gyms

    mixed app\controllers\ReportsController::get_divisions_gyms()





* Visibility: **public**




### get_typeform_reservation_and_sold_reports

    mixed app\controllers\ReportsController::get_typeform_reservation_and_sold_reports()





* Visibility: **public**




### typeform_reports

    mixed app\controllers\ReportsController::typeform_reports()





* Visibility: **public**




### convertCurrency

    mixed app\controllers\ReportsController::convertCurrency($from, $to, $amount)





* Visibility: **public**


#### Arguments
* $from **mixed**
* $to **mixed**
* $amount **mixed**



### soldReports

    mixed app\controllers\ReportsController::soldReports()





* Visibility: **public**




### suppliers

    mixed app\controllers\ReportsController::suppliers()

Supplier Reports



* Visibility: **public**




### project_greenlight

    mixed app\controllers\ReportsController::project_greenlight()

Greenlight Reports



* Visibility: **public**




### get_sales_report_summary

    mixed app\controllers\ReportsController::get_sales_report_summary()

Klipfolio Reports one page project



* Visibility: **public**




### getOnGoingMeetings

    mixed app\controllers\ReportsController::getOnGoingMeetings()





* Visibility: **public**




### getAccumulatedFranchisees

    mixed app\controllers\ReportsController::getAccumulatedFranchisees()





* Visibility: **public**




### getGymAverageOpenTime

    mixed app\controllers\ReportsController::getGymAverageOpenTime()





* Visibility: **public**




### ordinal_suffix

    mixed app\controllers\ReportsController::ordinal_suffix($num)





* Visibility: **public**


#### Arguments
* $num **mixed**



### franchisee_agreement_report

    mixed app\controllers\ReportsController::franchisee_agreement_report()





* Visibility: **public**




### exportagreementreport

    mixed app\controllers\ReportsController::exportagreementreport()





* Visibility: **public**




### outputCSV

    mixed app\controllers\ReportsController::outputCSV($data)





* Visibility: **public**


#### Arguments
* $data **mixed**



### validateDate

    mixed app\controllers\ReportsController::validateDate($date)





* Visibility: **private**


#### Arguments
* $date **mixed**



### get_franchise_open_per_month

    mixed app\controllers\ReportsController::get_franchise_open_per_month()





* Visibility: **public**




### franchisee_invoices

    mixed app\controllers\ReportsController::franchisee_invoices()





* Visibility: **public**




### setInvoiceIDReference

    mixed app\controllers\ReportsController::setInvoiceIDReference($franchisee_id, $invoice_id, $whole)





* Visibility: **private**


#### Arguments
* $franchisee_id **mixed**
* $invoice_id **mixed**
* $whole **mixed**



### new_studios_executive_report

    mixed app\controllers\ReportsController::new_studios_executive_report()





* Visibility: **public**




### executive_reports

    \app\controllers\[type] app\controllers\ReportsController::executive_reports()

Handles Executive Reports



* Visibility: **public**




### executive_reports_form

    \app\controllers\[type] app\controllers\ReportsController::executive_reports_form()

Handles saving functionality



* Visibility: **public**




### executive_reports_form_edit

    mixed app\controllers\ReportsController::executive_reports_form_edit()





* Visibility: **public**




### getPreOpenList

    \app\controllers\[type] app\controllers\ReportsController::getPreOpenList()

Return all studios that have all preopen photos  and
have not yet been approved



* Visibility: **public**




### getSalesApparel

    \app\controllers\[type] app\controllers\ReportsController::getSalesApparel()

Retrieve sales apparel



* Visibility: **public**




### admin_access_report

    \app\controllers\[type] app\controllers\ReportsController::admin_access_report()

Handles access admin report



* Visibility: **public**




### getDraftDayBookings

    array app\controllers\ReportsController::getDraftDayBookings()

Returns number of bookings each day (7days)
{day1 = 3, day2 => 4, day3 => 5}



* Visibility: **public**




### getContactRequests

    array app\controllers\ReportsController::getContactRequests()

Returns number of contact request each day(7days)
{day1 = 3, day2 => 4, day3 => 5}



* Visibility: **public**




### getYearlyFranchiseeContracts

    mixed app\controllers\ReportsController::getYearlyFranchiseeContracts()





* Visibility: **public**




### getChallengeUsers

    mixed app\controllers\ReportsController::getChallengeUsers()





* Visibility: **public**




### getFranchiseeActiveTVs

    mixed app\controllers\ReportsController::getFranchiseeActiveTVs()





* Visibility: **public**




### generateFreshDeskReport

    mixed app\controllers\ReportsController::generateFreshDeskReport()





* Visibility: **public**




### socialMediaReports

    mixed app\controllers\ReportsController::socialMediaReports()





* Visibility: **public**




### sales_projection

    mixed app\controllers\ReportsController::sales_projection()





* Visibility: **public**




### get_tvversion_franchisees

    mixed app\controllers\ReportsController::get_tvversion_franchisees()





* Visibility: **public**




### get_franchisee_tv_count

    mixed app\controllers\ReportsController::get_franchisee_tv_count()





* Visibility: **public**




### get_accumulated_franchisees

    mixed app\controllers\ReportsController::get_accumulated_franchisees()





* Visibility: **public**




### get_franchisees_overdue_date

    mixed app\controllers\ReportsController::get_franchisees_overdue_date()





* Visibility: **public**




### get_admin_last_activity

    mixed app\controllers\ReportsController::get_admin_last_activity()





* Visibility: **public**




### onboarding

    mixed app\controllers\ReportsController::onboarding()





* Visibility: **public**




### unconfirmedPO

    mixed app\controllers\ReportsController::unconfirmedPO()





* Visibility: **public**




### establishment_fees

    mixed app\controllers\ReportsController::establishment_fees()





* Visibility: **public**




### franchisee_group_owners

    mixed app\controllers\ReportsController::franchisee_group_owners()





* Visibility: **public**




### fee_start_date

    mixed app\controllers\ReportsController::fee_start_date()





* Visibility: **public**




### fee_start_date_download

    mixed app\controllers\ReportsController::fee_start_date_download()





* Visibility: **public**




### blacklisted

    mixed app\controllers\ReportsController::blacklisted()





* Visibility: **public**




### blacklisted_export

    mixed app\controllers\ReportsController::blacklisted_export()





* Visibility: **public**




### this_is_a_test

    mixed app\controllers\ReportsController::this_is_a_test()





* Visibility: **public**




### yelp_setup_report

    mixed app\controllers\ReportsController::yelp_setup_report()





* Visibility: **public**




### reformat_date

    mixed app\controllers\ReportsController::reformat_date($arr, $key)





* Visibility: **private**


#### Arguments
* $arr **mixed**
* $key **mixed**



### create_opened_and_opening_by_three_months_pie_chart

    mixed app\controllers\ReportsController::create_opened_and_opening_by_three_months_pie_chart($opened_studios, $opening_studios)





* Visibility: **private**


#### Arguments
* $opened_studios **mixed**
* $opening_studios **mixed**



### create_sold_and_opened_studios_chart

    mixed app\controllers\ReportsController::create_sold_and_opened_studios_chart($sold_studios, $opened_studios)





* Visibility: **private**


#### Arguments
* $sold_studios **mixed**
* $opened_studios **mixed**



### fill_line_chart_data_set

    mixed app\controllers\ReportsController::fill_line_chart_data_set($dates, $arr, $key1, $key2, $label, $color)





* Visibility: **private**


#### Arguments
* $dates **mixed**
* $arr **mixed**
* $key1 **mixed**
* $key2 **mixed**
* $label **mixed**
* $color **mixed**



### summary_sold_and_opened_studios

    mixed app\controllers\ReportsController::summary_sold_and_opened_studios($arr1, $arr2, $arr3)





* Visibility: **private**


#### Arguments
* $arr1 **mixed**
* $arr2 **mixed**
* $arr3 **mixed**



### f45tv_access_code_logs

    mixed app\controllers\ReportsController::f45tv_access_code_logs()





* Visibility: **public**




### save_access_code

    mixed app\controllers\ReportsController::save_access_code()





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



