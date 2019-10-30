app\models\InvoiceD
===============






* Class name: InvoiceD
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'invoice_id' => 'integer', 'type' => 'string', 'description' => 'string', 'tax' => 'string', 'qty' => 'float', 'price' => 'float')





* Visibility: **protected**


### $hasOne

    public mixed $hasOne = array('InvoiceH' => array('key' => array('invoice_id' => 'id')))





* Visibility: **public**



