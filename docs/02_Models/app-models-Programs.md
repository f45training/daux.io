app\models\Programs
===============






* Class name: Programs
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'name' => 'string', 'description' => 'text', 'slug_name' => 'string', 'workout_video_id' => 'integer', 'movement_image_filename' => 'string', 'program_json_data' => 'text', 'max_people_per_station' => 'integer', 'timestamp' => 'timestamp', 'number_of_stations' => 'integer')





* Visibility: **protected**


Methods
-------


### listPrograms

    mixed app\models\Programs::listPrograms()





* Visibility: **public**
* This method is **static**.




### findAll

    mixed app\models\Programs::findAll()





* Visibility: **public**
* This method is **static**.




### findByName

    object app\models\Programs::findByName(string $name)

Get all the program details using workout name.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string** - &lt;p&gt;Name of program&lt;/p&gt;



### getMaxPeoplePerProgramByName

    mixed app\models\Programs::getMaxPeoplePerProgramByName($name)





* Visibility: **public**


#### Arguments
* $name **mixed**


