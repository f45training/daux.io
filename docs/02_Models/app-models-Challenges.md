app\models\Challenges
===============






* Class name: Challenges
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'title' => 'string', 'is_active' => 'integer', 'timestamp' => 'timestamp')





* Visibility: **protected**


Methods
-------


### mysql_query

    mixed app\models\Challenges::mysql_query($sql)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $sql **mixed**



### getAllChallengesByChallenge

    \app\models\[type] app\models\Challenges::getAllChallengesByChallenge($challenge, integer $isActive)

Returns all challengers group by challenge_no



* Visibility: **public**
* This method is **static**.


#### Arguments
* $challenge **mixed**
* $isActive **integer** - &lt;p&gt;[description]&lt;/p&gt;



### getAllChallengeByStudio

    \app\models\[type] app\models\Challenges::getAllChallengeByStudio(\app\models\[type] $studio, integer $isActive)

Returns all challenges by studio id



* Visibility: **public**
* This method is **static**.


#### Arguments
* $studio **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $isActive **integer** - &lt;p&gt;[description]&lt;/p&gt;



### getAllChallengeByStudioAndChallenge

    \app\models\[type] app\models\Challenges::getAllChallengeByStudioAndChallenge(\app\models\[type] $studio, \app\models\[type] $challenge_no, integer $isActive)

Returns all challenges by studioId and challenge no



* Visibility: **public**
* This method is **static**.


#### Arguments
* $studio **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $challenge_no **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $isActive **integer** - &lt;p&gt;[description]&lt;/p&gt;



### runSqlSession

    mixed app\models\Challenges::runSqlSession()





* Visibility: **public**
* This method is **static**.




### allChallenges

    mixed app\models\Challenges::allChallenges()





* Visibility: **public**
* This method is **static**.




### setChallengeToInactive

    mixed app\models\Challenges::setChallengeToInactive()

This will disable other active challenges.



* Visibility: **public**
* This method is **static**.




### getAllPhotosUploadByChallenge

    mixed app\models\Challenges::getAllPhotosUploadByChallenge($challenge, $isActive)





* Visibility: **public**


#### Arguments
* $challenge **mixed**
* $isActive **mixed**


