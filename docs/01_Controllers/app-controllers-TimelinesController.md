app\controllers\TimelinesController
===============

Base class for controllers housing common functions.




* Class name: TimelinesController
* Namespace: app\controllers
* Parent class: [app\controllers\Rest](app-controllers-Rest.md)



Constants
----------


### VIDEO_PATH

    const VIDEO_PATH = "http://f45tv.s3-website-ap-southeast-2.amazonaws.com/videos/GYM_LOW_RES/"





Properties
----------


### $version

    private mixed $version = '2.5'





* Visibility: **private**


### $videoPath

    public mixed $videoPath = "http://socialstaging.com/xhtml/f45/videos/"





* Visibility: **public**


### $newVideoPath

    private mixed $newVideoPath = "http://f45tv.s3-website-ap-southeast-2.amazonaws.com/videos/GYM_LOW_RES/"





* Visibility: **private**


### $files

    public mixed $files = array()





* Visibility: **public**


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




### add

    mixed app\controllers\Rest::add()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### edit

    mixed app\controllers\Rest::edit()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### view

    mixed app\controllers\Rest::view()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### deleteMatrixCache

    \app\controllers\deleted app\controllers\TimelinesController::deleteMatrixCache()

Deletes caches from redis server using matches



* Visibility: **public**




### getPredisCacheKey

    string app\controllers\TimelinesController::getPredisCacheKey($predisClient, $pattern)

Gets Predis cache key from key pattern



* Visibility: **private**


#### Arguments
* $predisClient **mixed** - &lt;p&gt;Predis\Client predis client instance&lt;/p&gt;
* $pattern **mixed** - &lt;p&gt;string pattern, use * for wildcards&lt;/p&gt;



### getRequestJson

    array app\controllers\TimelinesController::getRequestJson(string $franchise_id, string $week, string $weekday)

Gets request json used for getTimeline



* Visibility: **private**


#### Arguments
* $franchise_id **string** - &lt;p&gt;the franchisee id&lt;/p&gt;
* $week **string** - &lt;p&gt;week generated from request&lt;/p&gt;
* $weekday **string** - &lt;p&gt;weekday generated from request&lt;/p&gt;



### getUniqueWorkouts

    mixed app\controllers\TimelinesController::getUniqueWorkouts($videos)





* Visibility: **public**


#### Arguments
* $videos **mixed**



### getVideos

    mixed app\controllers\TimelinesController::getVideos($videos, $workout_name)





* Visibility: **public**


#### Arguments
* $videos **mixed**
* $workout_name **mixed**



### getGymTimeline

    mixed app\controllers\TimelinesController::getGymTimeline()





* Visibility: **public**




### blockedTimeline

    mixed app\controllers\TimelinesController::blockedTimeline()





* Visibility: **public**




### getTimeline

    mixed app\controllers\TimelinesController::getTimeline()





* Visibility: **public**




### getRequestIP

    mixed app\controllers\TimelinesController::getRequestIP()





* Visibility: **private**




### getScreenTimestamp

    mixed app\controllers\TimelinesController::getScreenTimestamp($franchise_id, $ip)





* Visibility: **private**


#### Arguments
* $franchise_id **mixed**
* $ip **mixed**



### dataRegex

    mixed app\controllers\TimelinesController::dataRegex($value, $cache_key, $type)





* Visibility: **public**


#### Arguments
* $value **mixed**
* $cache_key **mixed**
* $type **mixed**



### getSchedules

    mixed app\controllers\TimelinesController::getSchedules($franchise_id, $weekday, $timezone)





* Visibility: **private**


#### Arguments
* $franchise_id **mixed**
* $weekday **mixed**
* $timezone **mixed**



### pushSchedule

    mixed app\controllers\TimelinesController::pushSchedule($weekday, $time, $workout_name, $timezone, $schedules, $is_current_day)





* Visibility: **public**


#### Arguments
* $weekday **mixed**
* $time **mixed**
* $workout_name **mixed**
* $timezone **mixed**
* $schedules **mixed**
* $is_current_day **mixed**



### insertItem

    mixed app\controllers\TimelinesController::insertItem($key, $value, $items, $output)





* Visibility: **private**


#### Arguments
* $key **mixed**
* $value **mixed**
* $items **mixed**
* $output **mixed**



### insertTimer

    mixed app\controllers\TimelinesController::insertTimer($progress, $duration, $content_id, $set, $mode, $set_repeat, $rest, $cd)





* Visibility: **private**


#### Arguments
* $progress **mixed**
* $duration **mixed**
* $content_id **mixed**
* $set **mixed**
* $mode **mixed**
* $set_repeat **mixed**
* $rest **mixed**
* $cd **mixed**



### pushFile

    mixed app\controllers\TimelinesController::pushFile($file)





* Visibility: **public**


#### Arguments
* $file **mixed**



### getRequestWeekAndDay

    array app\controllers\TimelinesController::getRequestWeekAndDay()

Gets current request's week and weekday



* Visibility: **private**




### franchiseeData

    mixed app\controllers\TimelinesController::franchiseeData($id, $week, $weekday)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $week **mixed**
* $weekday **mixed**



### addVideo

    mixed app\controllers\TimelinesController::addVideo($file)





* Visibility: **public**


#### Arguments
* $file **mixed**



### getLightTimeline

    mixed app\controllers\TimelinesController::getLightTimeline()





* Visibility: **public**




### three_peat_vids

    mixed app\controllers\TimelinesController::three_peat_vids()





* Visibility: **private**




### getWeeklyTimeline

    mixed app\controllers\TimelinesController::getWeeklyTimeline()

For email purposes only.

One page layout html.

* Visibility: **public**




### getWeekWeekdayTimeline

    mixed app\controllers\TimelinesController::getWeekWeekdayTimeline()





* Visibility: **public**




### manage_cache

    mixed app\controllers\TimelinesController::manage_cache()

Designed to clear the caches

2019-09-14 Was causing system failures when run (see the keys scan in line 1639)
and since not really being used have commented

* Visibility: **public**




### clear_caches

    mixed app\controllers\TimelinesController::clear_caches()





* Visibility: **public**




### view_timeline_caches

    mixed app\controllers\TimelinesController::view_timeline_caches()





* Visibility: **public**




### _init

    mixed app\controllers\Rest::_init()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### search

    mixed app\controllers\Rest::search()





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



