# baobab-nox
Tool to ascertain folder sizes from the command line.
With human-readable output.
With proper sorting from biggest to smallest.

## Sample output

```
$ baobab-nox /etc | head -20

******************************     2,2G  log
                        ******     517M  lib
                             *     116M  cache
                                   8,2M  backups
                                   2,9M  spool
                                    56K  tmp
                                    40K  games
                                    20K  www
                                    20K  mail
                                   4,0K  snap
                                   4,0K  opt
                                   4,0K  metrics
                                   4,0K  local
                                   4,0K  crash
                                      0  run
                                      0  lock
```
