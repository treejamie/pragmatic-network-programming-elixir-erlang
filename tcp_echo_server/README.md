# TCPEchoServer

Start the server with `mix run --no-halt`.

Use netcat to send data to the echo server.

```
echo -en "Hello\nworld\n" | nc localhost 4000
```
It doesn't do much other than echo stuff back because it's an echo server.

