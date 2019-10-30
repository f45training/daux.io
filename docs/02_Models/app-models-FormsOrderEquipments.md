app\models\FormsOrderEquipments
===============






* Class name: FormsOrderEquipments
* Namespace: app\models
* Parent class: lithium\data\Model



Constants
----------


### INVOICE_PREFIX

    const INVOICE_PREFIX = 'EQUIP'





### INVOICE_PREFIX_DEFAULT

    const INVOICE_PREFIX_DEFAULT = 'ORC'





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'json' => 'text', 'timestamp' => 'timestamp', 'submit_date' => 'timestamp', 'franchisee_name' => 'string', 'contact_person' => 'string', 'company_legal_name' => 'string', 'equipment_delivery_address' => 'string', 'address' => 'string', 'state' => 'string', 'city' => 'string', 'post_code' => 'string', 'tax_id' => 'string', 'email' => 'string', 'phone_no' => 'string', 'estimated_studio_opening_date' => 'string', 'earliest_date_to_receive_and_store_stock' => 'string', 'can_a_semi_trailer_access_your_delivery_area' => 'string', 'do_you_require_extra_flooring' => 'string', 'extra_sq_m' => 'string', 'ex_training_unit_area' => 'string', 'sled_track_length' => 'string', 'variation_notes' => 'string', 'contact_name' => 'string', 'additional_tiles' => 'string', 'additional_length' => 'string', 'wall_length' => 'string', 'wall_height' => 'string', 'wall_photo' => 'string', 'racing_stripe' => 'string', 'pylon_stripe' => 'string', 'secondary_delivery_address' => 'text', 'contact_name_2' => 'string', 'contact_number_2' => 'string', 'delivery_address_2' => 'text', 'can_you_accept_this_delivery_now' => 'string', 'stationary_studio_address' => 'text', 'stationary_phone' => 'string', 'stationary_email' => 'string', 'stationary_facebook' => 'string', 'stationary_instagram' => 'string', 'stationary_secondary_delivery_address' => 'text', 'stationary_contact_name_2' => 'string', 'stationary_contact_number_2' => 'string', 'stationary_delivery_address_2' => 'text', 'stationary_can_you_accept_this_delivery_now' => 'string', 'is_sent' => 'boolean')





* Visibility: **protected**


Methods
-------


### getLatest

    false app\models\FormsOrderEquipments::getLatest($franchisee_id, $for_invoice)

get latest



* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchisee_id **mixed** - &lt;p&gt;(string)&lt;/p&gt;
* $for_invoice **mixed**



### makeAFile

    mixed app\models\FormsOrderEquipments::makeAFile($invoice_pdf, $dir, $file_name, $file_format, $return)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $invoice_pdf **mixed**
* $dir **mixed**
* $file_name **mixed**
* $file_format **mixed**
* $return **mixed**


