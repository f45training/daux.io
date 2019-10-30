app\models\EquipmentDetails
===============






* Class name: EquipmentDetails
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'pack_price_excluding_tax' => 'float', 'shipping_price_excluding_tax' => 'float', 'currency' => 'string', 'notes' => 'text', 'date_ordered' => 'date', 'order_address' => 'string', 'earliest_date_to_receive_and_store_stock' => 'date', 'overall_status' => 'string', 'invoice' => 'string', 'invoice_paid' => 'boolean', 'timestamp' => 'integer', 'legal_entity' => 'string', 'date_paid' => 'date', 'secondary_order_address' => 'string', 'check_sec_address' => 'boolean', 'invoice_number' => 'string')





* Visibility: **protected**


### $legal_entity

    public mixed $legal_entity = array('' => 'Select From Entities', 'F45 Training Pty Ltd' => 'F45 Training Pty Ltd', 'F45 Training Canada' => 'F45 Training Canada', 'Functional 45 Training Limited' => 'Functional 45 Training Limited', 'F45 Training Asia Private Ltd  - Singapore' => 'F45 Training Asia Private Ltd  - Singapore', 'F45 Training LLC' => 'F45 Training LLC', 'F45 Training Incorporated' => 'F45 Training Incorporated')





* Visibility: **public**
* This property is **static**.


### $validates

    public mixed $validates = array('franchisee_id' => array(array('notEmpty', 'message' => 'You must include a franchisee_id.')))





* Visibility: **public**



