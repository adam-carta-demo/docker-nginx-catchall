A nginx catch-all server that rejects all requests.

## How to use

```sh
docker run \
  --name nginx-catch-all \
  --publish 8080:80 \
  emyller/nginx-400
```

Refer to the [official nginx repository](https://hub.docker.com/_/nginx/) to
learn more about other options.
