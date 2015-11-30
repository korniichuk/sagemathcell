.. contents:: Table of contents
   :depth: 2

Full description
================
The `ubuntu:trusty <https://hub.docker.com/_/ubuntu/>`_ Docker image with the SageMathCell.

Docker Hub
==========
The `korniichuk/sagemathcell <https://hub.docker.com/r/korniichuk/sagemathcell/>`_ repo.

Quickstart
==========
The following command starts a container with the SageMathCell listening for HTTP connections on port 8888::

    $ docker run -d -p 8888:8888 korniichuk/sagemathcell
