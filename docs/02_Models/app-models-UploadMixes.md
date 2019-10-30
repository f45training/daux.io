app\models\UploadMixes
===============






* Class name: UploadMixes
* Namespace: app\models
* Parent class: lithium\data\Model



Constants
----------


### DEFAULT_MIXTAB

    const DEFAULT_MIXTAB = 'licensed'





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'cover_id' => 'integer', 'mix_file_path' => 'string', 'workout_list_id' => 'integer', 'genre_list' => 'string', 'workout_types' => 'string', 'volume' => 'string', 'timestamp' => 'timestamp', 'week' => 'integer', 'year' => 'string', 'day' => 'integer', 'rate' => 'integer', 'duration' => 'string', 'mix_type' => 'string', 'dj_name' => 'string', 'custom_cover' => 'string')





* Visibility: **protected**


### $hasNoWeeksFilter

    public mixed $hasNoWeeksFilter = array('royalty', 'prodigy')





* Visibility: **public**
* This property is **static**.


### $allowOnlyToDays

    public mixed $allowOnlyToDays = array('recovery' => array('6', '7'))





* Visibility: **public**
* This property is **static**.


### $days

    public mixed $days = array('1' => 'Monday', '2' => 'Tuesday', '3' => 'Wednesday', '4' => 'Thursday', '5' => 'Friday', '6' => 'Saturday', '7' => 'Sunday')





* Visibility: **public**
* This property is **static**.


### $special_covers

    public mixed $special_covers = array(100 => 'DJ Competition')





* Visibility: **public**
* This property is **static**.


### $mix_types

    public mixed $mix_types = array('licensed' => 'Main Mixes', 'masters' => 'Masters', 'prodigy' => 'Prodigy', 'royalty' => 'Royalty Free Mixes', 'recovery' => 'Recovery')





* Visibility: **public**
* This property is **static**.


### $days_in_a_week

    public mixed $days_in_a_week = 7





* Visibility: **public**
* This property is **static**.


### $hasOne

    public mixed $hasOne = array('Covers' => array('key' => array('cover_id' => 'id')))





* Visibility: **public**


Methods
-------


### findAll

    mixed app\models\UploadMixes::findAll()





* Visibility: **public**
* This method is **static**.




### _getPlaylist

    mixed app\models\UploadMixes::_getPlaylist($week, $year, $search, $mix_type)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $week **mixed**
* $year **mixed**
* $search **mixed**
* $mix_type **mixed**



### _getPlaylist_for_fm

    array app\models\UploadMixes::_getPlaylist_for_fm($mix_type)

Mainly responsible for creating the playlist



* Visibility: **public**
* This method is **static**.


#### Arguments
* $mix_type **mixed** - &lt;p&gt;string the mix type slug enum on database&lt;/p&gt;



### _convertWeekDayYearToDate

    mixed app\models\UploadMixes::_convertWeekDayYearToDate($year, $week, $day_number)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $year **mixed**
* $week **mixed**
* $day_number **mixed**



### _getPlaylistSimpleAll

    mixed app\models\UploadMixes::_getPlaylistSimpleAll($mix_type)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $mix_type **mixed**



### _getGenreListNames

    mixed app\models\UploadMixes::_getGenreListNames($list)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $list **mixed**



### _getNextVolume

    mixed app\models\UploadMixes::_getNextVolume($cover_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $cover_id **mixed**



### _getNextDay

    mixed app\models\UploadMixes::_getNextDay($week, $year, $mix_type)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $week **mixed**
* $year **mixed**
* $mix_type **mixed**



### _checkIfDayIsAvailable

    mixed app\models\UploadMixes::_checkIfDayIsAvailable($week, $day, $year, $mix_type)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $week **mixed**
* $day **mixed**
* $year **mixed**
* $mix_type **mixed**



### _listWeeks

    \app\models\{array} app\models\UploadMixes::_listWeeks($weeks, $exclude_full_week, $mix_type)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $weeks **mixed**
* $exclude_full_week **mixed**
* $mix_type **mixed**



### _listYears

    \app\models\{array} app\models\UploadMixes::_listYears()





* Visibility: **public**
* This method is **static**.




### _getDjName

    mixed app\models\UploadMixes::_getDjName($week, $day, $mix_type, $workout_list_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $week **mixed**
* $day **mixed**
* $mix_type **mixed**
* $workout_list_id **mixed**



### getWeekWeekdayTimeline

    \app\models\{array} app\models\UploadMixes::getWeekWeekdayTimeline($week, $day)





* Visibility: **public**


#### Arguments
* $week **mixed**
* $day **mixed**



### getMixId

    \app\models\{int} app\models\UploadMixes::getMixId($week, $day, $year, $mix_type)





* Visibility: **public**


#### Arguments
* $week **mixed**
* $day **mixed**
* $year **mixed**
* $mix_type **mixed**


