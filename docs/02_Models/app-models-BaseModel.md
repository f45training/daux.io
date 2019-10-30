app\models\BaseModel
===============






* Class name: BaseModel
* Namespace: app\models
* Parent class: lithium\data\Model







Methods
-------


### getSchema

    mixed app\models\BaseModel::getSchema()

Returns all fields for a model, with its default values in place



* Visibility: **public**




### extract

    mixed app\models\BaseModel::extract(array $array)

Extracts data for this model, usually from a request parameter in array, by key



* Visibility: **public**
* This method is **static**.


#### Arguments
* $array **array** - &lt;p&gt;The array to exract from&lt;/p&gt;



### toArray

    mixed app\models\BaseModel::toArray(\lithium\data\Entity $entity)

Returns ->to('array') is existing, else use the default schema in place



* Visibility: **public**
* This method is **static**.


#### Arguments
* $entity **lithium\data\Entity** - &lt;p&gt;instance&lt;/p&gt;


