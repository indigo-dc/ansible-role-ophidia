docker-ophidia-terminal
=======================

Dockerfile to run the ophidia-terminal

The ophidia-terminal is the client tool to run the Ophidia Bid Data
framework


Introduction
------------

The image is built from the ansible-role of the following github
repository:
* https://github.com/indigo-dc/ansible-role-ophidia-terminal

It builds the ophidia-terminal application from:
* https://github.com/indigo-dc/ophidia-terminal

Information on running ophidia-terminal is in this repository and at
* http://ophidia.cmcc.it/documentation

Build docker image
------------------

The image can be built with
```
docker build -t ophidia-terminal .
```

Or you can pull it from the dockerhub:
```
$ docker pull indigodatacloudapps/ophidia-terminal
```

Run docker-ophidia-terminal
---------------------------

To run the container either:

```
docker run -it ophidia-terminal oph_term
```

```
$ docker run -it ophidia-terminal /bin/bash
# oph_term 


Oph_Term - the Ophidia shell, version 0.9.0
Copyright (C) 2012-2016 CMCC Foundation - www.cmcc.it
This program comes with ABSOLUTELY NO WARRANTY; for details type `warranty'.
This is free software, and you are welcome to redistribute it
under certain conditions; type `conditions' for details.

Welcome to Oph_Term !

Use the power of the Ophidia framework right from your terminal.
If you are going to use Oph_Term for the first time and need something
to get you started, just try entering "help"

[OPH_TERM] >> 
```

License
-------

Apache v2

Author Information
------------------

Mario David: mariojmdavid@gmail.com
LIP and Indigo-DataCloud project

Acknowledgments
---------------

* Ophidia CMCC group
* Further information can be found at: http://ophidia.cmcc.it/documentation.
