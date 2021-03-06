.. NOTE: This file has been generated automatically, don't manually edit it

remove_acl
~~~~~~~~~~

**Description**: This removes an ACL from physical port, port channel, VE or mgmt interface. 

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

                                     - gigabitethernet
                                     - tengigabitethernet
                                     - fortygigabitethernet
                                     - hundredgigabitethernet
                                     - port_channel
                                     - ve
                                     - loopback
                                     - ethernet
                                     - management
                                     - vlan

                                     **Default**: tengigabitethernet
   **intf_name**                     The interface names, can be comma separated physical ports, port channel numbers or VEs. Examples are 224/0/1, 224/0/2 or 7, 8, 9.

                                     Type: ``array``
   *rbridge_id*                      The RBridge ID of the VDX switch under which VE will be configured, only needed for VDX device.  Only applicable to NOS devices.

                                     Type: ``string``
   **acl_name**                      The ACL name.

                                     Type: ``string``
   **acl_direction**                 The ACL direction.

                                     Choose from:

                                     - in
                                     - out

                                     **Default**: in
   ================================  ======================================================================

