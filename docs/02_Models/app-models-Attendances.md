app\models\Attendances
===============






* Class name: Attendances
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'studio_name' => 'string', 'start_date' => 'date', 'end_date' => 'date', 'region' => 'string', 's3_link' => 'text', 'location' => 'string', 'paid_visits' => 'string', 'unique_clients' => 'string', 'comp_guest_visits' => 'string', 'total_visits' => 'string', 'timestamp' => 'timestamp')





* Visibility: **protected**


Methods
-------


### mysql_query

    mixed app\models\Attendances::mysql_query($sql)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $sql **mixed**



### searchDataByDateRange

    mixed app\models\Attendances::searchDataByDateRange($options)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $options **mixed**



### searchDataByMonth

    mixed app\models\Attendances::searchDataByMonth($options)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $options **mixed**



### getDatesFromRange

    mixed app\models\Attendances::getDatesFromRange($start, $end)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $start **mixed**
* $end **mixed**



### getAllByYear

    mixed app\models\Attendances::getAllByYear($year)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $year **mixed**


