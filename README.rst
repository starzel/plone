Minimal Plone demo for debugging
================================

Installation
------------

.. code-block:: bash

    git clone https://github.com/starzel/plone
    cd plone

    # Create and enable virtualenv:
    python3 -m venv .
    ./bin/activate

    # install
    pip install -r requirements.txt
    buildout

Run application
---------------

.. code-block:: bash

    # Start it:
    ./bin/instance fg

Open in http://localhost:8080
