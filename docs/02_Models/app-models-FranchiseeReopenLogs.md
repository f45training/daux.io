app\models\FranchiseeReopenLogs
===============

FranchiseeReopenLogs_Class is a class for FranchiseeReopenLogs model




* Class name: FranchiseeReopenLogs
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $belongsTo

    public mixed $belongsTo = array('Franchisees' => array('key' => 'franchisee_id'), 'FranchiseeChecklistTypes' => array('key' => 'franchisee_checklist_type_id'))





* Visibility: **public**


### $hasMany

    public mixed $hasMany = array('FranchiseeChecklistStatus' => array('key' => 'franchisee_reopen_log_id'))





* Visibility: **public**



