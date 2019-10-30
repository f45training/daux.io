app\models\F45BlitzInfluencers
===============






* Class name: F45BlitzInfluencers
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'blog_id' => 'integer', 'user_id' => 'integer', 'name' => 'string', 'email' => 'string', 'instagram' => 'string', 'occupation' => 'string', 'notes' => 'text', 'status' => 'integer', 'timestamp' => 'timestamp')





* Visibility: **protected**


Methods
-------


### getListInfluencers

    \app\models\[type] app\models\F45BlitzInfluencers::getListInfluencers()

Returns list of influencers



* Visibility: **public**




### getInfluencersById

    \app\models\[type] app\models\F45BlitzInfluencers::getInfluencersById(\app\models\[type] $id)

Return Influencers by id



* Visibility: **public**


#### Arguments
* $id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### getInfluencersByBlogIdAndUserId

    \app\models\[type] app\models\F45BlitzInfluencers::getInfluencersByBlogIdAndUserId(\app\models\[type] $blog_id, \app\models\[type] $user_id, $is_count)

Returns influencers by `blog_id` and `user_id`



* Visibility: **public**


#### Arguments
* $blog_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $user_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $is_count **mixed**


