# Overview
* Create managed-hana instance 
* Create hdi-share instance 

* Create redis instance
```
cf create-service redis v3.0-dev-large summit-redis
```
* Create rabbitmq instance
```
cf create-service rabbitmq v3.6-dev summit-rabbit-mq
```
**Service instance are also created in the cockpit**



Useful link: http://cli.cloudfoundry.org/en-US/cf/

