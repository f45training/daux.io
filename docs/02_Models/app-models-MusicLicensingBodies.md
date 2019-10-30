app\models\MusicLicensingBodies
===============






* Class name: MusicLicensingBodies
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $hasMany

    public mixed $hasMany = array('MusicLicensingBodiesRelation' => array('key' => array('id' => 'music_licensing_bodies_id')))





* Visibility: **public**


### $columns

    public mixed $columns = array('id', 'abbreviation', 'description', 'website')





* Visibility: **public**
* This property is **static**.


Methods
-------


### getWithLatestLicenseByCountryAndFranchisee

    mixed app\models\MusicLicensingBodies::getWithLatestLicenseByCountryAndFranchisee($country_id, $franchisee_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $country_id **mixed**
* $franchisee_id **mixed**


