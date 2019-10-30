app\models\InjuryLogs
===============






* Class name: InjuryLogs
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    public mixed $_schema = array('id' => 'integer', 'first_name' => 'string', 'last_name' => 'string', 'email' => 'string', 'phone_number' => 'string', 'studio_id' => 'integer', 'program_id' => 'integer', 'class_time' => 'string', 'seriousness' => 'integer', 'equipment_used' => 'string', 'exercise_id' => 'integer', 'injury_type' => 'string', 'injury_location' => 'string', 'injury_side' => 'string', 'injury_activity' => 'string', 'injury_occured_by' => 'string', 'is_ambulance_called' => 'integer', 'is_admitted_at_hospital' => 'integer', 'hospital_admission_date' => 'timestamp', 'hospital_name' => 'string', 'doctor_name' => 'string', 'is_treatment_completed' => 'integer', 'comments' => 'string', 'created_at' => 'timestamp', 'studio_name' => 'string', 'trainer_present' => 'string', 'action_points' => 'string', 'outcome' => 'string', 'follow_up' => 'string', 'date_injured' => 'string')





* Visibility: **public**


### $belongsTo

    public mixed $belongsTo = array('Programs' => array('to' => 'Programs', 'key' => 'program_id'), 'Exercises' => array('to' => 'Exercises', 'key' => 'exercise_id'), 'Studio' => array('to' => 'Franchisees', 'key' => 'studio_id'))





* Visibility: **public**


Methods
-------


### fullName

    mixed app\models\InjuryLogs::fullName($entity)





* Visibility: **public**


#### Arguments
* $entity **mixed**



### ambulanceCalled

    mixed app\models\InjuryLogs::ambulanceCalled($entity)





* Visibility: **public**


#### Arguments
* $entity **mixed**



### admittedAtHospital

    mixed app\models\InjuryLogs::admittedAtHospital($entity)





* Visibility: **public**


#### Arguments
* $entity **mixed**



### treatmentCompleted

    mixed app\models\InjuryLogs::treatmentCompleted($entity)





* Visibility: **public**


#### Arguments
* $entity **mixed**



### weeklyInjuryLogs

    mixed app\models\InjuryLogs::weeklyInjuryLogs()





* Visibility: **public**
* This method is **static**.



