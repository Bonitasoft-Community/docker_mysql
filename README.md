This image is based on MySQL [5.5](https://github.com/docker-library/mysql/blob/8ed790ab199eeef0f36ef0547ae28e5654cbef0d/5.5/Dockerfile) from the [MySQL Official Repo](https://registry.hub.docker.com/_/mysql/).

The only difference is that we increase the parameter max_allowed_packet (set by default to 1M) to 16M.
