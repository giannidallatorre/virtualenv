# First time only
Configure the ambient

Edit EBI-TSI-openrc.sh with your OpenStack references

    $ vim EBI-TSI-openrc.sh

New virtual environment for novavclient
    
    $ virtualenv venv
    $ venv/bin/pip install python-novaclient

# Usage  

Configure the ambient variable

    $ source EBI-TSI-openrc.sh

Activate python Virtualnv

   $ source venv/bin/activate

Use novaclient

    $ nova

Deactivate python Virtualnv

   $ deactivate

