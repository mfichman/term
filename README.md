Terminal session manager.  Keeps track of all your screen sessions, and reopens them.

Create a new session:

```
$ term session bob
```

Connect to a host:

```
$ term lumberjack@montypython.net
```

Show active screens:

```
$ term show
bob, 1828828181.22, lumberjack@montypython.net
```

Restore disconnected screens:

```
$ term restore
```

Currently works on OS X with Terminal.app.
