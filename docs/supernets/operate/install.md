---
id: supernets-install
title: Installation
sidebar_label: Install binaries
description: "Steps on how to install the Supernet binaries."
keywords:
  - docs
  - polygon
  - edge
  - install
  - installation
---

This document highlights the different methods available to install the Polygon Supernets source.

We recommend that you refer to the installation method that is most applicable to you. Our suggestion is to use the pre-built releases and verify the provided checksums.

:::info Latest release: v0.8.0

**The latest stable release is [v0.8.0](https://github.com/0xPolygon/polygon-edge/releases/tag/v0.8.0), which is the first stable release.**

:::

---

## Pre-built releases

To access the pre-built releases, visit the [GitHub Releases](https://github.com/0xPolygon/polygon-edge/releases) page for a list of releases. Polygon Edge provides cross-compiled AMD64/ARM64 binaries for Darwin and Linux.

## Docker image

To use Docker, you will need to have it installed on your system. If you haven't already installed Docker, you can follow the instructions on the
[official Docker website](https://www.docker.com/) for your operating system.

If you prefer to use Docker, you can access the official Docker images hosted under the [hub.docker.com registry](https://hub.docker.com/r/0xpolygon/polygon-edge) using the following command:

  ```bash
  docker pull 0xpolygon/polygon-edge:latest
  ```

## Build from source

To build from source, make sure that you have Go >=1.18 installed and properly configured before using go install. The stable branch is the branch of the latest release. Use the following commands to build from source:

  ```bash
  git clone https://github.com/0xPolygon/polygon-edge.git
  cd polygon-edge/
  go build -o polygon-edge .
  ```
