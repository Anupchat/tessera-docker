Tessera docker container
==============

A Docker container running the tessera (https://github.com/urbanairship/tessera).
Prequisite is to setup and install docker (http://docker.com)

```console
$ sudo docker run -d -p 5000:5000 anupchat/tessera-docker --name tessera
```
Browse to
http://localhost:5000/preferences/

Update the graphite URL and you are good to create your dashboards here which connects to your graphite instance.
