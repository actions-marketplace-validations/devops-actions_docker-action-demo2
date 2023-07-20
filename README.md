# docker-action-demo2


Example of a docker based action that can be used from the marketplace without having an action.yml file. 
The file was needed for releasing it into the marketplace, and got removed afterwards.

The runner does not care about the marketplace, and just looks at the action repo for `action.yml`, `action.yaml`, `Dockerfile`, or `dockerfile` in the root of the repository or folder that you are executing.
