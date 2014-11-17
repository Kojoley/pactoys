# Repman

Repman is a Pacman repository manager. You can use it for managing additional repositories in `/etc/pacman.d/repman.conf` using the command line. You can install it with:

```
gem install repman
```

## Example


```
repman --add name --url http://example.com
repman --remove name
repman --list
```

## License and copyright

Copyright (c) 2014 Renato Silva and others.
Licensed under the terms of the GNU GPL version 2 or later.
