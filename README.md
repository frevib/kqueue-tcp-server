# Example TCP server that uses `kqueue(2)` #
This is a bare minimum TCP server that can be used to learn how [`kqueue(2)`][kqueue_manpage_link] works. The code contains comments on what section of code does.


### Run ###
`make`

`./tcpserver_kqueue`

Now connect to the server at port 1815. For instance, using netcat:

`nc -v localhost 1815`

[kqueue_manpage_link]: https://www.freebsd.org/cgi/man.cgi?query=kqueue&apropos=0&sektion=2&manpath=FreeBSD+12.0-RELEASE+and+Ports&arch=default&format=html