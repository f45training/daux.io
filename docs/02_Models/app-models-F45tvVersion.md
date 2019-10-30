app\models\F45tvVersion
===============






* Class name: F45tvVersion
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'versionname' => 'string', 'versionnumber' => 'string', 'APKURL' => 'string', 'version_hash' => 'string', 'allow_public_upgrade' => 'boolean', 'minimum_timeline_version' => 'string', 'description' => 'text', 'timestamp' => 'timestamp')





* Visibility: **protected**


Methods
-------


### getTimeAgo

    \app\models\[type] app\models\F45tvVersion::getTimeAgo(\app\models\[type] $ptime)

[getTimeAgo description]



* Visibility: **private**


#### Arguments
* $ptime **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### getTvLastSeens

    \app\models\[type] app\models\F45tvVersion::getTvLastSeens(\app\models\[type] $request_id, $showEmptyTvData)

Handles Tv Last Seen details



* Visibility: **public**


#### Arguments
* $request_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $showEmptyTvData **mixed**



### sortTVLastSeen

    mixed app\models\F45tvVersion::sortTVLastSeen($data)





* Visibility: **public**


#### Arguments
* $data **mixed**



### getF45TvLogs

    mixed app\models\F45tvVersion::getF45TvLogs()





* Visibility: **public**



