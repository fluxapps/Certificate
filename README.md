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
git clone https://github.com/studer-raimann/Certificate.git Certificate
```
Update and activate the plugin in the ILIAS Plugin Administration

Please also install and enable [CertificateCron](https://github.com/studer-raimann/CertificateCron).

<del>
This plugin has some dependencies on other plugins and services. 
Please follow the installation guide of the [documentation](/doc/Documentation.pdf?raw=true).
</del>

## Documentation

An installation and user guide is available in [the doc/Documentation.pdf](/doc/Documentation.pdf?raw=true) file.

### Requirements
* ILIAS 5.4 or ILIAS 6
* PHP >=7.0

## Rebuild & Maintenance

fluxlabs ag, support@fluxlabs.ch

This project needs to be rebuilt before it can be maintained.

Are you interested in a rebuild and would you like to participate?
Take advantage of the crowdfunding opportunity under [discussions](https://github.com/fluxapps/Certificate/discussions/17).

## About fluxlabs plugins

Please also have a look at our other key projects and their [MAINTENANCE](https://github.com/fluxapps/docs/blob/8ce4309b0ac64c039d29204c2d5b06723084c64b/assets/MAINTENANCE.png).

The plugins that require a rebuild and the costs are listed here: [REBUILDS](https://github.com/fluxapps/docs/blob/8ce4309b0ac64c039d29204c2d5b06723084c64b/assets/REBUILDS.png)

