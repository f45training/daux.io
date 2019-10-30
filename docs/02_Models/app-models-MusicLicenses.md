app\models\MusicLicenses
===============






* Class name: MusicLicenses
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $columns

    public mixed $columns = array('franchisee_id', 'music_licensing_bodies_relation_id', 'name', 'file_url', 'license_date', 'expiry_date', 'status', 'is_deleted', 'created_at')





* Visibility: **public**
* This property is **static**.


### $STATUS_PENDING

    public mixed $STATUS_PENDING





* Visibility: **public**
* This property is **static**.


### $STATUS_APPROVED

    public mixed $STATUS_APPROVED = 1





* Visibility: **public**
* This property is **static**.


### $STATUS_REJECTED

    public mixed $STATUS_REJECTED = 2





* Visibility: **public**
* This property is **static**.


### $STATUS_EXPIRED

    public mixed $STATUS_EXPIRED = 3





* Visibility: **public**
* This property is **static**.


### $belongsTo

    public mixed $belongsTo = array('MusicLicensingBodiesRelation' => array('key' => array('music_licensing_bodies_relation_id' => 'id')))





* Visibility: **public**



