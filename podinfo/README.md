# Microservice 1

## Overview

This folder contains the resources for deploying Microservice 1 using Flux and Helm.

## Substitutable Values

The following values can be substituted in the HelmRelease:

- `REPLICA_COUNT`: The number of replicas for the deployment. Default: `2`.
- `IMAGE_REPOSITORY`: The Docker repository for the image. Default: `ghcr.io/stefanprodan/podinfo`.
- `IMAGE_TAG`: The tag of the Docker image. Default: `6.3.5`.
