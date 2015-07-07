# xlr-tfs2013-plugin v1.0.7

This plugin offers an interface from XL Release to Team Foundation Server 2013 to create Work Items. The following actions are supported:

#### CreateWorkItem
The CreateWorkItem.py script creates a new Work Item by executing a remote Windows batch wrapper script, CreateWorkItems.bat.  Input parameters are Collection, Project, Type, Title, AssignedTo, and Description; the script returns the number of the Work Item created.  

#### GetWorkItem
The GetWorkItem.py script retrieves a Work Item given its number and collection using the GetWorkItem.bat wrapper script.

#### UpdateWorkItem
The UpdateWorkItem.py script updates a Work Item given its number, collection, and set of update fields and values in the format fieldname1=value1;fieldname2=value2.

The functionality will be enhanced as specific needs materialize.

Notes:  The TFS machine must have Microsoft Visual Studio Team Foundation Server 2013 Update 2 Power Tools installed.  The CreateWorkItem.bat, GetWorkItem.bat, and UpdateWorkItem.bat scripts must be placed in a location on the TFS machine.
