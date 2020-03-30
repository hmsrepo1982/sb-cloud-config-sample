# sb-cloud-config-sample

- Externalized.
- Environment Specific
- Consistent
- Version History
- Realtime management 

Only 2 achieved - Externalized ( Property Files ) | 

Where config server stores this ??

Runtime value changes - how this is possible.

Spring Cloud Config Server -----> can connect to different Data Sources.

1. Database - wont work.

2. what if it can look up REPO Server. Thats what exactly solution it would work upon. This service can connect to GIT REPO.

Now changes become very simple. Make the change in GIT repo or commit change to GIT repo - 
Code has datasource pointing to GIT REPO.
Now it would take changes in real time instead - change, Build / deploy so that properties are hosted inside server.


This is Cloud config server and it is using application.yml file in spring 

https://github.com/hmsrepo1982/sb-config-server//application.yml

the Key used is # 

spring.cloud.config.server.git.uri=https://github.com/hmsrepo1982/sb-config-server/

Default application URI to check this is #

http://localhost:port/<file-name>/default 
  
when you run this application, you can form application url as suggested above so that you can see config file.
