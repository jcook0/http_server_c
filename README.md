# http_server_c
Basic and small prototype HTTP server coded in POSIX C. The motivation behind this project to learn more about HTTP, servers, and low level programming in a Unix-based environment. Based on tinyhttpd and Nigel's web server. It is able to serve static files, but not dynamic content.

## Features

- No dependencies
- HTTP/1.0/1.1 support
- Multi-threaded

## Usage
Compile
```
make all
```

Start the server
```
./server <port> <path/to/docroot>
```
## References
https://dev-notes.eu/2018/06/http-server-in-c/

https://notes.eatonphil.com/web-server-basics-http-and-sockets.html


