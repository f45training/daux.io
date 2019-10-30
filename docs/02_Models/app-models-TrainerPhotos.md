app\models\TrainerPhotos
===============






* Class name: TrainerPhotos
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'user_id' => 'integer', 'franchisee_id' => 'integer', 'photo_url' => 'string', 'status' => 'string', 'timestamp' => 'timestamp')





* Visibility: **protected**


### $belongsTo

    public mixed $belongsTo = array('Users' => array('to' => 'Users', 'key' => 'user_id'))





* Visibility: **public**



