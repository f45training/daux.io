app\models\Schedules
===============






* Class name: Schedules
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchise_id' => 'integer', 'week' => 'integer', 'week_day' => 'integer', 'time' => 'string', 'workout_name' => 'string', 'franchisee_type_id' => 'integer')





* Visibility: **protected**


### $belongsTo

    public mixed $belongsTo = array('franchisees' => array('key' => array('franchise_id' => 'id')))





* Visibility: **public**


Methods
-------


### getScheduleDay

    mixed app\models\Schedules::getScheduleDay(\app\models\Franchisees $franchisee, integer $day)

To get schedules week day for franchisee and a given day



* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchisee **[app\models\Franchisees](app-models-Franchisees.md)** - &lt;p&gt;the franchisee to check properties with&lt;/p&gt;
* $day **integer** - &lt;p&gt;The week day to resolve too for some condition based on props&lt;/p&gt;


