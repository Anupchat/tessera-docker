Tessera docker container
==============

A Docker container running the [tessera](https://github.com/urbanairship/tessera).

Prerequisite is to setup and install [docker](http://docker.com) for this container to work.

## Start the container

```console
$ sudo docker run -d -p 5000:5000 anupchat/tessera-docker --name tessera
```
Browse to [http://localhost:5000](http://localhost:5000) and you should see the tessera UI.

## Update Graphite connection

Browse to [http://localhost:5000/preferences/](http://localhost:5000/preferences/)

Update the graphite URL and you are good to create your dashboards here which connects to your graphite instance.
