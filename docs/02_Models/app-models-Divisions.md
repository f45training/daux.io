app\models\Divisions
===============






* Class name: Divisions
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'name' => 'string', 'pricing' => 'text', 'timestamp' => 'timestamp')





* Visibility: **protected**


Methods
-------


### getAllDivisions

    \app\models\[type] app\models\Divisions::getAllDivisions()

Returns all divisions



* Visibility: **public**




### getStudiosByDivision

    \app\models\[type] app\models\Divisions::getStudiosByDivision(\app\models\[type] $div_id)

Returns studios by division id



* Visibility: **public**


#### Arguments
* $div_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### getAllStudiosByDivisions

    \app\models\[type] app\models\Divisions::getAllStudiosByDivisions()

Return all studios group by division



* Visibility: **public**



