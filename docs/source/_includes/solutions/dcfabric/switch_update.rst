.. NOTE: This file has been generated automatically, don't manually edit it

switch_update
~~~~~~~~~~~~~

**Description**: Update the details of all the switches in the fabric or a specified single switch 

.. table::

   ================================  ======================================================================
   Parameter                         Description
   ================================  ======================================================================
   *fabric*                          Name of the fabric

                                     Type: ``string``
   *host*                            Management IP address of the switch

                                     Type: ``string``
   *user*                            Login user name to connect to the device

                                     Type: ``string``
   *passwd*                          Login password to connect to the device

                                     Type: ``string``
   *state*                           Device Provisioning State. Its mainly needed to mark the state during workflow execution.

                                     Choose from:

                                     - Provisioned
                                     - Failed
   *protocol*                        The protocol used for REST requests. This applies to REST platforms such as SLX and VDX.

                                     Choose from:

                                     - http
                                     - https

                                     **Default**: http
   ================================  ======================================================================

