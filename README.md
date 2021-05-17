# Multithreaded Server
Simple multithreaded server-client database program where the client can query data from the server. Server detaches one thread per connection to handle all client-side interactions. Client can request fake employee data by sending a `GETSALARY <ID>` request. Server responds back with employee's ID, name, and salary if it exists. If not, server sends an error message.

### Getting Started
`$ make` - Compiles the client and server code

`$ ./server port` - Starts server on identified port and listens for connections

`$ ./client host_name port` - Start client session and connect to server
