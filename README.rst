.. _README:

ELK on docker
===============

This is a all-in-one package for openstack related log collection. And each of ELK stack componets was running in a docker container.

Quick Start
============

All containers are organized by ``docker-compose`` . For these containers were linked by each other, containers could not separated to different hosts.

How ever, you may change the configuration files and make it running separately on a cluster.

Reference
===========

* rsyslog - this directory contains rsyslog configurations which let rsyslog on openstack-node read openstack logs and tranport to logstash.

* logstash_patterns - a collection of grok patterns that help logstash's filter to parse openstask's logs.

* all configuration files are volumes that mounted to containers. So change them to make you feel cool !

* the base images used by this project can be found in hub.docker.com. They are offical base images of course.

**If you have problems with this project, please create an issue. And we need your pull requests! Thanks!**

**DOCKERS ARE COOL**

