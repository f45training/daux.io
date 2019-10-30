app\models\PreviousAgreements
===============






* Class name: PreviousAgreements
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'date_terminated' => 'date', 'file_url' => 'string', 'notes' => 'text', 'timestamps' => 'timestamps')





* Visibility: **protected**


### $validates

    public mixed $validates = array('file_url' => array(array('notEmpty', 'message' => 'You must include a file url.')), 'date_terminated' => array(array('notEmpty', 'message' => 'You must include date it was terminated.')))





* Visibility: **public**



