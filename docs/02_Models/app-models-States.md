app\models\States
===============






* Class name: States
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $schema

    public mixed $schema = array('id' => 'integer', 'name' => 'string', 'abbrev' => 'string', 'name_only' => 'string', 'status' => 'string', 'is_deleted' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **public**


### $status

    public mixed $status = array('Select', 'No deferred estimated or world pack fees', 'Estimated fees deferred until open', 'Estimated fees and world pack fees deferred until open.')





* Visibility: **public**
* This property is **static**.


### $validates

    public mixed $validates = array('name' => array('isUniqueName', 'message' => 'State name already exists.'))





* Visibility: **public**


Methods
-------


### getAll

    mixed app\models\States::getAll()





* Visibility: **public**
* This method is **static**.



