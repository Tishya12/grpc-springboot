# grpc-springboot

Make proto file and compile it using mvn clean compile
then make server and client

In server
1. Extend grpc java stubs
2. get request inputs from client
3. construct response using builder
4. send back data using streamobserver.
