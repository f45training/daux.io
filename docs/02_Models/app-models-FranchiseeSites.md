app\models\FranchiseeSites
===============






* Class name: FranchiseeSites
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'public_signup_url' => 'text', 'site_id' => 'integer', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $hasOne

    public mixed $hasOne = array('Sites' => array('key' => array('site_id' => 'id')))





* Visibility: **public**



