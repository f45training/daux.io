app\models\FranchiseeTypes
===============






* Class name: FranchiseeTypes
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'type_name' => 'string', 'abbr' => 'string', 'timestamp' => 'datetime', 'slug' => 'string', 'schedulable' => 'boolean', 'week' => 'string', 'date_start' => 'timestamp', 'date_end' => 'timestamp')





* Visibility: **protected**


### $weeks

    public mixed $weeks = array(1 => "Monday", 2 => "Tuesday", 3 => "Wednesday", 4 => "Thursday", 5 => "Friday", 6 => "Saturday", 7 => "Sunday")





* Visibility: **public**
* This property is **static**.


Methods
-------


### getFranchiseeTypeNames

    mixed app\models\FranchiseeTypes::getFranchiseeTypeNames()





* Visibility: **public**
* This method is **static**.




### getFranchiseeTypeNamesWithID

    mixed app\models\FranchiseeTypes::getFranchiseeTypeNamesWithID()





* Visibility: **public**
* This method is **static**.




### getFranchiseeTypeNamesWithSlug

    mixed app\models\FranchiseeTypes::getFranchiseeTypeNamesWithSlug()





* Visibility: **public**
* This method is **static**.




### getFranchiseeTypeSlug

    mixed app\models\FranchiseeTypes::getFranchiseeTypeSlug($id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### getFranchiseeTypeName

    mixed app\models\FranchiseeTypes::getFranchiseeTypeName($id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### getFranchiseeTypeAbbr

    mixed app\models\FranchiseeTypes::getFranchiseeTypeAbbr($id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### isShowFranchiseeType

    mixed app\models\FranchiseeTypes::isShowFranchiseeType($franchisee_type_id, $weekSet, $timezone)





* Visibility: **public**


#### Arguments
* $franchisee_type_id **mixed**
* $weekSet **mixed**
* $timezone **mixed**


