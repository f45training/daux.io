app\models\FranchiseeChecklistTree
===============

FranchiseeChecklistTree_Class is a class for FranchiseeChecklistTree model




* Class name: FranchiseeChecklistTree
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_meta

    protected mixed $_meta = array('source' => 'franchisee_checklist_tree')





* Visibility: **protected**


### $columns

    protected mixed $columns = array('index', 'franchisee_checklist_id', 'parent_id', 'lft', 'rght', 'franchisee_checklist_type_id', 'name')





* Visibility: **protected**
* This property is **static**.


### $belongsTo

    public mixed $belongsTo = array('FranchiseeChecklists' => array('key' => 'franchisee_checklist_id'))





* Visibility: **public**



