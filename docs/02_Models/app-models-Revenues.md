app\models\Revenues
===============






* Class name: Revenues
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    public  $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'location' => 'string', 'discount' => 'float', 'tax' => 'float', 'total' => 'float', 'start_date' => 'date', 'end_date' => 'date', 'filename' => 'string', 'timestamp' => 'timestamp', 'discount_usd' => 'float', 'tax_usd' => 'float', 'total_usd' => 'float', 'currency' => 'string')





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('Franchisees' => array('key' => array('franchisee_id' => 'id')))





* Visibility: **public**


Methods
-------


### tabularFormat

    mixed app\models\Revenues::tabularFormat($dates, $min_year, $max_year, $filters, $limit)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $dates **mixed**
* $min_year **mixed**
* $max_year **mixed**
* $filters **mixed**
* $limit **mixed**



### revenueMetrics

    mixed app\models\Revenues::revenueMetrics($filters, $limit)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $filters **mixed**
* $limit **mixed**



### getRevenueUniqueLocations

    mixed app\models\Revenues::getRevenueUniqueLocations($page)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $page **mixed**



### recentUpload

    mixed app\models\Revenues::recentUpload()





* Visibility: **public**
* This method is **static**.




### missing

    mixed app\models\Revenues::missing($params)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $params **mixed**



### missingData

    mixed app\models\Revenues::missingData($franchiseeId)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchiseeId **mixed**



### mindbodyName

    mixed app\models\Revenues::mindbodyName($franchiseeId)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchiseeId **mixed**



### getAllRevenueLogsByYear

    mixed app\models\Revenues::getAllRevenueLogsByYear($params)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $params **mixed**



### findByLocationName

    mixed app\models\Revenues::findByLocationName($loc)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $loc **mixed**


