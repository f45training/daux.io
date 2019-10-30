app\models\Users
===============






* Class name: Users
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'name' => 'string', 'email' => 'string', 'contact_num' => 'string', 'phone_code' => 'string', 'user_photo' => 'string', 'is_show_trainer' => 'boolean', 'role' => 'string', 'description' => 'text', 'password' => 'string', 'hash' => 'string', 'franchisee_id' => 'integer', 'status' => 'boolean', 'user_level' => 'integer', 'academy' => 'string', 'is_after_induction_agree' => 'boolean', 'is_after_floorplan_agree' => 'boolean', 'is_after_premise_agree' => 'boolean', 'is_after_equipmentorder_agree' => 'boolean', 'is_after_signage_agree' => 'boolean', 'is_after_preopen_agree' => 'boolean', 'participating_sessions' => 'integer', 'shadowed_sessions' => 'integer', 'conducted_sessions' => 'integer', 'approved_trainer' => 'integer', 'is_team_captain' => 'boolean', 'is_trainer' => 'boolean', 'is_state_manager' => 'boolean', 'is_approved_web_pub' => 'boolean', 'is_show_billboard' => 'boolean', 'large_image' => 'string', 'quote' => 'string', 'qualification' => 'string', 'playoffs_score' => 'integer', 'accept_agreement' => 'boolean', 'is_show_again' => 'boolean', 'updated_at' => 'datetime', 'deleted_at' => 'timestamp', 'createdBy_user_id' => 'integer', 'lastUpdatedBy_user_id' => 'integer', 'timestamp' => 'timestamp', 'is_show_mobile' => 'boolean', 'accept_trainee_induction' => 'boolean', 'isContactSynced' => 'boolean')





* Visibility: **protected**


### $user_level

    public mixed $user_level = array('1' => 'owner', '2' => 'studio_manager', '3' => 'trainer')





* Visibility: **public**
* This property is **static**.


### $belongsTo

    public mixed $belongsTo = array('Franchisees' => array('key' => array('franchisee_id' => 'id')))





* Visibility: **public**


### $validates

    public mixed $validates = array('name' => array(array('notEmpty', 'message' => 'You must include a name.')), 'contact_num' => array(array('validateContactNum', 'message' => 'Contact number must be a number.')), 'phone_code' => array(array('validatePhoneCode', 'message' => 'Phone code will only accept numeric and "-" characters')), 'email' => array(array('notEmpty', 'message' => 'You must include a email.'), array('email', 'message' => 'email is not valid.'), array('isUniqueUserEmail', 'message' => 'email is already used.')), 'password' => array(array('notEmpty', 'message' => 'You must include a password.')), 'franchisee_id' => array(array('notEmpty', 'message' => 'You must include a gym.')), 'user_level' => array(array('notEmpty', 'message' => 'You must include a user level.')))





* Visibility: **public**


### $academy_fields

    public mixed $academy_fields = array('Academy', 'Participating Sessions', 'Shadowed Sessions', 'Conducted Sessions', 'Approved Trainer')





* Visibility: **public**
* This property is **static**.


Methods
-------


### __call

    mixed app\models\Users::__call($method, $paramss)

Used for dynamice functions isUserLevel*



* Visibility: **public**


#### Arguments
* $method **mixed**
* $paramss **mixed**



### getUsersByCriteria

    mixed app\models\Users::getUsersByCriteria($criteria, $isCount)





* Visibility: **public**


#### Arguments
* $criteria **mixed**
* $isCount **mixed**



### deleteTeamCaptainStateManagerByDivision

    mixed app\models\Users::deleteTeamCaptainStateManagerByDivision($division_number)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $division_number **mixed**


