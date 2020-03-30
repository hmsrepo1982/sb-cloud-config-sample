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
