# node-red-with-dashboards

Deploy a [Node-RED](https://nodered.org/) instance with dashboards (`node-red-dashboard`) out-of-the-box.

## How to start it

Run `docker-compose up` and head to [http://localhost:1880](http://localhost:1880]). The dashboards are at [http://localhost:1880/ui](http://localhost:1880/ui).


## Data directory

The data directory is in the path `/data` inside a container, so if you want to save your work, `docker cp` it or map it to a host folder.
