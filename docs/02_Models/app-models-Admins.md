app\models\Admins
===============






* Class name: Admins
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $hasAccessToAllFranchisees

    protected boolean $hasAccessToAllFranchisees = true





* Visibility: **protected**


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'name' => 'string', 'username' => 'string', 'password' => 'string', 'type' => 'integer', 'email' => 'string', 'token' => 'string', 'role_id' => 'integer')





* Visibility: **protected**


### $validates

    public mixed $validates = array('name' => array(array('notEmpty', 'message' => 'You must include a name.')), 'username' => array(array('notEmpty', 'message' => 'You must include a username.'), array('isUniqueUsername', 'message' => 'username is already used.')), 'password' => array(array('notEmpty', 'message' => 'You must include a password.')), 'type' => array(array('notEmpty', 'message' => 'You must include a user type.')))





* Visibility: **public**


Methods
-------


### getAdminType

    \app\models\[type] app\models\Admins::getAdminType(\app\models\[type] $user_id)

Get Admin type by id



* Visibility: **public**


#### Arguments
* $user_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### getAdminName

    mixed app\models\Admins::getAdminName($user_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $user_id **mixed**



### getPerfomanceManagers

    mixed app\models\Admins::getPerfomanceManagers()





* Visibility: **public**
* This method is **static**.




### getAllSalePersons

    mixed app\models\Admins::getAllSalePersons()

This function get list of Sale Persons role



* Visibility: **public**
* This method is **static**.



