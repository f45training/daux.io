app\models\ChecklistRelations
===============






* Class name: ChecklistRelations
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'checklist_id' => 'integer', 'status' => 'boolean', 'via_admin' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $validates

    public mixed $validates = array('franchisee_id' => array(array('notEmpty', 'message' => 'You must include a franchisee id.'), array('franchiseeExist', 'message' => 'Invalid franchisee id used')), 'checklist_id' => array(array('notEmpty', 'message' => 'You must include a checklist id.'), array('checklistExist', 'message' => 'Invalid checklist id used')))





* Visibility: **public**



