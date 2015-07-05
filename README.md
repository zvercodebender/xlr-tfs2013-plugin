# xlr-tfs2013-plugin v1.0.2

This plugin offers an interface from XL Release to Team Foundation Server 2013 to create Work Items.  The CreateWorkItem.py script executes a remote Windows batch script, CreateWorkItems.bat with Collection, Project, Type, Title, AssignedTo, and Description parameters, returning the number of the Work Item created.

The functionality will be enhanced as specific needs materialize.

Notes:  The TFS machine must have Microsoft Visual Studio Team Foundation Server 2013 Update 2 Power Tools installed.  The CreateWorkItem.bat script must be placed in a location on the TFS machine.
