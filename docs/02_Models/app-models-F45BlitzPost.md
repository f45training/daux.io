app\models\F45BlitzPost
===============






* Class name: F45BlitzPost
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $user_id

    public mixed $user_id





* Visibility: **public**


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'blog_id' => 'integer', 'title' => 'string', 'description' => 'text', 'thumbnail_image_url' => 'string', 'landscape_image_url' => 'string', 'status' => 'integer', 'timestamp' => 'timestamp', 'enable_at' => 'datetime')





* Visibility: **protected**


Methods
-------


### mysql_query

    mixed app\models\F45BlitzPost::mysql_query($sql)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $sql **mixed**



### getBlogPosts

    \app\models\[type] app\models\F45BlitzPost::getBlogPosts(\app\models\[type] $blog_id, $user_id)

Returns all blog posts filter by `blog_id`



* Visibility: **public**


#### Arguments
* $blog_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $user_id **mixed**



### getPostById

    \app\models\[type] app\models\F45BlitzPost::getPostById(\app\models\[type] $id, $user_id)

Returns Post details



* Visibility: **public**


#### Arguments
* $id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;
* $user_id **mixed**


