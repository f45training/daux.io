app\models\RevenueTotals
===============






* Class name: RevenueTotals
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    public mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'string', 'week' => 'string', 'year' => 'string', 'total' => 'float', 'timestamp' => 'timestamp')





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('Franchisees' => array('key' => array('franchisee_id' => 'id')))





* Visibility: **public**


Methods
-------


### total

    mixed app\models\RevenueTotals::total($params)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $params **mixed**


