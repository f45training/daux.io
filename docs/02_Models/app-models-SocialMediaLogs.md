app\models\SocialMediaLogs
===============






* Class name: SocialMediaLogs
* Namespace: app\models
* Parent class: lithium\data\Model



Constants
----------


### SOCIAL_FACEBOOK

    const SOCIAL_FACEBOOK = "fb"





### SOCIAL_INSTAGRAM

    const SOCIAL_INSTAGRAM = "instagram"





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'studio_id' => 'integer', 'social_media_name' => 'string', 'social_media_current_count' => 'integer', 'timestamp' => 'timestamp')





* Visibility: **protected**


Methods
-------


### getSocials

    mixed app\models\SocialMediaLogs::getSocials()





* Visibility: **public**




### getLatestCountBySocial

    mixed app\models\SocialMediaLogs::getLatestCountBySocial($social)





* Visibility: **public**


#### Arguments
* $social **mixed**


