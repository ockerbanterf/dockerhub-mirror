# DockerHub Mirror

DockerHub Mirror on [GHCR.io](https://ghcr.io) powered by Github Actions and [Crane](https://github.com/google/go-containerregistry/tree/main/cmd/crane)


Copy of [rblaine95/dockerhub-mirror](https://github.com/rblaine95/dockerhub-mirror)

[![GitHub Workflow Status (branch)][github-actions-badge]][github-actions-link]

GitHub Actions scheduled to run daily at Midnight UTC to mirror some images to [GHCR.io](https://ghcr.io), bypassing rate limits

Mirrored Images:

* [`node`](https://ghcr.io/ockerbanterf/node)
* [`oblakstudio/redisinsight`](https://ghcr.io/ockerbanterf/oblakstudio/redisinsight)
* [`nginxinc/nginx-unprivileged`](https://ghcr.io/ockerbanterf/nginxinc/nginx-unprivileged)

[github-actions-badge]: https://img.shields.io/github/actions/workflow/status/ockerbanterf/dockerhub-mirror/mirror.yml?branch=master "Github Workflow Status (master)"
[github-actions-link]: https://github.com/ockerbanterf/dockerhub-mirror/actions?query=workflow%3AMirror%20Dockerhub
