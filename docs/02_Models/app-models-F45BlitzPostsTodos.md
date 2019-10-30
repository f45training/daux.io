app\models\F45BlitzPostsTodos
===============






* Class name: F45BlitzPostsTodos
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'post_id' => 'integer', 'todo_id' => 'integer', 'user_id' => 'integer', 'todo_status' => 'integer', 'notes' => 'text', 'status' => 'integer', 'timestamp' => 'timestamp')





* Visibility: **protected**


Methods
-------


### mysql_query

    mixed app\models\F45BlitzPostsTodos::mysql_query($sql)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $sql **mixed**



### findAttributesPostTodos

    mixed app\models\F45BlitzPostsTodos::findAttributesPostTodos($post_id, $user_id, $todo_id)





* Visibility: **public**


#### Arguments
* $post_id **mixed**
* $user_id **mixed**
* $todo_id **mixed**



### getAllTodosByPostAndUser

    mixed app\models\F45BlitzPostsTodos::getAllTodosByPostAndUser($post_id, $user_id)





* Visibility: **public**


#### Arguments
* $post_id **mixed**
* $user_id **mixed**


