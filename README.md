knocker
=======

Knocker is a simple port knocker written in Python.  To configure it, make a
~/.knocker:

```
[config]
host=my.awesome.server.com
port=22
command=ssh %host
openseq=1234,5678,9123
closeseq=1111,2222,3333
```

Then, just run ```knocker.py```.  You can also run ```knocker.py -h``` to find
out how to configure it purely via the command-line.
