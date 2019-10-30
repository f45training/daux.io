app\models\GlofoxImplementations
===============






* Class name: GlofoxImplementations
* Namespace: app\models
* Parent class: [app\models\BaseModel](app-models-BaseModel.md)





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'branch_id' => 'string', 'branch_id_prodigy' => 'string', 'trial_id' => 'string', 'trial_id_prodigy' => 'string', 'membership_id' => 'string', 'membership_id_prodigy' => 'string', 'blue_trial_button' => 'text', 'blue_trial_button_prodigy' => 'text', 'red_button_membership_packages' => 'text', 'red_button_membership_packages_prodigy' => 'text', 'schedule_page' => 'text', 'schedule_page_prodigy' => 'text', 'trial_lead_management_script' => 'text', 'trial_lead_management_script_prodigy' => 'text', 'use_default_scripts' => 'boolean', 'use_default_scripts_prodigy' => 'boolean', 'timestamp' => 'timestamp')





* Visibility: **protected**


Methods
-------


### getSchema

    mixed app\models\BaseModel::getSchema()

Returns all fields for a model, with its default values in place



* Visibility: **public**
* This method is defined by [app\models\BaseModel](app-models-BaseModel.md)




### extract

    mixed app\models\BaseModel::extract(array $array)

Extracts data for this model, usually from a request parameter in array, by key



* Visibility: **public**
* This method is **static**.
* This method is defined by [app\models\BaseModel](app-models-BaseModel.md)


#### Arguments
* $array **array** - &lt;p&gt;The array to exract from&lt;/p&gt;



### toArray

    mixed app\models\BaseModel::toArray(\lithium\data\Entity $entity)

Returns ->to('array') is existing, else use the default schema in place



* Visibility: **public**
* This method is **static**.
* This method is defined by [app\models\BaseModel](app-models-BaseModel.md)


#### Arguments
* $entity **lithium\data\Entity** - &lt;p&gt;instance&lt;/p&gt;


