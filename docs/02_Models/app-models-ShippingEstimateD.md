app\models\ShippingEstimateD
===============






* Class name: ShippingEstimateD
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_default_ETA

    public mixed $_default_ETA = '7 weeks'





* Visibility: **public**
* This property is **static**.


### $_package_types

    public mixed $_package_types = array('Carton' => 'Carton', 'Heavy Carton' => 'Heavy Carton', 'Skid' => 'Skid', 'Pallet' => 'Pallet', 'Tube' => 'Tube', 'Crate' => 'Crate', 'Satchel/Bag' => 'Satchel/Bag', 'Other/Misc' => 'Other/Misc', 'Unpackaged' => 'Unpackaged', 'A3 Satchel' => 'A3 Satchel', 'A5 Satchel' => 'A5 Satchel')





* Visibility: **public**
* This property is **static**.


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'header' => 'integer', 'equipment' => 'integer', 'supplier' => 'integer', 'included_in_price' => 'integer', 'cost_price_currency' => 'string', 'cost_price' => 'float', 'is_gst_included' => 'integer', 'selling_price_currency' => 'string', 'selling_price' => 'float', 'shipping_method' => 'integer', 'shipping_price_currency' => 'string', 'shipping_price' => 'float', 'in_stock_percent' => 'float', 'standard_ETA' => 'string', 'from_address' => 'string', 'from_latitude' => 'string', 'from_longitude' => 'string', 'other_details' => 'text')





* Visibility: **protected**



