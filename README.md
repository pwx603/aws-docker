## aws-docker
Simple wrapper to inject aws credentials into docker container from local aws profile.

If script is not executable run:
```
$ chmod +x
```

soft link script to /usr/bin so it can be invoked from any path (MAC OSX)
```
$ ln -s /absolute/path/aws-docker /usr/local/bin/
```

E.g.
```
aws-docker run -it hello-world
```