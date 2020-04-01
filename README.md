MeshAgent
=========

Install the agent for a Mesh Central server.

Requirements
------------

System must have connectivity to a running Mesh Central server.

Role Variables
--------------

meshServer: meshcentral
MeshCentral server to register against.
Default: meshcentral

meshKey: ""
Group key to register.
Default: "" (null string)

meshProtocol: https
Protocol to use communication with meshServer. (do not include ://)
Default: https
Options: http, https

meshvalidateCert: no
Require valid SSL/TLS certificate (meshProtocol == https).
Default: no
Options: no, yes


License
-------

Gnu GPL

Author Information
------------------

Mark Coccimiglio <mark@coccimiglio.net> 

