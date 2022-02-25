# Certificate

The certificate plugin offers an enhanced support for creating and administrating certificates inside ILIAS.

![001](doc/images/certificate_plugin_preview.jpg)

## Features

* Multiple certificate types with different layouts
* Generate pretty PDF layouts with JasperReports, the world’s most popular open source reporting engine
* Custom placeholders in certificates
* Multiple languages
* Certificates (pdf files) are stored in the ILIAS data directory instead of getting generated dynamically
* Revision of files
* Rendering PDF certificates with the integraded PDF Service in ILIAS (>= 4.4) or with JasperReports

## Installation
Start at your ILIAS root directory
```bash
mkdir -p Customizing/global/plugins/Services/UIComponent/UserInterfaceHook
cd Customizing/global/plugins/Services/UIComponent/UserInterfaceHook
git clone https://github.com/fluxapps/Certificate.git Certificate
```
Update and activate the plugin in the ILIAS Plugin Administration

Please also install and enable [CertificateCron](https://github.com/fluxapps/CertificateCron).

<del>
This plugin has some dependencies on other plugins and services. 
Please follow the installation guide of the [documentation](/doc/Documentation.pdf?raw=true).
</del>

## Documentation

An installation and user guide is available in [the doc/Documentation.pdf](/doc/Documentation.pdf?raw=true) file.

# Contributing :purple_heart:
Please ...
1. ... register an account at https://git.fluxlabs.ch
2. ... write us an email: support@fluxlabs.ch
3. ... we give you access to the projects you like to contribute :fire:


# Adjustment suggestions / bug reporting :feet:
Please ...
1. ... register an account at https://git.fluxlabs.ch
2. ... ask us for a sla: support@fluxlabs.ch :kissing_heart:
3. ... we will give you the access with the possibility to read and create issues or to discuss feature requests with us.


[overview]: /doc/Images/certificate_plugin_preview.jpg?raw=true "Preview of certificate plugin"
