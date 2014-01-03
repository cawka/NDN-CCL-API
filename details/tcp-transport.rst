.. _TcpTransport:

TcpTransport Class
------------------

:[C++]:
    Namespace: ``ndn``

TcpTransport Constructor
++++++++++++++++++++++++

Create a TCP/IP-based transport with the given host and port.

:[C++]:

    .. code-block:: c++

        TcpTransport(
        
            const char *host
            [, unsigned short port]
            
        );

:[JavaScript]:

    .. code-block:: javascript

        var TcpTransport = function TcpTransport(
            {
                [ host:host, ]
                [ port:port, ]
            }
        );

:Parameters:

    - `host`
        The host for the connection.

    - `port`
        (optional) The port number for the connection. If omitted, use 6363.


