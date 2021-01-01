##step-1)composer require teambravo/websitepackage


##step-2)
Inside Config/app.php  Register inside providers,

\TeamBravo\WebSitepkg\WebSiteServiceProvider::class,


##step-3)
now Run this Command again

	php artisan vendor:publish --provider="TeamBravo\WebSitepkg\WebSiteServiceProvider" --tag="assets"


##step-4)
 this is middleware , register inside App->Http->Middlweare -> karnel.php

'EmployeeAccessControl'=>\TeamBravo\WebSitepkg\Http\Middleware\EmployeeAccessMiddleware::class


##step-5)php artisan migrate


##step-6)php artisan serve


##step-7)
now hit this link:
localhost:8000/site_admin/

by Mohammad Ruhul Amin
