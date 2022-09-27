# OD4DAsia Hub Website Buildout

This is a self contained zc.buildout for development and deployment of
OD4DAsia Hub Website.

# Build Instructions

Linux

Ensure that python3 and python development packages are installed, along
with virtualenv.

## Development

    virtualenv -p /usr/bin/python3 python3-plone
    source python3-plone/bin/activate
    pip install zc.buildout plonecli
    git clone https://github.com/Sinar/od4dasia.buildout
    
In checked out od4dasia.buildout directory:

    buildout -v

You can then start the application server with
    
    bin/instance start

The applicaiton server and default empty site will be accessible on
localhost:8080

TODO

## Deployment

TODO

## Acknowledgements

This project was carried out under the Open Data for Development Phase III initiative, with financial support from Global Affairs Canada, the William and Flora Hewlett Foundation, and Canada’s International Development Reesarch Centre. 
