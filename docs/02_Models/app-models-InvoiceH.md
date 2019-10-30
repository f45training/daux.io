app\models\InvoiceH
===============






* Class name: InvoiceH
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'start_date' => 'date', 'end_date' => 'date', 'notes' => 'string', 'paid_amount' => 'float', 'total' => 'float', 'status' => 'string', 'date_created' => 'timestamp')





* Visibility: **protected**


### $hasMany

    public mixed $hasMany = array('InvoiceD' => array('key' => array('id' => 'invoice_id')))





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('Franchisees' => array('key' => array('franchisee_id' => 'id')))





* Visibility: **public**


### $status

    public mixed $status = array('Pending', 'Paid', 'Overdue', 'Void', 'Waived')





* Visibility: **public**
* This property is **static**.



