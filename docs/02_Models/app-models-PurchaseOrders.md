app\models\PurchaseOrders
===============






* Class name: PurchaseOrders
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    public mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'equipment' => 'string', 'recipient' => 'string', 'content' => 'text', 'sent_at' => 'timestamp', 'is_confirmed' => 'boolean', 'confirmed_at' => 'timestamp', 'hash_code' => 'text', 'timestamp' => 'timestamp')





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('Equipments' => array('key' => array('equipment' => 'id')))





* Visibility: **public**


Methods
-------


### _list

    mixed app\models\PurchaseOrders::_list($query)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $query **mixed**



### unconfirmedPO

    mixed app\models\PurchaseOrders::unconfirmedPO()





* Visibility: **public**
* This method is **static**.



