# Sandvine Cloud packages. Release Notes.

Please, refer to PacketLogic Cloud deployment documentation for details.

## 18.1.2.0-v1. Pre-release. 

### Common features

* Interface types (admin, aux, channels) auto-detection and auto-configuration based on PCI id
* Cloud-init support for data-sources config-drive (preferable) and Openstack metadata service
* Service autodiscovery with zeroconf:
	* LM VNF initial configuration
	* PRE VNF initial configuration
	* Automatic PRE/PIC/PSM licensing 
	* Automatic CIK file installation

### Openstack Heat

* Heat support from Mitaka and onwards
* Control plane and data plane networking based on Neutron objects
* Cinder volumes are required to run PSM and PIC VNFs


### Contrail Heat

* Juniper Contrail support from v3.1 and onwards
* Control plane networking based on Neutron objects, data-plane networking based on Contrail objects
* Scaling In/Out support with Heat AutoscalingGroups
* Cinder volumes are required to run PSM and PIC VNFs


### Open Source MANO

* OSM R3 templates format support
* No EPA requirements for VIM/NFVI

### Rift.ware MANO

* Rift.ware 5.3 templates format support
* No EPA requirements for VIM/NFVI
