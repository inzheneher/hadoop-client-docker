# hadoop-client-docker
this is docker build for hadoop client.

# Usage
```docker run -it --rm -v <conf_dir>:/opt/cluster-conf ryneyang/hadoop-utils:2.7.7 hadoop fs -ls /```
1. conf_dir is the dir that holds hadoop confs, at least those 2 files (core-site.xml, hdfs-site.xml)
2. you can include yarn-site.xml to get yarn working so you can submit yarn applications
3. you can also extend this image to build more application level services

# Dockerhub
https://hub.docker.com/r/ryneyang/hadoop-utils/
