Chat App

Accomplished:
Includes a web client, server, and database
Messages contain only text
Messages persist if the server is shut down and restarted
Messages display in the order they are sent
Messages must be accepted by the client and sent to the server via an asynchronous call
The server must store messages in a database for later retrieval

Yet to do:
The messages are not timestamped.

Extra:
Created delete functions for each message, but haven't implemented it on the front end.

----------------------------------------------
IMPLEMENTED(5/31/2017)

- Messages are timestamped and ordered by ascending timestamps. Clicking on the message body displays the timestamp.
- Created a 'clear conversation' button to delete all messages.
- Some other minor changes.