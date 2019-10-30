app\models\FranchiseeChecklistStatus
===============

FranchiseeChecklistStatus_Class is a class for FranchiseeChecklistStatus model




* Class name: FranchiseeChecklistStatus
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_meta

    protected mixed $_meta = array('source' => 'franchisee_checklist_status')





* Visibility: **protected**


### $columns

    protected mixed $columns = array('franchisee_reopen_log_id', 'franchisee_checklist_tree_id', 'status', 'updated_at', 'updated_by')





* Visibility: **protected**
* This property is **static**.


### $belongsTo

    public mixed $belongsTo = array('FranchiseeChecklistTree' => array('key' => 'franchisee_checklist_tree_id'), 'FranchiseeReopenLogs' => array('key' => 'franchisee_reopen_log_id'))





* Visibility: **public**


### $funnels

    public mixed $funnels = array('1' => array('awaiting-compliance-checks' => array('conditions' => array('welcome-call-completed')), 'awaiting-progress-call' => array('conditions' => array('compliance')), 'approved-to-operate' => array('conditions' => array('approved-to-open')), 'functioning' => array('conditions' => array('approved-to-open'))))





* Visibility: **public**
* This property is **static**.


Methods
-------


### areAllStatusApproved

    integer|string app\models\FranchiseeChecklistStatus::areAllStatusApproved(integer $id)

Function areAllStatusApproved
Check if all the checklists are approved



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **integer** - &lt;p&gt;Reopen identifier for a certain checklist&lt;/p&gt;



### getStatusValue

    string app\models\FranchiseeChecklistStatus::getStatusValue(integer|boolean $status)

Function getStatusValue
Check if all the checklists are approved



* Visibility: **public**


#### Arguments
* $status **integer|boolean** - &lt;p&gt;determing status of value&lt;/p&gt;


