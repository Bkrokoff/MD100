# SERVICES HIERARCHY

![[servicesHierarchy.png]]

What service will start if you restart this computer?

Service 1 cannot start because it is dependent on service 3, which is disabled on startup

Service 2 will start because it is set to automatic, 6 will start because service 2 will start

Service 3 will not start because it is disabled

Service 4 will not start because it is disabled

Service 5 will start because it is automatic and not dependent on any other services

Service 6 will start since service 2 is dependent on it starting and service 2 is set to automatic

DISABLED
AUTOMATIC
MANUAL