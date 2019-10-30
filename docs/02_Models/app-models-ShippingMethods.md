app\models\ShippingMethods
===============






* Class name: ShippingMethods
* Namespace: app\models
* Parent class: lithium\data\Model



Constants
----------


### FIX_STATUS

    const FIX_STATUS = 'fix'





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'method_name' => 'string', 'default_cost' => 'float', 'default_calculation' => 'float', 'default_api_endpoint' => 'string', 'other_details' => 'text', 'is_active' => 'integer')





* Visibility: **protected**


Methods
-------


### isStatusFix

    mixed app\models\ShippingMethods::isStatusFix($status_id, $data)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $status_id **mixed**
* $data **mixed**


