app\models\StatusChecklistFiles
===============






* Class name: StatusChecklistFiles
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'id_status' => 'integer', 'id_substatus' => 'integer', 'id_gym' => 'integer', 'file_url' => 'string', 'filename' => 'string', 'timestamp' => 'timestamp', 'is_approved' => 'boolean', 'approved_history' => 'text', 're_open_date' => 'integer')





* Visibility: **protected**


Methods
-------


### getAllPreopenList

    \app\models\[type] app\models\StatusChecklistFiles::getAllPreopenList()

Return all studios with preopen list and not yet approved



* Visibility: **public**



