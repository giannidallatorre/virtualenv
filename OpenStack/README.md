# First time only
Configure the ambient

Edit EBI-TSI-openrc.sh with your OpenStack references

    $vim EBI-TSI-openrc.sh

New virtual environment for novavclient
    
    $ virtualenv venv
    $ env/bin/pip install python-novaclient

# Usage
Configure the ambient variable

    $ source EBI-TSI-openrc.sh

Activate python Virtualnv

   $ source env/bin/activate

Use novaclient

    $ nova

Deactivate python Virtualnv

   $ deactivate

