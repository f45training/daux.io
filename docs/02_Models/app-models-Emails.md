app\models\Emails
===============






* Class name: Emails
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'email' => 'string', 'franchisee_id' => 'string', 'type' => 'string', 'timestamp' => 'timestamp', 'is_deleted' => 'boolean', 'created_at' => 'timestamp', 'updated_at' => 'timestamp')





* Visibility: **protected**


### $validates

    public mixed $validates = array('email' => array(array('isUniqueEmail', 'message' => 'email is already used.')))





* Visibility: **public**


Methods
-------


### getAllFranchiseesEmail

    mixed app\models\Emails::getAllFranchiseesEmail()





* Visibility: **public**
* This method is **static**.



