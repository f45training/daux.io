app\models\FranchiseeLanguages
===============






* Class name: FranchiseeLanguages
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'schedule_tv_language_id' => 'integer', 'workout_tv_language_id' => 'integer', 'show_in_playbook' => 'boolean')





* Visibility: **protected**


### $belongsTo

    public mixed $belongsTo = array('Franchisees' => array('key' => 'franchisee_id'))





* Visibility: **public**



