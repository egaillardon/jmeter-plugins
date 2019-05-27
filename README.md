# Docker image for **Apache JMeter** and **JMeter plugins**

[![Apache JMeter Logo](https://jmeter.apache.org/images/logo.svg)](https://jmeter.apache.org)
[![JMeter PLugins Logo](https://jmeter-plugins.org/img/site/logo.png)](https://jmeter-plugins.org)

[![Docker Stars](https://img.shields.io/docker/stars/egaillardon/jmeter-plugins.svg?style=plastic)](https://hub.docker.com/r/egaillardon/jmeter-plugins/)
[![Docker Pulls](https://img.shields.io/docker/pulls/egaillardon/jmeter-plugins.svg?style=plastic)](https://hub.docker.com/r/egaillardon/jmeter-plugins/)
[![Docker Automated build](https://img.shields.io/docker/automated/egaillardon/jmeter-plugins.svg?style=plastic)](https://hub.docker.com/r/egaillardon/jmeter-plugins/)
[![Docker Build Status](https://img.shields.io/docker/build/egaillardon/jmeter-plugins.svg?style=plastic)](https://hub.docker.com/r/egaillardon/jmeter-plugins/)


[![Github Stars](https://img.shields.io/github/stars/egaillardon/jmeter-plugins.svg?style=social)](https://github.com/egaillardon/jmeter-plugins)
[![Github Forks](https://img.shields.io/github/forks/egaillardon/jmeter-plugins.svg?style=social)](https://github.com/egaillardon/jmeter-plugins)

[![Follow](https://img.shields.io/twitter/follow/egaillardon_org.svg?label=Follow&style=social)](https://twitter.com/egaillardon_org)
[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=%40egaillardon_org%20-%20Docker%20image%20for%20Apache%20JMeter%20and%20JMeter%20plugins%20-%20https%3A%2F%2Fhub.docker.com%2Fr%2Fegaillardon%2Fjmeter-plugins%20%3A)


* **Apache JMeter** : an application designed to load test functional behavior and measure performance - https://jmeter.apache.org

* **JMeter Plugins** : an independent set of plugins - https://jmeter-plugins.org


* The **version number** is composed of two version numbers
  * the first is the version of the Apache JMeter embedded in this docker image
  * the second is for this docker image itself

## Apache JMeter including all plugins available with the JMeter Plugins Manager

* `egaillardon/jmeter-plugins`

***For a Docker image containing only Apache JMeter, see https://hub.docker.com/r/egaillardon/jmeter/***

### Supported tags and respective `Dockerfile` links

* Apache JMeter 5.1.1 (see changelog below)
  * `latest`, `5.1.1-1.1.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.1.1-1.1.0/Dockerfile)
  * `5.1.1-1.0.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.1.1-1.0.1/Dockerfile)
  * `5.1.1-1.0.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.1.1-1.0.0/Dockerfile)


* Apache JMeter 5.1 (see changelog below)
  * **No more new 5.1 version (03/31/2019)**
  * `5.1.0-1.0.2` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.1.0-1.0.2/Dockerfile)
  * `5.1.0-1.0.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.1.0-1.0.1/Dockerfile)
  * `5.1.0-1.0.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.1.0-1.0.0/Dockerfile)


* Apache JMeter 5.0 (see changelog below)
  * **No more new 5.0 version (02/20/2019)**
  * `5.0.0-6.0.4` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-6.0.4/Dockerfile-jmeter5-plugins)
  * `5.0.0-6.0.3` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-6.0.3/Dockerfile-jmeter5-plugins)
  * `5.0.0-6.0.2` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-6.0.2/Dockerfile-jmeter5-plugins)
  * `5.0.0-6.0.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-6.0.1/Dockerfile-jmeter5-plugins)
  * `5.0.0-6.0.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-6.0.0/Dockerfile-jmeter5-plugins)
  * `5.0.0-5.0.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-5.0.0/Dockerfile-jmeter5-plugins)
  * `5.0.0-4.0.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-4.0.0/Dockerfile-jmeter5-plugins)
  * `5.0.0-2.1.2` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-2.1.2/Dockerfile-jmeter5-plugins)
  * `5.0.0-2.1.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-2.1.1/Dockerfile-jmeter5-plugins)
  * `5.0.0-2.1.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-2.1.0/Dockerfile-jmeter5-plugins)
  * `5.0.0-2.0.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-2.0.1/Dockerfile-jmeter5-plugins)
  * `5.0.0-2.0.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-2.0.0/Dockerfile-jmeter5-plugins)
  * `5.0.0-1.0.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-1.0.1/Dockerfile-jmeter5-plugins)
  * `5.0.0-1.0.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/5.0.0-1.0.0/Dockerfile-jmeter5-plugins)


* Apache JMeter 4.0 (see changelog below)
  * **No more new 4.0 version (02/20/2019)**
  * `4.0.0-6.0.4` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-6.0.4/Dockerfile-jmeter4-plugins)
  * `4.0.0-6.0.3` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-6.0.3/Dockerfile-jmeter4-plugins)
  * `4.0.0-6.0.2` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-6.0.2/Dockerfile-jmeter4-plugins)
  * `4.0.0-6.0.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-6.0.1/Dockerfile-jmeter4-plugins)
  * `4.0.0-6.0.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-6.0.0/Dockerfile-jmeter4-plugins)
  * `4.0.0-5.0.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-5.0.0/Dockerfile-jmeter4-plugins)
  * `4.0.0-3.1.2` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-3.1.2/Dockerfile-jmeter4-plugins)
  * `4.0.0-3.1.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-3.1.1/Dockerfile-jmeter4-plugins)
  * `4.0.0-3.1.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-3.1.0/Dockerfile-jmeter4-plugins)
  * `4.0.0-3.0.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-3.0.1/Dockerfile-jmeter4-plugins)
  * `4.0.0-3.0.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-3.0.0/Dockerfile-jmeter4-plugins)
  * `4.0.0-2.2.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-2.2.1/Dockerfile-jmeter4-plugins)
  * `4.0.0-2.2.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-2.2.0/Dockerfile-plugins)
  * `4.0.0-2.1.4` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-2.1.4/Dockerfile-plugins)
  * `4.0.0-2.1.3` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-2.1.3/Dockerfile-plugins)
  * `4.0.0-2.1.2` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-2.1.2/Dockerfile-plugins)
  * `4.0.0-2.1.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-2.1.1/Dockerfile-plugins)
  * `4.0.0-2.1.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-2.1.0/Dockerfile-plugins)
  * `4.0.0-2.0.3` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-2.0.3/Dockerfile-plugins)
  * `4.0.0-2.0.2` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-2.0.2/Dockerfile-plugins)
  * `4.0.0-2.0.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-2.0.1/Dockerfile-plugins)
  * `4.0.0-2.0.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-2.0.0/Dockerfile-plugins)
  * `4.0.0-1.2.3` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-1.2.3/Dockerfile-plugins)
  * `4.0.0-1.2.2` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-1.2.2/Dockerfile-plugins)
  * `4.0.0-1.2.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-1.2.1/Dockerfile-plugins)
  * `4.0.0-1.2.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-1.2.0/Dockerfile-plugins)
  * `4.0.0-1.1.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-1.1.0/Dockerfile-plugins)
  * `4.0.0-1.0.4` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-1.0.4/Dockerfile-plugins)
  * `4.0.0-1.0.3` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-1.0.3/Dockerfile-plugins)
  * `4.0.0-1.0.2` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-1.0.2/Dockerfile-plugins)
  * `4.0.0-1.0.1` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-1.0.1/Dockerfile-plugins)
  * `4.0.0-1.0.0` [(Dockerfile)](https://github.com/egaillardon/jmeter-plugins/blob/4.0.0-1.0.0/Dockerfile-plugins)

## Quick reference

* Where to get more information about Apache JMeter and JMeter Plugins
  * [Apache JMeter](http://jmeter.apache.org)
  * [Apache JMeter Getting Started](http://jmeter.apache.org/usermanual/get-started.html)
  * [Apache JMeter Remote Testing](http://jmeter.apache.org/usermanual/remote-test.html)
  * [Apache JMeter Distributed Testing Step-by-step](http://jmeter.apache.org/usermanual/jmeter_distributed_testing_step_by_step.html)
  * [JMeter Plugins](https://jmeter-plugins.org)
* Where to get more information about Docker
  * [Docker](https://www.docker.com)
  * [Get started with Docker](https://docs.docker.com/get-started/)
  * [Docker run reference](https://docs.docker.com/engine/reference/run/)

## How to use this image

### Working directory

The working directory defined in the Dockerfile is `/jmeter`.

### Default User

The default user is `jmeter`.

### Environment variables

| Variable          |  Description                                                           | Default value                                                                      |
| ----------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `GC_ALGO`         |  Java runtime options to specify JVM garbage collection algorithm      | `"-XX:+UseG1GC -XX:MaxGCPauseMillis=100 -XX:G1ReservePercent=20"`                  |
| `VERBOSE_GC`      |  Java runtime options to generate GC verbose file                      | `"-verbose:gc -Xloggc:gc_jmeter_%p.log -XX:+PrintGCDetails -XX:+PrintGCCause  -XX:+PrintTenuringDistribution -XX:+PrintHeapAtGC -XX:+PrintGCApplicationConcurrentTime  -XX:+PrintAdaptiveSizePolicy -XX:+PrintGCApplicationStoppedTime -XX:+PrintGCDateStamps"` |
| `HEAP`            | Java runtime options for memory management used when JMeter is started | `"-Xms1g -Xmx1g -X:MaxMetaspaceSize=256m"`                                         |
| `JMETER_LANGUAGE` | Java runtime options to specify used language                          | `"-Duser.language=en -Duser.region=EN"`                                            |
| `JMETER_OPTS`     | Java runtime options used when JMeter is started                       | `""`                                                                               |
| `JVM_ARGS`        | Optional java args, e.g. -Dprop=val                                    | `""`                                                                               |
| `JMETER_GROUP_ID` | Set the jmeter user's group id inside the container | `1000` |
| `JMETER_USER_ID`  | Set the jmeter user's id inside the container | `1000` |


### Running clients and servers

#### Running standalone clients

###### Runner an interactive dockerized client in non-GUI mode

`docker run --interactive --tty --rm --volume `pwd`:/jmeter egaillardon/jmeter-plugins --nongui --testfile test.jmx --logfile result.jtl`

###### Runner a detached dockerized client in non-GUI mode

`docker run --detach --rm --volume `pwd`:/jmeter egaillardon/jmeter-plugins --nongui --testfile test.jmx --logfile result.jtl`

#### Running servers

###### Running a server on 192.168.1.1 with default RMI port (1099) and SSL for RMI disabled

`docker run --detach --publish 1099:1099 --rm egaillardon/jmeter-plugins -Jserver.rmi.ssl.disable=true -Djava.rmi.server.hostname=192.168.1.1 -Jserver.rmi.localport=1099 --server`

###### Running a server on 192.168.1.1 with specified RMI port (1098) and SSL for RMI disabled

`docker run --detach --publish 1098:1098 --rm egaillardon/jmeter-plugins -Jserver.rmi.ssl.disable=true -Djava.rmi.server.hostname=192.168.1.1 -Jserver.rmi.localport=1098 -Dserver_port=1098 --server`

#### Running clients in distributed tesing mode

###### Running a client in non-GUI mode with SSL for RMI disabled, connecting to a remote server on 192.168.1.1 with default RMI port (1099)

* with docker

`docker run --detach --rm --volume `pwd`:/jmeter egaillardon/jmeter-plugins -Jserver.rmi.ssl.disable=true --nongui --testfile test.jmx --remotestart 192.168.1.1 --logfile result.jtl`

* without docker

`jmeter -Jserver.rmi.ssl.disable=true --nongui --testfile ../test.jmx --remotestart 192.168.1.1 --logfile result.jtl`

###### Running a dockerized client in non-GUI mode with SSL for RMI disabled, connecting to a remote server on 192.168.1.1 with specfied RMI port (1098)

* with docker

`docker run --detach --rm --volume `pwd`:/jmeter egaillardon/jmeter-plugins -Jserver.rmi.ssl.disable=true --nongui --testfile test.jmx --remotestart 192.168.1.1:1098 --logfile result.jtl`

* without docker

`jmeter -Jserver.rmi.ssl.disable=true --nongui --testfile ../test.jmx --remotestart 192.168.1.1:1098 --logfile result.jtl`

###### Running a dockerized client in non-GUI mode with SSL for RMI disabled, connecting to the two remote servers on 192.168.1.1

* with docker

`docker run --detach --rm --volume `pwd`:/jmeter egaillardon/jmeter-plugins -Jserver.rmi.ssl.disable=true --nongui --testfile test.jmx --remotestart 192.168.1.1:1098,192.168.1.1:1099 --logfile result.jtl`

* without docker

`jmeter -Jserver.rmi.ssl.disable=true --nongui --testfile ../test.jmx --remotestart 192.168.1.1:1098,192.168.1.1:1099 --logfile result.jtl`

#### An example that generates a report at the end of the run

`docker run --detach --rm --volume `pwd`:/jmeter egaillardon/jmeter-plugins -Jserver.rmi.ssl.disable=true --nongui --testfile test.jmx --remotestart 192.168.1.1:1098,192.168.1.1:1099 --logfile result.jtl --forceDeleteResultFile --reportatendofloadtests --reportoutputfolder report -Jjmeter.reportgenerator.overall_granularity=10000`

### Full list of command-line options

#### Command

`docker run --interactive --tty --rm egaillardon/jmeter-plugins`

#### Result

```
--?
  print command line options and exit
