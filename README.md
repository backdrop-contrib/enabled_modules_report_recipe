Enabled Modules Report Recipe
=============================

This module is a simple recipe to add an administrative report that 
lists all enabled modules on the site. Useful when reporting bugs 
or seeking support from third parties. The provided report has
an exposed filter to show core modules, contrib modules, or all 
modules.

Simply install and enable this recipe to add this option to your 
admin/reports menu. 


Requirements
------------

Requires [BackdropCMS 1.20](https://github.com/backdrop/backdrop/releases/tag/1.20.0) or greater.

Installation
------------

- This recipe can be found in the Recipes package on the modules 
  page (admin/modules/list).

- Install this like any other module using the official Backdrop CMS 
  instructions at https://backdropcms.org/guide/modules.

- Disabling and uninstalling this module will not delete any of the 
  configuration that this module provides, but will disable the CSS
  files that came with this module. 

Instructions
------------

After enabling the module you will find a new administrative report under
the admin/reports menu - `/admin/reports/enabled-modules`.

Uninstall or Upgrate Options
----------------------------

It is not currently possible to uninstall or upgrade this recipe.
If you no longer wish to keep this functionality, you will need 
to remove the items added by the recipe manually.

Issues
------

- https://github.com/backdrop-contrib/enabled_module_report_recipe/issues

Feedback
--------

We are experimenting with config recipes and welcome your feedback. Please, let us know how this config recipe worked for you and how you think we could improve it for other users in the future. https://github.com/backdrop-contrib/enabled_module_report_recipe/issues/1


Current Maintainers
-------------------

- [Tim Erickson](https://github.com/stpaultim).

Credits
-------

- Sponsored by [Simplo](https://www.simplo.site)

License
-------

This project is GPL v2 software. 
See the LICENSE.txt file in this directory for complete text.
