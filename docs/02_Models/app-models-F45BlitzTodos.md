app\models\F45BlitzTodos
===============






* Class name: F45BlitzTodos
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'post_id' => 'integer', 'title' => 'string', 'description' => 'text', 'status' => 'integer', 'expected_date_execution' => 'datetime', 'timestamp' => 'timestamp')





* Visibility: **protected**


Methods
-------


### mysql_query

    mixed app\models\F45BlitzTodos::mysql_query($sql)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $sql **mixed**



### getOverduesByPostIdAndUserId

    \app\models\[type] app\models\F45BlitzTodos::getOverduesByPostIdAndUserId($post_id, $user_id)

Get Total todo overdue



* Visibility: **public**


#### Arguments
* $post_id **mixed**
* $user_id **mixed**



### getAllTodosByPostId

    \app\models\[type] app\models\F45BlitzTodos::getAllTodosByPostId(\app\models\[type] $post_id)

Get all to dos by `post_id`



* Visibility: **public**


#### Arguments
* $post_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### getTodoByPostId

    \app\models\[type] app\models\F45BlitzTodos::getTodoByPostId(\app\models\[type] $post_id)

Get all todos by `post_id`



* Visibility: **public**


#### Arguments
* $post_id **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### getTotalFinishedTodoByPostId

    mixed app\models\F45BlitzTodos::getTotalFinishedTodoByPostId($post_id, $user_id)





* Visibility: **public**


#### Arguments
* $post_id **mixed**
* $user_id **mixed**



### getTotalTodoCountByPost

    mixed app\models\F45BlitzTodos::getTotalTodoCountByPost($post_id)





* Visibility: **public**


#### Arguments
* $post_id **mixed**



### getTodosByPostIdAndUserId

    mixed app\models\F45BlitzTodos::getTodosByPostIdAndUserId($post_id, $user_id)





* Visibility: **public**


#### Arguments
* $post_id **mixed**
* $user_id **mixed**


