app\models\TrademarksD
===============






* Class name: TrademarksD
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'trademarks_h_id' => 'integer', 'refno' => 'string', 'property_type' => 'string', 'f45_ref' => 'string', 'country' => 'string', 'official_no' => 'string', 'new_renewal_date' => 'date', 'case_status' => 'string', 'created_at' => 'datetime', 'updated_at' => 'datetime', 'timestamp' => 'timestamp', 'is_deleted' => 'boolean')





* Visibility: **protected**


### $validates

    public mixed $validates = array('refno' => array(array('notEmpty', 'message' => 'You must include a refno.')))





* Visibility: **public**


Methods
-------


### getPropertyTypes

    \app\models\[type] app\models\TrademarksD::getPropertyTypes()

Return Property Types



* Visibility: **public**




### getCaseStatuses

    \app\models\[type] app\models\TrademarksD::getCaseStatuses()

Return Case Statuses



* Visibility: **public**




### findById

    \app\models\[type] app\models\TrademarksD::findById(\app\models\[type] $id)

Return model object by id



* Visibility: **public**


#### Arguments
* $id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;


