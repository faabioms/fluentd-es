fluentd - elasticsearch
==============================

forked from https://github.com/AnalogJ/docker-consul-template-haproxy.
DockerHub Repository: https://registry.hub.docker.com/u/shayashibara/docker-consul-template-haproxy/

## Overview

This repository contains a Dockerfile to create a fluentd image with elasticsearchplugin enabled. 

docker run -d -p 24224:24224 --name fluentd-es mmaquevice/fluentd-es:1.0