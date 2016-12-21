# collectd docker image


Run collectd with the default configuration:

```
docker run --privileged -dti --restart=always --uts="host" --name collectd -v /proc:/mnt/proc:ro -v /:/hostfs:ro h1kkan/collectd-docker:5.7
```
