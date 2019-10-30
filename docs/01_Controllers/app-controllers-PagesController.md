app\controllers\PagesController
===============

This controller is used for serving static pages by name, which are located in the `/views/pages`
folder.

A Lithium application's default routing provides for automatically routing and rendering
static pages using this controller. The default route (`/`) will render the `home` template, as
specified in the `view()` action.

Additionally, any other static templates in `/views/pages` can be called by name in the URL. For
example, browsing to `/pages/about` will render `/views/pages/about.html.php`, if it exists.

Templates can be nested within directories as well, which will automatically be accounted for.
For example, browsing to `/pages/about/company` will render
`/views/pages/about/company.html.php`.


* Class name: PagesController
* Namespace: app\controllers
* Parent class: lithium\action\Controller







Methods
-------


### _init

    mixed app\controllers\PagesController::_init()





* Visibility: **public**




### playbookLogin

    mixed app\controllers\PagesController::playbookLogin()





* Visibility: **public**




### view

    mixed app\controllers\PagesController::view()





* Visibility: **public**




### renew_pdf

    mixed app\controllers\PagesController::renew_pdf()





* Visibility: **public**




### locationpreapprovals

    mixed app\controllers\PagesController::locationpreapprovals()





* Visibility: **public**




### location_pdf

    mixed app\controllers\PagesController::location_pdf()





* Visibility: **public**




### generatePDF

    mixed app\controllers\PagesController::generatePDF()





* Visibility: **public**



