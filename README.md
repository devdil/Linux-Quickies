# Linux-Quickies
A collection of linux commands that will help you debug stuff
```bash
$ sudo lsof -i -P -n | grep LISTEN # print sockets on listen mode
$ sudo strings /proc/12642/environ # print environment variables of a process
$ sudo netstat -tunapl # tuna please
```

## Profiling
```bash
$ python3 -m cProfile {filename}
$ pycallgraph graphviz --output-format=dot --output-file=pycallgraph.dot -- {pythonfilename} # requires graphviz to be installed

```

