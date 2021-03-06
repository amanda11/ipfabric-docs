.. NOTE: This file has been generated automatically, don't manually edit it

configure_vrrpe_gw
~~~~~~~~~~~~~~~~~~

**Description**: This create VLAN, VE interface on specified GWs and configure VRRPe on VE interfaces. 

.. table::

   ================================  ======================================================================
   Parameter                         Description
   ================================  ======================================================================
   **mgmt_ip**                       The management IP address of the target device.

                                     Type: ``string``
   *username*                        The login user name to connect to the device.

                                     Type: ``string``

                                     **Default**: admin
   *password*                        The login password to connect to the device.

                                     Type: ``string``

                                     **Default**: password
   *rbridge_id*                      This is a single Rbridge or a list of Rbridges separated by comma that needs VE/VRRPe creation.

                                     Type: ``array``
   **vlan_id**                       A single VLAN ID. VDX range is from 1 through 8191 and 1 through 4090 for SLX.

                                     Type: ``string``
   *vlan_desc*                       The VLAN description without any space.

                                     Type: ``string``
   *ve_ip*                           A single or a list of IPv4/IPv6 addresses to be configured on the VE. IPv4/subnet-length or IPv6/prefix-length, for example 10.0.0.10/22, 30.0.0.10/22.

                                     Type: ``array``
   *vrid*                            The virtual group ID. Range for VDX & SLX is from 1 through 255.

                                     Type: ``string``
   **virtual_ip**                    The VRRPe virtual IP address without the netmask.

                                     Type: ``string``
   *vrf_name*                        The VRF name, for example vrf32 or 32.

                                     Type: ``string``
   *afi*                             The IP address type.

                                     Choose from:

                                     - ipv4
                                     - ipv6

                                     **Default**: ipv4
   *intf_type*                       The interface type, VDX & SLX supports only `ve`.

                                     Choose from:

                                     - ve

                                     **Default**: ve
   *intf_name*                       The VE ID. This is mandatory args for SLX. VE range for SLX is from 1 through 4096 and 1 through 8191 for VDX. `intf_name` will be infered as `vlan_id` if not passed.

                                     Type: ``string``
   *display_show_results*            This enable/disable output display of show commands executed on the devices.

                                     Type: ``boolean``
   ================================  ======================================================================

