=====================
django-setman Changes
=====================

0.3 (current)
-------------

- ...

0.2
---

+ Add support of app-based settings.
+ Fix converting values to Decimal at ``DecimalSetting`` instances.
+ Return default value for setting even it not stored to database.
+ Lazy process ``validators`` and ``choices`` setting attributes, don't care
  about import ordering.
+ Added labels support for ``choices`` value in ``ChoiceSetting``.
+ Use "Revert" mode in Django admin panel without including ``setman.urls``
  urlpatterns in root URLConf module.
+ Added ``get_config`` helper function.

0.1-beta
--------

- Initial release
