app\models\MusicLicensingBodiesRelation
===============






* Class name: MusicLicensingBodiesRelation
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_meta

    protected mixed $_meta = array('source' => 'music_licensing_bodies_relation')





* Visibility: **protected**


### $columns

    public mixed $columns = array('id', 'music_licensing_countries_id', 'music_licensing_bodies_id')





* Visibility: **public**
* This property is **static**.


### $belongsTo

    public mixed $belongsTo = array('MusicLicensingCountries' => array('key' => array('music_licensing_countries_id' => 'id')), 'MusicLicensingBodies' => array('key' => array('music_licensing_bodies_id' => 'id')))





* Visibility: **public**



