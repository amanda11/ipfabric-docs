.. NOTE: This file has been generated automatically, don't manually edit it

remove_switchport_trunk_allowed_vlan
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Description**: This removes the switch port trunk allowed VLAN from an interface for SLX/NOS or remove a tagged port from a VLAN or list of VLANs for MLX. 

.. table::

   ================================  ======================================================================
   Parameter                         Description
   ================================  ======================================================================
   **mgmt_ip**                       The management IP address of the target device.

                                     Type: ``string``
   *username*                        The login user name to connect to the device.

                                     Type: ``string``
   *password*                        The login password to connect to the device.

                                     Type: ``string``
   **intf_type**                     The interface type.

                                     Choose from:

                                     - ethernet
                                     - tengigabitethernet
                                     - gigabitethernet
                                     - fortygigabitethernet
                                     - hundredgigabitethernet
                                     - port_channel

                                     **Default**: tengigabitethernet
   **intf_name**                     The interface name, for VDX in 3-tuple format (24/0/1), SLX/MLX in 2-tuple format (24/1) or Port-channel number <1-6144>, for MLX <1-256>.

                                     Type: ``string``
   **vlan_id**                       For 802.1Q VLANs, single or range of VLANs, for example, 5 or 4-7 or 4,6,9-11 or all; ID must be below 4096. For service or transport VFs, single ID, range can be from 4096 through 8191. For MLX vlan range <1-4090>.

                                     Type: ``string``
   *c_tag*                           This specifies an incoming C-TAG or range of C-TAGs for service or transport VLANs in a Virtual Fabrics context. For service VF only single ID is allowed, for Transport VFs a range of IDs, for example, 100-200, or 10,20,100-200. it is no-op for MLX.

                                     Type: ``string``
   ================================  ======================================================================

