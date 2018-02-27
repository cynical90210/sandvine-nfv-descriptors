# Sandvine Cloud packages

Sandvine provides reference templates for cloud platforms, including OSM, Openstack Heat and Juniper Contrail. This repository is the collection of structured and tested templates ready for onboarding to NFV Orchestrator. 

## Before you start

Please read Sandvine PacketLogic Cloud architecture documentation before proceeding to deployment in Cloud platform.

## Platforms in scope

### OSM packages

OSM defines a package format and provides on-boarding of these packages for NS and VNF.
Currently the following packages are provided for OSM on-boarding
* PRE VNF package
* PSM VNF package
* PIC VNF package
* LM VNF package (includes Elements and Licence Manager)
* Standard networks NS package
* Channel networks NS package
* PacketLogic example NS package

### Openstack Heat packages

OpenStack Heat does not define a package format, but we have organised the HOTs (the Heat templates) required for PacketLogic deployment in and identical structure as for the OSM packages (and hopefully the same structure for the ETSI packages). The Heat packages consists of the Heat template files that make up the "descriptors" for the particular function represented by the package.
Currently the following packages are provided for Heat on-boarding
* PRE VNF package
* PSM VNF package
* PIC VNF package
* LM VNF package (includes Elements and Licence Manager)
* Standard networks NS package
* Channel networks NS package
* PacketLogic example NS package

### Juniper Contrail Heat packages

Juniper Contrail package follows same format as Openstack Heat package.
Currently the following packages are provided for Heat on-boarding
* PRE VNF package
* PSM VNF package
* PIC VNF package
* LM VNF package (includes Elements and Licence Manager)
* Standard networks NS package
* Channel networks NS package (Contrail specific objects)
* PRE VNF scaling NS package
* PacketLogic example NS package

## Deployment

Detailed deployment process for each Cloud platform in scope described in official Sandvine PacketLogic Cloud deployment guide. Please contact your Sandvine Sales representative to get required documentation.

Sandvine supplies PacketLogic products images for Cloud in QCOW2 and VMDK format. Please contact your Sandvine Sales representative to get PacketLogic products images.

For the list of supported features, please, refer to [RELEASE_NOTES.md](RELEASE_NOTES.md)

## Versioning

Sandvine PacketLogic Cloud packages versioning is aligned with PacketLogic products firmware lifecycle.

Each branch in current repository corresponds to PacketLogic firmware version in 4 digits format. Make sure that you uploaded correct firmware version to your Cloud platform. 
Cloud packages versions inside branch are based on git tags. For the versions available, see the [tags on this repository](https://github.com/sandvine/sandvine-nfv-descriptors/tags). 

Following naming conventions applies to PacketLogic Cloud packages:
```
0-18.1.1.7
```
Where:
* 18.1.1.7 is PacketLogic products firmware version
* 0- is Cloud package version

## Authors

See  the list of [contributors](https://github.com/sandvine/sandvine-nfv-descriptors/graphs/contributors) who participated in this project.

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE.md](LICENSE.md) file for details
