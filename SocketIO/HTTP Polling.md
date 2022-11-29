# Notion
- Client request to the server after server is going to send response to client 
-  If response server is empty, client request to server until response not empty
# Drawback
- Client will request to the server until the server send response with information not empty, so resources o the server get wasted
- Client doesn't know ahead of time whether new data is available