-h, --help
  print usage information and exit
-v, --version
  print the version information and exit
-p, --propfile <argument>
  the jmeter property file to use
-q, --addprop <argument>
  additional JMeter property file(s)
-t, --testfile <argument>
  the jmeter test(.jmx) file to run. "-t LAST" will load last
  used file
-l, --logfile <argument>
  the file to log samples to
-i, --jmeterlogconf <argument>
  jmeter logging configuration file (log4j2.xml)
-j, --jmeterlogfile <argument>
  jmeter run log file (jmeter.log)
-n, --nongui
  run JMeter in nongui mode
-s, --server
  run the JMeter server
-E, --proxyScheme <argument>
  Set a proxy scheme to use for the proxy server
-H, --proxyHost <argument>
  Set a proxy server for JMeter to use
-P, --proxyPort <argument>
  Set proxy server port for JMeter to use
-N, --nonProxyHosts <argument>
  Set nonproxy host list (e.g. *.apache.org|localhost)
-u, --username <argument>
  Set username for proxy server that JMeter is to use
-a, --password <argument>
  Set password for proxy server that JMeter is to use
-J, --jmeterproperty <argument>=<value>
  Define additional JMeter properties
-G, --globalproperty <argument>=<value>
  Define Global properties (sent to servers)
  e.g. -Gport=123
   or -Gglobal.properties
