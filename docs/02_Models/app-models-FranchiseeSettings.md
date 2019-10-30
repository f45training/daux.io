app\models\FranchiseeSettings
===============






* Class name: FranchiseeSettings
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'is_master' => 'boolean', 'is_prodigy' => 'boolean', 'is_f45_training' => 'boolean', 'is_prodigy_files_access' => 'boolean', 'is_show_compliance_form' => 'boolean', 'is_recovery' => 'boolean', 'is_prodigy_marketing_enabled' => 'boolean', 'is_non_compliant' => 'boolean', 'non_compliant_note' => 'text', 'prodigy_facebook' => 'string', 'prodigy_instagram' => 'string', 'prodigy_phone' => 'string', 'prodigy_email' => 'string', 'free_trial_copy' => 'string', 'prodigy_enabled_email' => 'boolean', 'prodigy_enabled_sms' => 'boolean', 'use_playbook2' => 'boolean', 'is_checking_prodigy_enabled' => 'boolean', 'prodigy_opening_date' => 'date', 'studio_manager_approval' => 'boolean', 'studio_manager_approval_date' => 'date', 'performance_manager_admin_id' => 'integer')





* Visibility: **protected**


Methods
-------


### enabledFranchiseeTypes

    mixed app\models\FranchiseeSettings::enabledFranchiseeTypes($enabledItems, $gymId)





* Visibility: **public**


#### Arguments
* $enabledItems **mixed**
* $gymId **mixed**



### convertStringValue

    mixed app\models\FranchiseeSettings::convertStringValue($item)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $item **mixed**


