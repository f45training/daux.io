app\controllers\DropboxController
===============






* Class name: DropboxController
* Namespace: app\controllers
* Parent class: lithium\action\Controller





Properties
----------


### $disAllowed

    public mixed $disAllowed = array('index', 'view', 'add', 'edit', 'delete', 'publish', 'unpublish')





* Visibility: **public**


### $accessToken

    private mixed $accessToken = "RBmtQelTCkIAAAAAAABVFFt20ZqWnAxmpaDBHaH4RTe1j3Trx0qTNhbOsxfyIK-7"





* Visibility: **private**


### $base_folder

    private mixed $base_folder = "/F45 PLAYBOOK"





* Visibility: **private**


### $only_new

    private mixed $only_new





* Visibility: **private**


### $adapter

    private mixed $adapter





* Visibility: **private**


### $appSecret

    private mixed $appSecret = 'bx1lzj9810w6trs'





* Visibility: **private**


Methods
-------


### _init

    mixed app\controllers\DropboxController::_init()





* Visibility: **public**




### folder

    mixed app\controllers\DropboxController::folder()





* Visibility: **public**




### thumb_from_file_type

    mixed app\controllers\DropboxController::thumb_from_file_type($contents, $folder)





* Visibility: **public**


#### Arguments
* $contents **mixed**
* $folder **mixed**



### search

    mixed app\controllers\DropboxController::search()





* Visibility: **public**




### download

    mixed app\controllers\DropboxController::download()





* Visibility: **public**




### download2

    mixed app\controllers\DropboxController::download2()





* Visibility: **public**




### folder_formatting

    mixed app\controllers\DropboxController::folder_formatting()





* Visibility: **public**




### create_img_thumb

    mixed app\controllers\DropboxController::create_img_thumb($pdf_location, $folder)





* Visibility: **public**


#### Arguments
* $pdf_location **mixed**
* $folder **mixed**



### create_video_thumb

    mixed app\controllers\DropboxController::create_video_thumb($file_location, $folder)





* Visibility: **public**


#### Arguments
* $file_location **mixed**
* $folder **mixed**



### create_pdf_thumb

    mixed app\controllers\DropboxController::create_pdf_thumb($pdf_location, $folder)





* Visibility: **public**


#### Arguments
* $pdf_location **mixed**
* $folder **mixed**



### get_site_url

    mixed app\controllers\DropboxController::get_site_url()





* Visibility: **public**




### clear_cache

    mixed app\controllers\DropboxController::clear_cache()

Clear cahce
/v1/dropbox/clear_cache/{folder_name}
Example: /v1/dropbox/clear_cache/F45 PLAYBOOK/

Removed this whole operation, moved to connect php and it causes host cache to delete everthing

* Visibility: **public**




### dropbox_webhook_clear

    mixed app\controllers\DropboxController::dropbox_webhook_clear()

Calls dropbox clear cache still, but this is used by Dropbox webpack
/v1/dropbox/dropbox_webhook_clear

Removed this whole operation, moved to connect php and it causes host cache to delete everthing

* Visibility: **public**




### dropbox_clear

    mixed app\controllers\DropboxController::dropbox_clear()





* Visibility: **public**




### clear_search_cache

    mixed app\controllers\DropboxController::clear_search_cache()

Removed this whole operation, moved to connect php and it causes host cache to delete everthing



* Visibility: **public**




### get_shareable_link

    mixed app\controllers\DropboxController::get_shareable_link($path)





* Visibility: **public**


#### Arguments
* $path **mixed**



### spider_cache

    mixed app\controllers\DropboxController::spider_cache()





* Visibility: **public**




### sub_folder_create_cache

    mixed app\controllers\DropboxController::sub_folder_create_cache($result)





* Visibility: **public**


#### Arguments
* $result **mixed**



### cache_folder

    mixed app\controllers\DropboxController::cache_folder($arg)





* Visibility: **public**


#### Arguments
* $arg **mixed**


