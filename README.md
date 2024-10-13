# WHAT IS ACTIVE DIRECTORY?
Active directory(AD) is a directory service is a database and it's primary function is identity and access management. Meaning it is used to authenticate and authorize users and computers in a microsoft windows domain.

## ARCHITECTURE OF ACTIVE DIRECTORY 
### Domain Controller(DC):- 
Is any server/ computer on which the active directory domain services are installed and configured.

Every Domain controller has a read and write copy of the AD database. This means that there is no master slave operation going on here. If any CHANGE( creation, deletion, modification, movement) happens on one DC, it reflects in the other DCs- as an administrator, you can make change on any domain controller.

Some DCs take up additional roles and these roles are called "Flexible Single Master Operations"
