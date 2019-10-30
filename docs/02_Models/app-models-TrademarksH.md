app\models\TrademarksH
===============






* Class name: TrademarksH
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'title' => 'string', 'owner' => 'string', 'created_at' => 'datetime', 'updated_at' => 'datetime', 'timestamp' => 'timestamp', 'is_deleted' => 'boolean')





* Visibility: **protected**


### $validates

    public mixed $validates = array('owner' => array(array('notEmpty', 'message' => 'You must include a owner.')), 'title' => array(array('notEmpty', 'message' => 'You must include a title.')))





* Visibility: **public**


Methods
-------


### getDetailsById

    \app\models\[type] app\models\TrademarksH::getDetailsById(\app\models\[type] $tmh_id)

Return details by id



* Visibility: **public**


#### Arguments
* $tmh_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### findById

    \app\models\[type] app\models\TrademarksH::findById(\app\models\[type] $tmh_id)

[findById description]



* Visibility: **public**


#### Arguments
* $tmh_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;


