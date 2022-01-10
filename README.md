# clasp_by_remotecontainer
Environment for using clasp with Remote Container

## configuration
* [clasp](https://github.com/google/clasp)
* [Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## usage
(The part that opens in the container is omitted.)

1. login to clasp
```
clasp login --no-localhost
```

2. create a project
```
clasp create your_project_name --rootDir ./src
```
if ```.clasp.json``` is created under ```/work/src/```, move under ```/work/```.

3. change time zone
change ```appsscript.json```'s time zone.

