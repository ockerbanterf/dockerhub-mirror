# DockerHub Mirror

DockerHub Mirror on [GHCR.io](https://ghcr.io) powered by Github Actions and [Crane](https://github.com/google/go-containerregistry/tree/main/cmd/crane)


Copy of [rblaine95/dockerhub-mirror](https://github.com/rblaine95/dockerhub-mirror)

[![Mirror Dockerhub](https://github.com/ockerbanterf/dockerhub-mirror/actions/workflows/mirror.yaml/badge.svg)](https://github.com/ockerbanterf/dockerhub-mirror/actions/workflows/mirror.yaml)

GitHub Actions scheduled to run daily at Midnight UTC to mirror some images to [GHCR.io](https://ghcr.io), bypassing rate limits

Mirrored Images:

* [`node`](https://ghcr.io/ockerbanterf/node)
* [`oblakstudio/redisinsight`](https://ghcr.io/ockerbanterf/oblakstudio/redisinsight)
* [`nginxinc/nginx-unprivileged`](https://ghcr.io/ockerbanterf/nginxinc/nginx-unprivileged)
* [`appsmith/appsmith-ce`](https://ghcr.io/ockerbanterf/appsmith/appsmith-ce)
* [`matomo`](https://ghcr.io/ockerbanterf/matomo)