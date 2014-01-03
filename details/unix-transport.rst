.. _UnixTransport:

UnixTransport Class
------------------

:[C++]:
    Namespace: ``ndn``

UnixTransport Constructor
++++++++++++++++++++++++

Create a UNIX socket-based (stream socket) transport with the given
name of the socket.

:[C++]:

    .. code-block:: c++

        UnixTransport(
        
            [const std::string &unixSocket]
        
        );

:Parameters:

    - `unixSocket`
        (optional) UNIX socket path. If omitted, use ``/tmp/.ndn.sock``.

