app\models\DraftStudios
===============






* Class name: DraftStudios
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'user_id' => 'integer', 'before_user_id' => 'string', 'sales_type' => 'string', 'other_sales_type' => 'string', 'contact_version_number' => 'string', 'sales_person_name' => 'string', 'legat_entity' => 'string', 'additional_notes' => 'text', 'country' => 'string', 'region' => 'string', 'state' => 'string', 'territory_population' => 'string', 'franchisee_name' => 'string', 'trading_name' => 'string', 'company_number' => 'string', 'key_person' => 'string', 'key_person_email' => 'string', 'key_person_mobile' => 'string', 'equipment_arrangement' => 'string', 'other_equip_arr' => 'string', 'address_line_one' => 'string', 'address_suburb_or_city' => 'string', 'address_state' => 'string', 'address_post_code' => 'string', 'address_country' => 'string', 'term_one' => 'integer', 'term_two' => 'integer', 'term_three' => 'integer', 'term_four' => 'integer', 'mango_map_exact_territory_name' => 'string', 'upload_territory_map' => 'string', 'equipment_sched_pdf' => 'string', 'financial_term_pdf' => 'string', 'aggrement_addendum' => 'string', 'date_reserved' => 'date', 'contract_date' => 'date', 'monthly_free_start_date' => 'date', 'currency' => 'string', 'deposit_taken' => 'string', 'created_at' => 'date', 'timestamp' => 'timestamp', 'sign_contract' => 'boolean')





* Visibility: **protected**


