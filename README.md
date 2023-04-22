# Naikari Build Infrastructure
This repository contains Dockerfiles for all of the [Naikari Project](https://github.com/naikari/naikari)'s CI and CD build images, and Github Actions workflows.

### Overview:
- `naikari-linux-latest` (Used for CI and testing.)
- `naikari-linux-lts` (Used for release builds. Oldest targeted glibc platform)
- `naikari-macos` (Used to cross compile for macOS.)
- `naikari-release` (Used for packaging releases)
- `naikari-windows` (Used to cross compile for Windows.)


Publicly available images are available from the Github Package Registry [HERE](https://github.com/orgs/naikari/packages?repo_name=naikari-infrastructure).
These images are used by the [Naikari Project](https://github.com/naikari/naikari) in CI and CD workflows to provide standard build environments, and limit 'moving parts'.


### Build Status:
[![Naikari Infrastructure Testing](https://github.com/naikari/naikari-infrastructure/actions/workflows/test_docker.yml/badge.svg)](https://github.com/naikari/naikari-infrastructure/actions/workflows/test_docker.yml) \
[![Naikari Infrastructure Deployment](https://github.com/naikari/naikari-infrastructure/actions/workflows/deploy_docker.yml/badge.svg)](https://github.com/naikari/naikari-infrastructure/actions/workflows/deploy_docker.yml)
