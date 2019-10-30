app\models\F45BlitzBlog
===============






* Class name: F45BlitzBlog
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array()





* Visibility: **protected**


Methods
-------


### mysql_query

    mixed app\models\F45BlitzBlog::mysql_query($sql)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $sql **mixed**



### findBlogIdByName

    \app\models\[type] app\models\F45BlitzBlog::findBlogIdByName(\app\models\[type] $blog_name)

Returns blog's information by name



* Visibility: **public**


#### Arguments
* $blog_name **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### getBlogById

    \app\models\[type] app\models\F45BlitzBlog::getBlogById(\app\models\[type] $id)

Return blog information by `blog_id`



* Visibility: **public**


#### Arguments
* $id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### getActiveBlog

    \app\models\[type] app\models\F45BlitzBlog::getActiveBlog()

Returns active blog



* Visibility: **public**



