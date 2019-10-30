app\models\Diagnostics
===============






* Class name: Diagnostics
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $schema

    public mixed $schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'monthly_trial_signups' => 'string', 'facebook_likes' => 'integer', 'instagram_followers' => 'integer', 'monthly_trial_redemptions' => 'string', 'average_trial_class_per_member' => 'string', 'average_price_per_member' => 'float', 'average_life_cycle_member' => 'string', 'trainers_session_highlights' => 'string', 'watched_webinars' => 'string', 'no_of_trainers' => 'string', 'no_of_trainers_with_certificates' => 'integer', 'no_of_support_tickets' => 'integer', 'recent_compliant' => 'string', 'average_studio_rating' => 'float', 'studio_rent_price' => 'string', 'typeform_submit_date' => 'string', 'created_at' => 'timestamp', 'updated_at' => 'timestamp')





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('Franchisees' => array('key' => array('franchisee_id' => 'id')))





* Visibility: **public**


Methods
-------


### mysql_query

    mixed app\models\Diagnostics::mysql_query($sql)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $sql **mixed**



### getSelectStudioMemberCount

    mixed app\models\Diagnostics::getSelectStudioMemberCount($f_id, $past_date)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $f_id **mixed**
* $past_date **mixed**



### getOtherStudioMemberCount

    mixed app\models\Diagnostics::getOtherStudioMemberCount($f_id, $past_date)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $f_id **mixed**
* $past_date **mixed**


