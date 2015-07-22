
Changelog - django-celery-fulldbresult
======================================

0.1.1 - July 21st 2015
----------------------

- The order of choice fields are now fixed (sorted) so that migrations are not
  re-generated depending on the version of Python or Django.

0.1.0 - June 1st 2015
---------------------

- First release!
- Can store the parameters and enough meta in the task result to retry the task
- Integration with Django Admin: possible to retry a task from a task result
  (admin action)