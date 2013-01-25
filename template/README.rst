{{ app_name }}
========================

Welcome to the documentation for django-{{ app_name }}!

Quick start
-----------

1. Add "{{ app_name }}" to your INSTALLED_APPS setting like this::

      INSTALLED_APPS = (
          ...
          '{{ app_name }}',
      )

2. Include the {{ app_name }} URLconf in your project urls.py like this::

      url(r'^{{ app_name }}/', include('{{ app_name }}.urls')),

3. Start the development server and visit http://127.0.0.1:8000/admin/
to create a record (you'll need the Admin app enabled).

4. Visit http://127.0.0.1:8000/{{ app_name }}/ to start using
{{ app_name }}.

Running the Tests
------------------------------------

You can run the tests with via::

    python setup.py test

or::

    python runtests.py
