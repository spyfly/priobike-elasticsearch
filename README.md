# priobike-elasticsearch

## Requirements
1. Increase the maxmium amount of memory-mapped-areas (Linux only) `sudo sysctl -w vm.max_map_count=262144`

## Usage
1. Start the cluster with `docker-compose up` or add `-d` to run in the background
2. Visit `http://localhost:5601` to access Kibana and login with the user `elastic` and the password `elastic_priobike`.