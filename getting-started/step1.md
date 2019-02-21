## Start ArangoDB Docker Container
`docker run -e ARANGO_ROOT_PASSWORD=test123 -p 8529:8529 -d arangodb/arangodb`{{execute}}

## Access the UI
Wait for the container and ArangoDB to be started (might take up to 2 minutes) and then switch to the ArangoDB UI Tab or use the below link to open a new window. 

https://[[HOST_SUBDOMAIN]]-8529-[[KATACODA_HOST]].environments.katacoda.com

## Login 
Login using user `root`  and password `test123`.

Select the _system database.

*Welcome to ArangoDB!*
