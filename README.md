# Python Flask app on Azure App Service Web

This is a minimal sample app that demonstrates how to run a Python Flask application on Azure App Service Web (Windows).

This repository can directly be deployed to Azure App Service.

Original documentation: https://github.com/Azure-Samples/app-service-web-python-get-started

> Microsoft have deprecated the Python extensions for App Service on Windows as described in this article in favor of a direct deployment to App Service on Linux.

This will mean that the community will need to provide updates and new versions of the Python site extension. A fork of the Microsoft Python Site Extension can be found here: https://github.com/davidrpk/azure-python-siteextensions. 

## Installing Python Site Extension

1. To run this you'll need to install a Python Web Site Extensions.
2. Then update web.config in this repository to match the install location of python from the site extension. 

Details on how to install python and find the installed location can be found in the included documentation docs/app-service-web-get-started-python.md
