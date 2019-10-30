app\controllers\ExerciseRelationsController
===============

Base class for controllers housing common functions.




* Class name: ExerciseRelationsController
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


### by_franchisee

    mixed app\controllers\ExerciseRelationsController::by_franchisee()





* Visibility: **public**




### by_franchisee_date

    mixed app\controllers\ExerciseRelationsController::by_franchisee_date()





* Visibility: **public**




### update

    array app\controllers\Rest::update()

Update details of the specific controller extending Rest class



* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### reorder

    mixed app\controllers\ExerciseRelationsController::reorder()





* Visibility: **public**




### multiple

    mixed app\controllers\ExerciseRelationsController::multiple()





* Visibility: **public**




### hookToZapier

    mixed app\controllers\ExerciseRelationsController::hookToZapier($data)





* Visibility: **public**


#### Arguments
* $data **mixed**



### get_exercises

    mixed app\controllers\ExerciseRelationsController::get_exercises()





* Visibility: **public**




### get_gym_exercise

    mixed app\controllers\ExerciseRelationsController::get_gym_exercise()





* Visibility: **public**




### getGymWeekWeekdayExercises

    mixed app\controllers\ExerciseRelationsController::getGymWeekWeekdayExercises($params)





* Visibility: **public**


#### Arguments
* $params **mixed**



### getExercisesAlternative

    mixed app\controllers\ExerciseRelationsController::getExercisesAlternative($exer_ids, $data)





* Visibility: **public**


#### Arguments
* $exer_ids **mixed**
* $data **mixed**



### get_exercises_weekly

    mixed app\controllers\ExerciseRelationsController::get_exercises_weekly()





* Visibility: **public**




### delete

    mixed app\controllers\Rest::delete()





* Visibility: **public**
* This method is defined by [app\controllers\Rest](app-controllers-Rest.md)




### save_exercises

    mixed app\controllers\ExerciseRelationsController::save_exercises()





* Visibility: **public**




### save_gym_exercises

    mixed app\controllers\ExerciseRelationsController::save_gym_exercises()





* Visibility: **public**




### copy

    mixed app\controllers\ExerciseRelationsController::copy()





* Visibility: **public**




### insert

    mixed app\controllers\ExerciseRelationsController::insert()





* Visibility: **public**




### get_exercises_week_weekday

    mixed app\controllers\ExerciseRelationsController::get_exercises_week_weekday()





* Visibility: **public**




### get_franchise_exercises_week_weekday

    mixed app\controllers\ExerciseRelationsController::get_franchise_exercises_week_weekday()





* Visibility: **public**




### set_as_alternative

    mixed app\controllers\ExerciseRelationsController::set_as_alternative()





* Visibility: **public**




### delete_all_workouts

    mixed app\controllers\ExerciseRelationsController::delete_all_workouts()





* Visibility: **public**




### workouts_copy

    mixed app\controllers\ExerciseRelationsController::workouts_copy()





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



