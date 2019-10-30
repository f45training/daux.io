app\models\EquipmentNames
===============






* Class name: EquipmentNames
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'name' => 'string', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $hasMany

    public mixed $hasMany = array('Equipments' => array('key' => array('id' => 'equipment')))





* Visibility: **public**


Methods
-------


### equipment_name

    \app\models\actual app\models\EquipmentNames::equipment_name($id)

Get equipment name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**


