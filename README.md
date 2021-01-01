##step-1)
##composer require teambravo/websitepackage

##step-2)
##	\TeamBravo\WebSitepkg\WebSiteServiceProvider::class,
##step-3)
##	php artisan vendor:publish --provider="TeamBravo\WebSitepkg\WebSiteServiceProvider" --tag="assets"

##step-4)
 ##'EmployeeAccessControl'=>\TeamBravo\WebSitepkg\Http\Middleware\EmployeeAccessMiddleware::class
##step-5)
##php artisan migrate
##step-6)
##php artisan serve
##step-7)localhost:8000/site_admin/
