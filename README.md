# docker-serf
Docker image based on Alpine, with [Serf](https://www.serf.io) installed. 

In order to run the agent, launch the container with the following command:
```
docker run -d -p 7946:7946 -p 7373:7373 ivaquero/serf:0.8.0 agent -rpc-addr=0.0.0.0:7373
```

For more information, read the [Serf documentation](https://www.serf.io/docs/index.html).
