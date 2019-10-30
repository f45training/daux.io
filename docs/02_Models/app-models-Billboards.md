app\models\Billboards
===============






* Class name: Billboards
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchise_id' => 'integer', 'advertisement_type' => 'string', 'title' => 'string', 'description' => 'text', 'quote' => 'text', 'billboard_image' => 'string', 'when' => 'string', 'where' => 'string', 'time' => 'string', 'playoff_score' => 'string', 'qualifications' => 'string', 'member' => 'string', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $belongsTo

    public mixed $belongsTo = array('Franchisees' => array('key' => 'franchise_id'))





* Visibility: **public**


### $advertisementType

    public mixed $advertisementType = array('playoffs' => 'Playoffs', 'playoffs2' => 'Playoffs 2', 'dj' => 'Disk Jockey', 'holloween' => 'Holloween', 'trainer' => 'Trainer', 'christmas' => 'Christmas', 'drink' => 'Drink', 'easter' => 'Easter', 'calorie' => 'Calorie', 'sessions' => 'Sessions', 'studio' => 'Studio', 'person' => 'Person', 'thanksgiving' => 'Thanksgiving', 'skinny' => 'Skinny')





* Visibility: **public**
* This property is **static**.



