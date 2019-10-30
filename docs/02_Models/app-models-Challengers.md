app\models\Challengers
===============






* Class name: Challengers
* Namespace: app\models
* Parent class: lithium\data\Model



Constants
----------


### MALE_CHALLENGER

    const MALE_CHALLENGER = 0





### FEMALE_CHALLENGER

    const FEMALE_CHALLENGER = 1





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'challenge_no' => 'integer', 'studio_id' => 'integer', 'studio_details' => 'string', 'name' => 'string', 'age' => 'string', 'gender' => 'string', 'start_weight_date' => 'date', 'end_weight_date' => 'date', 'start_weight' => 'float', 'end_weight' => 'float', 'start_bodyfat' => 'float', 'end_bodyfat' => 'float', 'photo_upload' => 'text', 'is_active' => 'integer', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $participants

    public mixed $participants = array(0 => 'male', 1 => 'female')





* Visibility: **public**
* This property is **static**.


Methods
-------


### findAllChallengersByStudio

    mixed app\models\Challengers::findAllChallengersByStudio($studioId)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $studioId **mixed**



### getLatestChallengeByStudioAndChallenge

    \app\models\[type] app\models\Challengers::getLatestChallengeByStudioAndChallenge(\app\models\[type] $studio, \app\models\[type] $challenge_no, $limit)

Returns latest challenge by studio and challenge



* Visibility: **public**
* This method is **static**.


#### Arguments
* $studio **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $challenge_no **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $limit **mixed**



### getAllChallengersByGender

    mixed app\models\Challengers::getAllChallengersByGender($gender)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $gender **mixed**



### getAllPhotosUploadByChallenger

    mixed app\models\Challengers::getAllPhotosUploadByChallenger($challenger)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $challenger **mixed**



### getTotalBwl

    mixed app\models\Challengers::getTotalBwl($start_weight, $end_weight)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $start_weight **mixed**
* $end_weight **mixed**



### getTotalFl

    mixed app\models\Challengers::getTotalFl($start_bodyfat, $end_bodyfat)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $start_bodyfat **mixed**
* $end_bodyfat **mixed**


