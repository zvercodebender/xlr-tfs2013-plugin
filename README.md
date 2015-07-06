# xlr-tfs2013-plugin v1.0.7

This plugin offers an interface from XL Release to Team Foundation Server 2013 to create Work Items.  The CreateWorkItem.py script executes a remote Windows batch script, CreateWorkItems.bat with Collection, Project, Type, Title, AssignedTo, and Description parameters, returning the number of the Work Item created.  The GetWorkItem.py script retrieves a Work Item given its number and collection, while the UpdateWorkItem.py script udpates a Work Item given a set of update fields and values.

The functionality will be enhanced as specific needs materialize.

Notes:  The TFS machine must have Microsoft Visual Studio Team Foundation Server 2013 Update 2 Power Tools installed.  The CreateWorkItem.bat, GetWorkItem.bat, and UpdateWorkItem.bat scripts must be placed in a location on the TFS machine.
