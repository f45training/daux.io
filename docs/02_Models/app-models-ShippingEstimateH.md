app\models\ShippingEstimateH
===============






* Class name: ShippingEstimateH
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $default_config

    public mixed $default_config = "AU"





* Visibility: **public**
* This property is **static**.


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'country' => 'string', 'google_address' => 'string', 'latitude' => 'string', 'longitude' => 'string', 'overall_shipping_cost' => 'float')





* Visibility: **protected**


Methods
-------


### allCountriesFromFranchisees

    mixed app\models\ShippingEstimateH::allCountriesFromFranchisees()

Array of Countries



* Visibility: **public**
* This method is **static**.




### getAddress

    \app\models\($ch) app\models\ShippingEstimateH::getAddress(\app\models\($address) $address)

Equipment country



* Visibility: **public**
* This method is **static**.


#### Arguments
* $address **app\models\($address)**



### getShipping

    mixed app\models\ShippingEstimateH::getShipping($country, $postal_code, $suburb)

Get Shipping Price



* Visibility: **public**
* This method is **static**.


#### Arguments
* $country **mixed** - &lt;p&gt;(string)&lt;/p&gt;
* $postal_code **mixed**
* $suburb **mixed**



### parseItems

    mixed app\models\ShippingEstimateH::parseItems($details)

Parse other details



* Visibility: **public**
* This method is **static**.


#### Arguments
* $details **mixed**


