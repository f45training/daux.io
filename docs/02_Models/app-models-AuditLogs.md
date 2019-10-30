app\models\AuditLogs
===============






* Class name: AuditLogs
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'id_admin' => 'integer', 'time' => 'string', 'ip' => 'string', 'action' => 'text', 'request_url' => 'string', 'requestor' => 'string', 'timestamp' => 'timestamp', 'model' => 'string', 'object_id' => 'integer')





* Visibility: **protected**


Methods
-------


### mysql_query

    mixed app\models\AuditLogs::mysql_query($sql)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $sql **mixed**



### getStatusCheckListLog

    \app\models\[type] app\models\AuditLogs::getStatusCheckListLog($request_id)

Return Last Approved on Induction



* Visibility: **public**


#### Arguments
* $request_id **mixed**



### playoffsReport

    \app\models\[type] app\models\AuditLogs::playoffsReport()

Return gyms that set their week and day to week 309 and day 5 and how long does it take before they change to correct week/day



* Visibility: **public**
* This method is **static**.




### getTimeAgo

    mixed app\models\AuditLogs::getTimeAgo($ftime, $ptime)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $ftime **mixed**
* $ptime **mixed**


