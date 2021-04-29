=====
Usage
=====

To use Multiple Select Widget in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'multiple_select_widget.apps.MultipleSelectWidgetConfig',
        ...
    )

Add Multiple Select Widget's URL patterns:

.. code-block:: python

    from multiple_select_widget import urls as multiple_select_widget_urls


    urlpatterns = [
        ...
        url(r'^', include(multiple_select_widget_urls)),
        ...
    ]
