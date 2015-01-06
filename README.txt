INTRODUCTION
------------
Swagger is a library for documenting RESTful services provided by wordnik.

Documentation can be found at https://github.com/wordnik/swagger-core/wiki

This module will generate swagger-parsable json documentation for each service.
If provided with the swagger-ui library, it will also provide a page to display
the data via swagger-ui.


REQUIREMENTS
------------
This module requires the following modules:
 * Services (https://www.drupal.org/project/services)


INSTALLATION
------------
 * Install as you would normally install a contributed Drupal module. See:
   https://drupal.org/documentation/install/modules-themes/modules-7
   for further information.

 * (optional) Install the Swagger UI library:

   - Download the latest release from
     https://github.com/swagger-api/swagger-ui/releases.
   - Create a new folder in sites/all/libraries named "swagger".
   - From the latest release, copy the contents of the "dist" directory into
     the new "swagger" folder.
   - Flush caches.


CONFIGURATION
-------------
 * Configure user permissions in Administration > People > Permissions:

   - View Swagger UI and JSON

     Controls access to the JSON created by this module, and the pages used to
     display the Swagger UI. If the JSON is going to be consumed externally, you
     will likely need to grant this permission to the anonymous user.


MAINTAINERS
-----------
Current maintainers:
 * Mark Millford (mindgrub) - https://www.drupal.org/user/1674598
