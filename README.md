# The official starter repository for the Rock the JVM Akka Persistence with Scala course

Powered by [Rock the JVM!](rockthejvm.com)

This repository contains the starter code for the [Rock the JVM's Akka Persistence with Scala](https://www.udemy.com/akka-persistence) course on Udemy.

### How to install
- either clone the repo or download as zip
- open with IntelliJ as an SBT project

No need to do anything else, as the IDE will take care to download and apply the appropriate library dependencies.

### The complete code

The repository for the completed code is [here](https://github.com/rockthejvm/udemy-akka-persistence). You can follow the instructions there - although the download/import steps are identical to this one. Additionally, the completed repo is enhanced with commit tags that allow you to go back to an earlier state of the repository, prior to each lecture.

### Contents in this repo

* a filled-in `build.sbt` with the appropriate library dependencies
* a complete Scala IntelliJ project with a `Playground` app that you can compile to see that the libraries were downloaded
* a `docker-compose.yml` with already configured Docker containers for Postgres and Cassandra
* a simple `docker-clean.sh` script to remove your Docker containers if you want to start them fresh
* a `/sql` folder with a SQL script that will automatically be run in the Postgres container and create the correct tables for Akka (more on that in the PostgreSQL lecture)
* a helper script `psql.sh` to easily connect to Postgres once started
* a helper scripte `cqlsh.sh` to easily connect to Cassandra once started

### For questions or suggestions

If you have changes to suggest to this repo, either
- submit a GitHub issue
- tell me in the course Q/A forum
- submit a pull request!
