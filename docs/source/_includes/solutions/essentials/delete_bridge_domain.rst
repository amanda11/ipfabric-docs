.. NOTE: This file has been generated automatically, don't manually edit it

delete_bridge_domain
~~~~~~~~~~~~~~~~~~~~

**Description**: This deletes the bridge domain. 

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
   **bridge_domain_id**              A single or list of Bridge-domain IDs. <1-4096> on SLX9140,SLX9850 and <1-3566> on SLX9240.

                                     Type: ``string``
   *bridge_domain_service_type*      The bridge domain service type. `p2p` is not supported on SLX9140 and SLX9240 platforms.

                                     Choose from:

                                     - p2mp
                                     - p2p

                                     **Default**: p2mp
   ================================  ======================================================================

