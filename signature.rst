.. _Signature:

Signature Class
===============

A Signature is an abstract base class providing methods to work with the signature information in a Data packet. You must create an object of a subclass, for example Sha256WithRsaSignature.

:[C++]:
    Namespace: ``ndn``

:[Python]:
    Module: ``pyndn``

SignatureSha256WithRsa Class
----------------------------

A SignatureSha256WithRsa extends Signature and holds the signature bits and other info representing a SHA256-with-RSA signature in a data packet.

:[C++]:
    Namespace: ``ndn``

:[Python]:
    Module: ``pyndn``

SignatureSha256WithRsa Constructor
----------------------------------

Create a new Sha256WithRsaSignature object.

:[C++]:

.. code-block:: c++

    Sha256WithRsaSignature();

