# gitlab-octocli

This repository contains GitLab-compatible Docker images for:

- The [_legacy_ Octopus CLI](https://github.com/OctopusDeploy/OctopusCLI) : `octo`
- The new [_vNext_ Octopus CLI](https://github.com/OctopusDeploy/cli): `octopus`

Each image is built from the `alpine` platform.

**Please Consider this repository provided as is.  If there are any issues please do not contact support.**

## Tags

The version tag corresponds to the version of the Octopus CLI installed on the image. 
A new image will be built each time a new version of Octopus CLI is created.  

The tags are as follows:
- Latest
- [Version] For example `1.3.0`
- Latest-[architecture] For example `latest-alpine`
- [Version]-[architecture] For example `1.3.0-alpine`

### gitlab-octocli Tags

Tag | Dockerfile
---------| ---------------
alpine| [Dockerfile](https://github.com/OctopusDeployLabs/gitlab-octocli/blob/main/octopus-cli/alpine/dockerfile)

You can retrieve a list of all available tags for octopuslabs/gitlab-octopus-cli at https://hub.docker.com/v2/repositories/octopuslabs/gitlab-octopus-cli/tags.

### gitlab-octopuscli Tags

Tag | Dockerfile
---------| ---------------
alpine| [Dockerfile](https://github.com/OctopusDeployLabs/gitlab-octocli/blob/main/octopus-cli/alpine/dockerfile)

You can retrieve a list of all available tags for octopuslabs/gitlab-octopus-cli at https://hub.docker.com/v2/repositories/octopuslabs/gitlab-octopus-cli/tags.

