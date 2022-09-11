# ardrive-statistics-board
Dashboard for viewing total storage used by ardrive apps, with user, drive, and file counts.


## Why?

Information on how each user stores and interacts with data can be valuable to ardrive to know, as well as know exactly how much storage the protocol needs. In the event a third party client wants to leverage ArFS stored files, they can reference to the dashboard for higher quality data on the user base. They might need, for example, to know the cost of hosting a certain amount of data for their users.

## How?

the dashboard has two modes. Server, and browser. Server mode allows you to run a database on a server for storing sorted information. Browser mode temporarily stores information every time you run it, with the option to download a CSV file. It also has the option to upload a previously downloaded csv file and read from that, or save it to local storage and it will automatically detect and load it. The benifit of server mode is potentially having a running updated dashboard. Users can point their dashboards settings to that server and recieve the updated information from their. This also reduces queries on the gateway.
