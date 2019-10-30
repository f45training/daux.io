app\models\Payments
===============






* Class name: Payments
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchisee_id' => 'integer', 'file_url' => 'string', 'date_upload' => 'datetime', 'reference_no' => 'string', 'payable_to' => 'string', 'bank_details' => 'string', 'currency' => 'string', 'amount' => 'float', 'paid_date' => 'datetime', 'notes' => 'text', 'payment_request' => 'integer', 'paid' => 'integer', 'timestamp' => 'timestamp')

Schema



* Visibility: **protected**


### $belongsTo

    public mixed $belongsTo = array('Franchisees' => array('key' => array('franchisee_id' => 'id')), 'Currencies' => array('key' => array('abbr' => 'currency')))

Relationships



* Visibility: **public**


### $payment_status

    public mixed $payment_status = array('1' => 'Require Payment', '2' => 'Paid')

Payment status



* Visibility: **public**
* This property is **static**.



