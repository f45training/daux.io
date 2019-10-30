app\models\FranchiseeInsurance
===============

Insurance Policies




* Class name: FranchiseeInsurance
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'file_name' => 'string', 'file_url' => 'string', 'expiry' => 'timestamp', 'status' => 'string', 'is_deleted' => 'boolean', 'timestamp' => 'timestamp', 'approved_at' => 'timestamp', 'rejected_at' => 'timestamp', 'updated_by' => 'string')





* Visibility: **protected**


### $belongsTo

    public mixed $belongsTo = array('Franchisees' => array('key' => 'franchisee_id'))





* Visibility: **public**