### $_forms

    public mixed $_forms = array('Sale Details' => array('description' => '', 'data' => array(array('type' => 'select', 'name' => 'Sale Type', 'field_name' => 'sales_type', 'description' => '', 'attr' => 'required', 'option' => array('' => '', 'New Sale' => 'New Sale', 'Re-sale' => 'Re-sale', 'Additional Studio in Existing Territory' => 'Additional Studio in Existing Territory', 'Other' => 'Other')), array('type' => 'input', 'name' => 'Contract Version Number', 'field_name' => 'contact_version_number', 'description' => '', 'attr' => 'required'), array('type' => 'input', 'name' => 'Sales person Name', 'field_name' => 'sales_person_name', 'description' => '', 'attr' => 'required'), array('type' => 'select', 'name' => 'Legal entity', 'field_name' => 'legat_entity', 'description' => '', 'attr' => 'required', 'option' => array('' => '', 'F45 Training Pty Ltd' => 'F45 Training Pty Ltd', 'F45 Training Canada' => 'F45 Training Canada', 'Functional F45 Training Limited' => 'Functional F45 Training Limited', 'F45 Training Asia Private Ltd - Singapore' => 'F45 Training Asia Private Ltd - Singapore', 'US INC' => 'US INC', 'F45 U LLC' => 'F45 U LLC')), array('type' => 'textarea', 'name' => 'Additional Notes', 'field_name' => 'additional_notes', 'description' => 'Any Extra Payment terms that finance needs to know about.', 'attr' => ''))), 'Sale Location' => array('description' => '', 'data' => array(array('type' => 'select', 'name' => 'Country', 'field_name' => 'country', 'description' => '', 'attr' => 'required', 'option' => array()), array('type' => 'select', 'name' => 'Region', 'field_name' => 'region', 'description' => '', 'attr' => 'required', 'option' => array()), array('type' => 'input', 'name' => 'State', 'field_name' => 'state', 'description' => 'PLEASE USE ABBREVIATION ONLY', 'attr' => 'required'), array('type' => 'input', 'name' => 'Territory Population', 'field_name' => 'territory_population', 'description' => '', 'attr' => 'required'))), 'Franchisee Details' => array('description' => '', 'data' => array(array('type' => 'input', 'name' => 'Franchisee Name', 'field_name' => 'franchisee_name', 'description' => 'If the Franchisee is a Company, insert the full name of the Company', 'attr' => 'required'), array('type' => 'input', 'name' => 'Trading Name', 'field_name' => 'trading_name', 'description' => '', 'attr' => 'required'), array('type' => 'input', 'name' => 'Company Number or ABN', 'field_name' => 'company_number', 'description' => '', 'attr' => 'required'), array('type' => 'input', 'name' => 'Key Person', 'field_name' => 'key_person', 'description' => '', 'attr' => 'required'), array('type' => 'email', 'name' => 'Key Person - Email', 'field_name' => 'key_person_email', 'description' => '', 'attr' => 'required'), array('type' => 'text', 'name' => 'Key Person - Mobile', 'field_name' => 'key_person_mobile', 'description' => '', 'attr' => 'required'), array('type' => 'select', 'name' => 'Equipment Arrangement', 'field_name' => 'equipment_arrangement', 'description' => '', 'attr' => 'required', 'option' => array('' => '', 'No Equipment Included (in Establishment Free)' => 'No Equipment Included (in Establishment Free)', 'F45 World Pack - US (No Install)' => 'F45 World Pack - US (No Install)', 'F45 World Pack - International (No Install)' => 'F45 World Pack - International (No Install)', 'Other' => 'Other')))), 'Franchisee Address' => array('description' => 'Please note, this is an important part of the form, as we will automate some physical welcome letters. This does have to have anything to do with the location they are reserving.', 'data' => array(array('type' => 'input', 'name' => 'Address Line 1', 'field_name' => 'address_line_one', 'description' => '', 'attr' => 'required'), array('type' => 'input', 'name' => 'Address Suburb/City', 'field_name' => 'address_suburb_or_city', 'description' => '', 'attr' => 'required'), array('type' => 'input', 'name' => 'Address State', 'field_name' => 'address_state', 'description' => 'Please use 2 letter code for US states: eg. NC or CA', 'attr' => 'required'), array('type' => 'input', 'name' => 'Address Postcode', 'field_name' => 'address_post_code', 'description' => '', 'attr' => 'required'), array('type' => 'select', 'name' => 'Address Country', 'field_name' => 'address_country', 'description' => '', 'attr' => 'required', 'option' => array()))), 'Agreement Terms' => array('description' => '', 'data' => array(array('type' => 'select', 'name' => 'Term 1 - Number of years', 'field_name' => 'term_one', 'description' => '', 'attr' => 'required', 'option' => array(0 => '0', 1 => '1', 2 => '2', 3 => '3', 4 => '4', 5 => '5', 6 => '6', 7 => '7', 8 => '8', 9 => '9', 10 => '10')), array('type' => 'select', 'name' => 'Term 2 - Number of years', 'field_name' => 'term_two', 'description' => '', 'attr' => 'required', 'option' => array(0 => '0', 1 => '1', 2 => '2', 3 => '3', 4 => '4', 5 => '5', 6 => '6', 7 => '7', 8 => '8', 9 => '9', 10 => '10')), array('type' => 'select', 'name' => 'Term 3 - Number of years', 'field_name' => 'term_three', 'description' => '', 'attr' => 'required', 'option' => array(0 => '0', 1 => '1', 2 => '2', 3 => '3', 4 => '4', 5 => '5', 6 => '6', 7 => '7', 8 => '8', 9 => '9', 10 => '10')), array('type' => 'select', 'name' => 'Term 4 - Number of years', 'field_name' => 'term_four', 'description' => '', 'attr' => 'required', 'option' => array(0 => '0', 1 => '1', 2 => '2', 3 => '3', 4 => '4', 5 => '5', 6 => '6', 7 => '7', 8 => '8', 9 => '9', 10 => '10')), array('type' => 'input', 'name' => 'Mango map exact territory name', 'field_name' => 'mango_map_exact_territory_name', 'description' => '', 'attr' => 'required'), array('type' => 'file', 'name' => 'Upload Territory Map Screenshot', 'field_name' => 'upload_territory_map', 'description' => '', 'attr' => 'required'), array('type' => 'file', 'name' => 'Equipment schedule PDF', 'field_name' => 'equipment_sched_pdf', 'description' => '', 'attr' => 'required'), array('type' => 'file', 'name' => 'Financial Terms PDF', 'field_name' => 'financial_term_pdf', 'description' => '', 'attr' => 'required'), array('type' => 'file', 'name' => 'Agreement Addendum', 'field_name' => 'aggrement_addendum', 'description' => '', 'attr' => ''))), 'Agreement Dates' => array('description' => '', 'data' => array(array('type' => 'date', 'name' => 'Date Reserved', 'field_name' => 'date_reserved', 'description' => '', 'attr' => 'required'), array('type' => 'date', 'name' => 'Contract Reserved', 'field_name' => 'contract_date', 'description' => '', 'attr' => 'required'), array('type' => 'date', 'name' => 'Monthly Fee Start Date', 'field_name' => 'monthly_free_start_date', 'description' => 'This is the date that the first Fee payment is DUE', 'attr' => 'required'))), 'Agreement Financial' => array('description' => '', 'data' => array(array('type' => 'select', 'name' => 'Currency', 'field_name' => 'currency', 'description' => '', 'attr' => 'required', 'option' => array()), array('type' => 'select', 'name' => 'Deposit Taken', 'field_name' => 'deposit_taken', 'description' => 'This is the reservation fee', 'attr' => 'required', 'option' => array('' => '', 'Yes' => 'Yes', 'No' => 'No')))))





* Visibility: **public**
* This property is **static**.


Methods
-------


### countryLists

    mixed app\models\DraftStudios::countryLists()





* Visibility: **public**
* This method is **static**.




### getAll

    mixed app\models\DraftStudios::getAll()





* Visibility: **public**
* This method is **static**.



