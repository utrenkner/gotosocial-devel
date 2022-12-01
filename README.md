# FreeBSD net-im/gotosocial-devel port
This is a quick&dirty adaptation of the official [gotosocial port](https://github.com/freebsd/freebsd-ports/tree/main/net-im/gotosocial) in the FreeBSD ports tree.

## How to use
Clone this repository to your local ports tree, e.g.
```git clone https://github.com/utrenkner/gotosocial-devel.git /usr/ports/net-im/gotosocial-devel```

You may also need to add this line to ``/path/to/ports-tree/net-im/Makefile``:
```SUBDIR += gotosocial```

Then you can build ``net-im/gotosocial-devel`` the way you usually build your ports (e.g. with poudriere).