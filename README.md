djangocms-angular-compendium
============================

A collection of templates for various DjangoCMS plugins to be used for overriding when the frontend
is running together with the AngularJS framework.

Currently these templates are overridden:

* ``cmsplugin_filer_image/image.html``: Replace tag ``<img src="...">`` against ``<img ng-src="...">``.
  This is required by the AngularJS ngSrc directive: http://docs.angularjs.org/api/ng.directive:ngSrc
* ``cms/plugins/bootstrap/carousel.html`` and ``carousel-slide.html``: Replace the Carousel HTML
  code with a variant running with AngularJS: http://angular-ui.github.io/bootstrap/#/carousel

License
-------
Released under the terms of MIT License.

Copyright (C) 2013, Jacob Rief <jacob.rief@gmail.com>
