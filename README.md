psycopg2
=======================================

PostgreSQL database adapter for the Python programming language</br></br></br>


<p style="text-align: center;">
  <img src="https://avatars1.githubusercontent.com/u/2947270?s=200&v=4" height="100" />
  <img src=".vscode/equal.png" height="70" />
  <img src=".vscode/python.png" height="100" />
  <img src=".vscode/plus.png" height="70" />
  <img src="https://www.postgresql.org/media/img/about/press/elephant.png" height="100" />
</p>


Installation
------------

Building Psycopg requires a few prerequisites (a C compiler, some development
packages): please check the install_ and the faq_ documents in the ``doc`` dir
or online for the details.

If prerequisites are met, you can install psycopg like any other Python
package, using ``pip`` to download it from PyPI_::

    $ pip install psycopg2

or using ``setup.py`` if you have downloaded the source package locally::

    $ python setup.py build
    $ sudo python setup.py install

You can also obtain a stand-alone package, not requiring a compiler or
external libraries, by installing the `psycopg2-binary`_ package from PyPI::

    $ pip install psycopg2-binary

The binary package is a practical choice for development and testing but in
production it is advised to use the package built from sources.


Contents 
------------

- intro to psycopg2
- postgreSQL.sql
- Join.ipynb: how to join multiple tables
- Trigger.ipynb: create trigger for updating sales log whenever insert or update or delete happens in ppl_cpu_purchases table
- View.ipynb: create view
- config.py
- csv_to_psql.ipynb: read csv file and insert into postgreSQL database
- hstore.ipynb: 
- injection.ipynb
- json.ipynb: read json data and insert into posetgreSQL database
- pattern_matching.ipynb: fizzy


