# Description
This project runs a development Elastic Search cluster on Docker with 3 nodes (1 leader and 2 followers), and a Kibana interface to interact with the cluster.

The ES nodes are available on [localhost:9200](http://localhost:9200) and the Kibana interface on [localhost:5601](http://localhost:5601).

# Running
Make sure you have docker installed on your machine

Then upgrade your max memory mapping
```bash
# On Linux
sudo sysctl -w vm.max_map_count=262144
```

After that simply run the docker-compose file
```bash
docker-compose up
```
