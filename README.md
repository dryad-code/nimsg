nimsg -- Network Instant MeSsanGer
==================================
`nimsg` is a compact, server-based chat program written in Python 2.7.3.  
`nimsg` has a curses interface, which looks pretty on terminals.  
This package assumes that you are working on a Unix-like system with `make` installed.  `nimsg` is able to run on other systems such as Windows, but only if you have Python installed and even then you might need a little tweaking.  
To install `nimsg`, `cd` to the directory where you downloaded `nimsg`, and type in at a command line:  
`make all`  
`make install`  
Note that you must run `make install` __as root__.  If you don't, then `nimsg` won't install.  
To run the `nimsg` client, type in at a command line:  
`nimsg server_ip`  
To run the `nimsgd` server, type in at a command line:  
`nimsgd &`  
Enjoy!
