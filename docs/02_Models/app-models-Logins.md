app\models\Logins
===============






* Class name: Logins
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchise_id' => 'integer', 'origin' => 'integer', 'username' => 'string', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $origin

    public mixed $origin = array('1' => 'playbook', '2' => 'f45tv')





* Visibility: **public**
* This property is **static**.


### $validates

    public mixed $validates = array('origin' => array(array('notEmpty', 'message' => "You must include origin")))





* Visibility: **public**



