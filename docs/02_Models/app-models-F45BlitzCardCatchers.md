app\models\F45BlitzCardCatchers
===============






* Class name: F45BlitzCardCatchers
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'blog_id' => 'integer', 'user_id' => 'integer', 'business_name' => 'string', 'contact_person' => 'string', 'notes' => 'text', 'card_history' => 'text', 'status' => 'integer', 'timestamp' => 'timestamp')





* Visibility: **protected**


Methods
-------


### getListCardCatchers

    \app\models\[type] app\models\F45BlitzCardCatchers::getListCardCatchers()

Returns all list of card catchers



* Visibility: **public**




### getCardCatcherById

    \app\models\[type] app\models\F45BlitzCardCatchers::getCardCatcherById(\app\models\[type] $id)

Returns detail info of card catcher filter by id



* Visibility: **public**


#### Arguments
* $id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### getCardCatchersByUserIdAndBlogId

    \app\models\[type] app\models\F45BlitzCardCatchers::getCardCatchersByUserIdAndBlogId(\app\models\[type] $user_id, \app\models\[type] $blog_id, $is_count)

Returns data by `user_id` and `blog_id`



* Visibility: **public**


#### Arguments
* $user_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $blog_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $is_count **mixed**


