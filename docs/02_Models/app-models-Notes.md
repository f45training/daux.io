app\models\Notes
===============






* Class name: Notes
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchise_id' => 'integer', 'id_admin' => 'integer', 'note' => 'text', 'timestamp' => 'timestamp', 'note_for' => 'string')





* Visibility: **protected**


### $belongsTo

    public mixed $belongsTo = array('Admins' => array('key' => array('id_admin' => 'id')))





* Visibility: **public**


### $validates

    public mixed $validates = array('franchise_id' => array(array('notEmpty', 'message' => 'You must include franchise id')), 'note' => array(array('notEmpty', 'message' => 'You must include note')))





* Visibility: **public**


Methods
-------


### del

    mixed app\models\Notes::del($id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### new_note

    mixed app\models\Notes::new_note($franchisee_id, $admin_id, $note)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $franchisee_id **mixed**
* $admin_id **mixed**
* $note **mixed**



### update_note

    mixed app\models\Notes::update_note($note_id, $admin_id, $note)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $note_id **mixed**
* $admin_id **mixed**
* $note **mixed**



### get_studio_notes

    mixed app\models\Notes::get_studio_notes($id, $limit, $offset)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**
* $limit **mixed**
* $offset **mixed**