-D, --systemproperty <argument>=<value>
  Define additional system properties
-S, --systemPropertyFile <argument>
  additional system property file(s)
-f, --forceDeleteResultFile
  force delete existing results files and web report folder if
   present before starting the test
-L, --loglevel <argument>=<value>
  [category=]level e.g. jorphan=INFO, jmeter.util=DEBUG or com
  .example.foo=WARN
-r, --runremote
  Start remote servers (as defined in remote_hosts)
-R, --remotestart <argument>
  Start these remote servers (overrides remote_hosts)
-d, --homedir <argument>
  the jmeter home directory to use
-X, --remoteexit
  Exit the remote servers at end of test (non-GUI)
-g, --reportonly <argument>
  generate report dashboard only, from a test results file
-e, --reportatendofloadtests
  generate report dashboard after load test
-o, --reportoutputfolder <argument>
  output folder for report dashboard
```

### Tips and tricks

#### Stopping a server after the end of the test

Set the JMeter property `server.exitaftertest` to true.

`docker run --detach --publish 1099:1099 --rm egaillardon/jmeter-plugins -Jserver.rmi.ssl.disable=true -Djava.rmi.server.hostname=192.168.1.15 -Jserver.rmi.localport=1099 -Jserver.exitaftertest=true --server`

#### Stopping a test before the end

Replace `relaxed_kilby` by your client container id or name.

`docker exec -it relaxed_kilby shutdonwn.sh`  
or  
`docker exec -it relaxed_kilby stoptest.sh`

#### Setting a fixed RMI port on the client side

Set the JMeter property `client.rmi.localport` (useful when there is a firewall between the client and servers).

`docker run --detach --rm --volume `pwd`:/jmeter egaillardon/jmeter-plugins -Jserver.rmi.ssl.disable=true -Jclient.rmi.localport=2500 --nongui --testfile test.jmx  --remotestart 192.168.1.15:1098,192.168.1.15:1099 --logfile result.jtl`

#### Sending the content of the jmeter log file to console
Set the `jmeterlogconf` option in order to use another [log4j2.xml file (see the example file provided)](https://github.com/egaillardon/jmeter-plugins/blob/master/log4j2.xml)

`docker run --detach --publish 1099:1099 --volume `pwd`:/jmeter --rm egaillardon/jmeter-plugins -Jserver.rmi.ssl.disable=true -Djava.rmi.server.hostname=192.168.1.15 -Jserver.rmi.localport=1099 -Dserver_port=1099 --server --jmeterlogconf log4j2.xml`

#### Running a client in GUI mode, with SSL for RMI disabled, to connect to remote servers

`jmeter -Jremote_hosts=192.168.1.1 -Jserver.rmi.ssl.disable=true`

#### SSL for RMI
In distributed testing, SSL for RMI has to be enabled or disabled on both sides.
See [Apache JMeter Remote Testing](http://jmeter.apache.org/usermanual/remote-test.html) for more information.

#### Getting the IP address
* On Linux

`hostname -I`  
`/sbin/ifconfig eth0 | grep 'inet '| awk '{ print $2}'`

* On macOS

`ipconfig getifaddr en0`  
`/sbin/ifconfig en0 | grep 'inet '| awk '{ print $2}'`

#### Setting your timezone in the docker container
* Add the `TZ` environment variable

`docker run --detach --publish 1099:1099 --env TZ=Europe/Paris --rm egaillardon/jmeter-plugins`

#### Assigning the local user's id and group to the jmeter user inside the container

`docker run --env JMETER_GROUP_ID=`/usr/bin/id -g` --env JMETER_USER_ID=`/usr/bin/id -u` --rm egaillardon/jmeter --server -Jserver.rmi.ssl.disable=true`

## Changelog

* Apache JMeter 5.1.1
  * 5.1.1-1.1.0 :
    * [JMeter Listener pack (jmeter.pack-listener)](https://gitlab.com/testload/jmeter-listener/wikis/home) : add 1.5
  * 5.1.1-1.0.1 :
    * [RTE Protocol Support (bzm-rte)](https://github.com/Blazemeter/RTEPlugin/blob/master/README.md) : upgrade to 1.1.1 from 1.1
    * [HLS Sampler (bzm-hls)](https://github.com/Blazemeter/HLSPlugin/blob/master/README.md) : upgrade to 1.3 from 1.2
  * 5.1.1-1.0.0 :
    * [RTE Protocol Support (bzm-rte)](https://github.com/Blazemeter/RTEPlugin/blob/master/README.md) : upgrade to 1.1 from 1.0.4
    * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.6.1 from 2.6.0
    * Change docker base image version to `egaillardon/jmeter:5.1.1-1.0.0`


* Apache JMeter 5.1
  * 5.1.0-1.0.2 :
    * [Custom Thread Groups (jpgc-casutg)](https://jmeter-plugins.org/wiki/ConcurrencyThreadGroup/) : upgrade to 2.8 from 2.7
  * 5.1.0-1.0.1 :
    * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.6.0 from 2.5.4
  * 5.1.0-1.0.0 :
    * Change docker base image version to `egaillardon/jmeter:5.1.0-1.0.0`


* Apache JMeter 5.0
  * 5.0.0-6.0.4 :
    * [Custom Thread Groups (jpgc-casutg)](https://jmeter-plugins.org/wiki/ConcurrencyThreadGroup/) : upgrade to 2.7 from 2.6
  * 5.0.0-6.0.3 :
    * [HTTP Simple Table Server (jpgc-sts)](https://jmeter-plugins.org/wiki/HttpSimpleTableServer/) : upgrade to 2.4 from 2.3
  * 5.0.0-6.0.2 :
    * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.5.4 from 2.5.3
  * 5.0.0-6.0.1 :
    * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.5.3 from 2.5.2
  * 5.0.0-6.0.0 :
    * Change docker base image version to `egaillardon/jmeter:5.0.0-2.1.1`
  * 5.0.0-5.0.0 :
    * Change docker base image version to `egaillardon/jmeter:5.0.0-2.1.0`
  * 5.0.0-4.0.0 :
    * Change docker base image version to `egaillardon/jmeter:5.0.0-2.0.0` (Change base image from openjdk to openjdk-alpine)
  * 5.0.0-2.1.2 :
    * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.5.2 from 2.5.1
  * 5.0.0-2.1.1 :
    * [Parallel Controller & Sampler (bzm-parallel)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/parallel/Parallel.md) : upgrade to 0.9 from 0.8
  * 5.0.0-2.1.0 :
    * The jmeter user's id and its group id can be changed inside the container in order to avoid issue when mounting local volumes.
  * 5.0.0-2.0.1
    * [Parallel Controller & Sampler (bzm-parallel)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/parallel/Parallel.md) : upgrade to 0.8 from 0.7
    * [Custom SOAP Sampler (custom-soap)](https://github.com/spinning10/JMeterSoapSampler/wiki) : upgrade to 1.3.3 from 1.3
  * 5.0.0-2.0.0
    * Change docker base image version to `egaillardon/jmeter:5.0.0-1.1.0`
  * 5.0.0-1.0.0
    * Upgrade to Apache JMeter 5.0.0
  * 5.0.0-1.0.1
    * [UDP Protocol Support (jpgc-udp)](https://jmeter-plugins.org/wiki/UDPRequest/) : upgrade to 0.4 from 0.3


* Apache JMeter 4.0
  * 4.0.0-6.0.4 :
    * [Custom Thread Groups (jpgc-casutg)](https://jmeter-plugins.org/wiki/ConcurrencyThreadGroup/) : upgrade to 2.7 from 2.6
  * 4.0.0-6.0.3 :
    * [HTTP Simple Table Server (jpgc-sts)](https://jmeter-plugins.org/wiki/HttpSimpleTableServer/) : upgrade to 2.4 from 2.3
  * 4.0.0-6.0.2 :
    * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.5.4 from 2.5.3
  * 4.0.0-6.0.1 :
    * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.5.3 from 2.5.2
  * 4.0.0-6.0.0 :
    * Change docker base image version to `egaillardon/jmeter:4.0.0-2.1.1`
  * 4.0.0-5.0.0 :
    * Change docker base image version to `egaillardon/jmeter:4.0.0-2.1.0`
  * 4.0.0-4.0.0 :
    * Change docker base image version to `egaillardon/jmeter:4.0.0-2.0.0`(Change base image from openjdk to openjdk-alpine)
  * 4.0.0-3.1.2 :
    * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.5.2 from 2.5.1
  * 4.0.0-3.1.1 :
    * [Parallel Controller & Sampler (bzm-parallel)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/parallel/Parallel.md) : upgrade to 0.9 from 0.8
  * 4.0.0-3.1.0 :
    * The jmeter user's id and its group id can be changed inside the container in order to avoid issue when mounting local volumes.
  * 4.0.0-3.0.1
    * [Parallel Controller & Sampler (bzm-parallel)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/parallel/Parallel.md) : upgrade to 0.8 from 0.7
    * [Custom SOAP Sampler (custom-soap)](https://github.com/spinning10/JMeterSoapSampler/wiki) : upgrade to 1.3.3 from 1.3
  * 4.0.0-3.0.0
    * Change docker base image version to `egaillardon/jmeter:4.0.0-1.2.0`
  * 4.0.0-2.2.1
    * [UDP Protocol Support (jpgc-udp)](https://jmeter-plugins.org/wiki/UDPRequest/) : upgrade to 0.4 from 0.3
  * 4.0.0-2.2.0 :
    * [Siebel CRM Recorder (bzm-siebel)](https://github.com/Blazemeter/SiebelPlugin/blob/master/README.md) : add 0.1.0-beta
  * 4.0.0-2.1.4 :
    * [Filter Results Tool (jpgc-filterresults)](https://jmeter-plugins.org/wiki/FilterResultsTool/) : upgrade to 2.2 from 2.1
    * [Custom Thread Groups (jpgc-casutg)](https://jmeter-plugins.org/wiki/ConcurrencyThreadGroup/) : upgrade to 2.6 from 2.5
    * [Selenium/WebDriver Support (jpgc-webdriver)](https://jmeter-plugins.org/wiki/WebDriverSampler/) : upgrade to 3.0 from 2.3
    * [JSON/YAML Plugins (deprecated) (jpgc-json)](https://jmeter-plugins.org/wiki/JSONPathExtractor/) : upgrade to 2.7 from 2.6
    * [Command-Line Graph Plotting Tool (jpgc-cmd)](https://jmeter-plugins.org/wiki/JMeterPluginsCMD/) : upgrade to 2.2 from 2.1
    * [SSHMon Sample Collector (tilln-sshmon)](https://github.com/tilln/jmeter-sshmon) : upgrade to 1.1 from 1.0
    * [Redis Data Set (jpgc-redis)](https://jmeter-plugins.org/wiki/RedisDataSet/) : upgrade to 0.3 from 0.2
    * [Weighted Switch Controller (jpgc-wsc)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/wsc/WeightedSwitchController.md) : upgrade to 0.7 from 0.6
    * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.5.1 from 2.5.0
    * [WS Security for SOAP (tilln-wssecurity)](https://github.com/tilln/jmeter-wssecurity) : upgrade to 1.6 from 1.5
    * [Test Plan Check Tool (jpgc-plancheck)](https://jmeter-plugins.org/wiki/TestPlanCheckTool/) : upgrade to 2.4 from 2.3
  * 4.0.0-2.1.3 :
    * [Test Plan Check Tool (jpgc-plancheck)](https://jmeter-plugins.org/wiki/TestPlanCheckTool/) : upgrade to 2.3 from 2.2
  * 4.0.0-2.1.2 :
    * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.5.0 from 2.4.3
    * [Weighted Switch Controller (jpgc-wsc)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/wsc/WeightedSwitchController.md) : upgrade to 0.6 from 0.5
  * 4.0.0-2.1.1 :
    * [HTTP/2 Sampler (bzm-http2)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/http2/README.md) : upgrade to 1.4 from 1.3
    * [Synthesis Report (jpgc-synthesis)](https://jmeter-plugins.org/wiki/SynthesisReport/) : upgrade to 2.2 from 2.1
    * [BM.Sense Uploader (jpgc-sense)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/sense-uploader/BlazemeterPlugin.md) : upgrade to 3.5 from 3.4
  * 4.0.0-2.1.0 :
    * [RTE Protocol Support (bzm-rte)](https://github.com/Blazemeter/RTEPlugin/blob/master/README.md) : add 1.0.4
  * 4.0.0-2.0.3 :
    * [WebSocket Samplers by Peter Doornbosch (websocket-samplers)](https://bitbucket.org/pjtr/jmeter-websocket-samplers/overview) : upgrade to 1.2.1 from 1.2
    * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.4.3 from 2.4.1
  * 4.0.0-2.0.2 :
    * [Weighted Switch Controller (jpgc-wsc)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/wsc/WeightedSwitchController.md) : upgrade to 0.5 from 0.4
  * 4.0.0-2.0.1 :
    * [HTTP/2 Sampler (bzm-http2)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/http2/README.md) : upgrade to 1.3 from 1.2
    * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.4.1 from 2.3.1
  * 4.0.0-2.0.0 :
     * [Plugins Manager](https://jmeter-plugins.org/wiki/PluginsManager/) : upgrade to 1.3 from 1.2
  * 4.0.0-1.2.3 :
     * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.3.2 from 2.3.1
  * 4.0.0-1.2.2 :
     * [HTTP/2 Sampler (bzm-http2)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/http2/README.md) : upgrade to 1.2 from 1.1
     * [Plugins Manager](https://jmeter-plugins.org/wiki/PluginsManager/) : upgrade to 1.2 from 1.0.1
     * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.3.1 from 2.2.5
     * [Throughput Shaping Timer (jpgc-tst)](https://jmeter-plugins.org/wiki/ThroughputShapingTimer/) : upgrade to 2.5 from 2.4
     * [Weighted Switch Controller (jpgc-wsc)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/wsc/WeightedSwitchController.md) : upgrade to 0.4 from 0.3
     * [WebSocket Samplers by Peter Doornbosch (websocket-samplers)](https://bitbucket.org/pjtr/jmeter-websocket-samplers/overview) : upgrade to 1.2 from 1.1
  * 4.0.0-1.2.1 :
     * [Parallel Controller & Sampler (bzm-parallel)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/parallel/Parallel.md) : upgrade to 0.7 from 0.5
  * 4.0.0-1.2.0 :
     * [Plugins Manager](https://jmeter-plugins.org/wiki/PluginsManager/) : upgrade to 1.0.1 from 0.20
     * [CMD Runner](https://jmeter-plugins.org/wiki/PluginsManagerAutomated/) : upgrade to 2.2.1 from 2.0
  * 4.0.0-1.1.0 :
     * Set the user `jmeter` when running the image
  * 4.0.0-1.0.4 :
     * [Parallel Controller & Sampler (bzm-parallel)](https://github.com/Blazemeter/jmeter-bzm-plugins/blob/master/parallel/Parallel.md) : upgrade to 0.5 from 0.4
  * 4.0.0-1.0.3 :
     * [ElasticSearch backend listener (jmeter.backendlistener.elasticsearch)](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) : upgrade to 2.2.5 from 2.2.4
  * 4.0.0-1.0.2 :
     * [Throughput Shaping Timer (jpgc-tst)](https://jmeter-plugins.org/wiki/ThroughputShapingTimer/) : upgrade to 2.4 from 2.3
  * 4.0.0-1.0.1 :
     * [Custom JMeter Functions (jpgc-functions)](https://jmeter-plugins.org/wiki/Functions/) : upgrade to 2.1 from 2.0
     * [Parameterized Controller & Set Variables Action (jpgc-prmctl)](https://jmeter-plugins.org/wiki/ParameterizedController/) : upgrade to 0.4 from 0.3
