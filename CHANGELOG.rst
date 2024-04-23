^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package gz_utils_vendor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.0 (2024-04-23)
------------------
* Use an alias target for the root library (`#3 <https://github.com/gazebo-release/gz_utils_vendor/issues/3>`_)
  Without this patch, doing `find_package(gz-utils)` (or any vendor
  package) multiple times in a single CMakeLists file fails with an
  error indicating that cmake cannot create the imported target
  because another target with the same name already exists.
* Contributors: Addisu Z. Taddese

0.0.3 (2024-04-10)
------------------
* Add support for the `<pkg>::<pkg>` and `<pkg>::all` targets, fix sourcing of dsv files
* Contributors: Addisu Z. Taddese

0.0.2 (2024-03-28)
------------------
* Require calling find_package on the underlying package (`#2 <https://github.com/gazebo-release/gz_utils_vendor/issues/2>`_)
* Fix linter (`#1 <https://github.com/gazebo-release/gz_utils_vendor/issues/1>`_)
* Initial import
* Contributors: Addisu Z. Taddese
