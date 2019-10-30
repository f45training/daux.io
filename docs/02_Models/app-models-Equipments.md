app\models\Equipments
===============






* Class name: Equipments
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $equipments

    public mixed $equipments = array()





* Visibility: **public**
* This property is **static**.


### $overall_status

    public mixed $overall_status = array('Price Required', 'Pending Order', 'Pending Payment', 'Ship Now', 'Dispatched', 'Complete')





* Visibility: **public**
* This property is **static**.


### $statuses

    public mixed $statuses = array('Not Set', 'Price Required', 'Pending Order', 'Ship Now', 'Dispatched', 'PO Sent', 'PO Confirmed', 'Ready for Order')





* Visibility: **public**
* This property is **static**.


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'gym_id' => 'integer', 'rename' => 'string', 'equipment' => 'integer', 'status' => 'integer', 'supplier' => 'integer', 'date_ordered' => 'timestamp', 'expected_arrival' => 'timestamp', 'received_date' => 'timestamp', 'earliest_received_date' => 'timestamp', 'tracking_code' => 'string', 'reference_id' => 'string', 'notes' => 'string', 'invoice' => 'string', 'deposit_paid' => 'integer', 'shipping_quoted' => 'string', 'price_quoted' => 'float', 'currency' => 'string', 'amount' => 'float', 'paid_date' => 'timestamp', 'paid' => 'integer', 'product_pricing' => 'string', 'shipping_price' => 'string', 'timestamp' => 'timestamp', 'details' => 'text', 'invoice_files' => 'string', 'po_details' => 'text', 'equipment_notes' => 'text')





* Visibility: **protected**


### $validates

    public mixed $validates = array('equipment' => array(array('notEmpty', 'message' => 'You must include an equipment.')))





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('EquipmentNames' => array('key' => array('equipment' => 'id')), 'EquipmentDetails' => array('key' => array('gym_id' => 'franchisee_id')), 'Franchisees' => array('key' => array('gym_id' => 'id')), 'ShippingEstimateD' => array('key' => array('equipment' => 'equipment')), 'Suppliers' => array('key' => array('supplier' => 'id')))





* Visibility: **public**


Methods
-------


### __construct

    mixed app\models\Equipments::__construct()

Add Constructor Function to Set Equipments



* Visibility: **public**




### equipments

    mixed app\models\Equipments::equipments()

Get All Equipment Names



* Visibility: **public**
* This method is **static**.




### equipments_raw

    array app\models\Equipments::equipments_raw()

Get All Raw Equipment Names



* Visibility: **public**
* This method is **static**.




### dashboard_required

    mixed app\models\Equipments::dashboard_required($fid)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $fid **mixed**



### dashboard_table

    mixed app\models\Equipments::dashboard_table($fid)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $fid **mixed**


