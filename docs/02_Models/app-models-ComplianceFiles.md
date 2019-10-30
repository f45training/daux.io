app\models\ComplianceFiles
===============






* Class name: ComplianceFiles
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'file_url' => 'string', 'file_name' => 'string', 'notes' => 'string', 'approved_at' => 'integer', 'approved_by_admin' => 'integer', 'compliance_id' => 'integer', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $belongsTo

    public mixed $belongsTo = array('ComplianceQuestion' => array('to' => 'ComplianceQuestion', 'key' => 'compliance_id', 'constraint' => array(), 'fields' => array(), 'order' => null, 'limit' => null))





* Visibility: **public**



