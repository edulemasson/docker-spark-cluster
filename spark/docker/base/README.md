# Spark base

- Spark 2.0
- Hadoop 2.7

The Spark base image serves as a base image for the Spark master, Spark worker and Spark submit images.

> The user should not run this image directly. 

## Build the base image:
bash```docker build --rm -t edulemasson/spark-base .``` 

> TODO: General Makefile with all commands


> Project inspired by [big-data-europe/docker-spark README](https://github.com/big-data-europe/docker-spark) for more information.