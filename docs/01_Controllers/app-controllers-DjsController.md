app\controllers\DjsController
===============

Base class for controllers housing common functions.




* Class name: DjsController
* Namespace: app\controllers
* Parent class: [app\controllers\Rest](app-controllers-Rest.md)





Properties
----------


### $dataExclude

    public mixed $dataExclude = array()





* Visibility: **public**


### $s3_class_logos_path

    public mixed $s3_class_logos_path = "http://f45tv.s3.amazonaws.com/class-logos/"





* Visibility: **public**


### $s3_class_logos_ext

    public mixed $s3_class_logos_ext = "png"





* Visibility: **public**


### $data

    private  $data





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




### home

    mixed app\controllers\DjsController::home()

DJ Landing Page



* Visibility: **public**




### home_royalty

    mixed app\controllers\DjsController::home_royalty()

DJ Royalty Landing Page



* Visibility: **public**




### for_fm

    mixed app\controllers\DjsController::for_fm()

For FM



* Visibility: **public**




### for_fm_extra

    mixed app\controllers\DjsController::for_fm_extra()

For FM Royalty



* Visibility: **public**




### self_playlist_data_for_fm

    void app\controllers\DjsController::self_playlist_data_for_fm(array $data, string $mix_type)

This loads up playlist data read out by F45.FM frontend.

This is the main call to loading API.
NOTE: This will update the passed object parameter $data defined below

* Visibility: **public**


#### Arguments
* $data **array** - &lt;p&gt;&amp;$data Just leave this as empty array [], as this will be filled in&lt;/p&gt;
* $mix_type **string** - &lt;p&gt;The mix type as string, with values from the keys of UploadMixes::$mix_types&lt;/p&gt;



### getRequestIp

    mixed app\controllers\DjsController::getRequestIp()





* Visibility: **private**




### getIpTimezone

    mixed app\controllers\DjsController::getIpTimezone($ip)





* Visibility: **private**


#### Arguments
* $ip **mixed**



### fm_download

    mixed app\controllers\DjsController::fm_download()

Forces download dialog for S3 downlaod service.



* Visibility: **public**




### listen

    null|mixed app\controllers\DjsController::listen()

API for Audio streaming. This API is temporarily disabled by BTP-11



* Visibility: **public**




### self_playlist_data

    mixed app\controllers\DjsController::self_playlist_data($data, $selected_week, $selected_year, $search, $mix_type)





* Visibility: **public**


#### Arguments
* $data **mixed**
* $selected_week **mixed**
* $selected_year **mixed**
* $search **mixed**
* $mix_type **mixed**



### self_upload_mix_data

    mixed app\controllers\DjsController::self_upload_mix_data($data, $mix_type)





* Visibility: **public**


#### Arguments
* $data **mixed**
* $mix_type **mixed**



### get_cover

    mixed app\controllers\DjsController::get_cover()





* Visibility: **public**




### save

    mixed app\controllers\DjsController::save()





* Visibility: **public**




### save_royalty

    mixed app\controllers\DjsController::save_royalty()

Save Royalty



* Visibility: **public**




### link_playlist

    \app\controllers\compact app\controllers\DjsController::link_playlist()





* Visibility: **public**




### delete_mix

    mixed app\controllers\DjsController::delete_mix()





* Visibility: **public**




### get_mix

    mixed app\controllers\DjsController::get_mix()





* Visibility: **public**




### rate

    mixed app\controllers\DjsController::rate()





* Visibility: **public**




### checkTimelineSchedule

    mixed app\controllers\DjsController::checkTimelineSchedule($week, $day, $year, $programs)





* Visibility: **public**


#### Arguments
* $week **mixed**
* $day **mixed**
* $year **mixed**
* $programs **mixed**



### getIsoWeeksInYear

    mixed app\controllers\DjsController::getIsoWeeksInYear($year)





* Visibility: **private**


#### Arguments
* $year **mixed**



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



