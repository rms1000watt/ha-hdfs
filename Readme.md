# HA HDFS

## Introduction

This is the output from [https://github.com/smizy/docker-hadoop-base](https://github.com/smizy/docker-hadoop-base) after running:

```bash
./make_docker_compose_file.sh hdfs      > hdfs.compose.yml
./make_docker_compose_file.sh hdfs yarn > hdfs-yarn.compose.yml
```

## Contents

- [Usage](#usage)
- [Dockerfile](#dockerfile)

## Usage

```bash
docker network create vnet
docker-compose -f hdfs.compose.yml up -d
```

## Dockerfile

The Dockerfile is a copy and paste from: [https://github.com/smizy/docker-hadoop-base/blob/master/Dockerfile](https://github.com/smizy/docker-hadoop-base/blob/master/Dockerfile)
