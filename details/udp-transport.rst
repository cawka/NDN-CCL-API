.. _UdpTransport:

UdpTransport Class
------------------

:[C++]:
    Namespace: ``ndn``

UdpTransport Constructor
++++++++++++++++++++++++

Create a UDP-based transport with the given host and port.

:[C++]:

    .. code-block:: c++

        UdpTransport(
        
            const char *host
            [, unsigned short port]
        
        );

:Parameters:

    - `host`
        The host for the connection.

    - `port`
        (optional) The port number for the connection. If omitted, use 6363.

