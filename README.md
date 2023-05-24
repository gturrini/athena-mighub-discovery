Query example creates a view of ALL hosts analysed (with hardware details), with a list of ALL identified processes (including system processes) and ALL identified INBOUND and/or OUTBOUND connections (both with protocol, source, destination and ports).
for example it could be used to filter::

* at host level to identify ALL running processes that could represent one or more application
* at process level to identify all instances of one particular application
* at the process/network level to identify applications sitting behind a load balancer or a proxy
* ...



