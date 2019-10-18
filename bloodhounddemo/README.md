Dockerfile for a BloodHound demo database.

Based on the [neo4j docker image](https://hub.docker.com/_/neo4j) and databased stole from [@SadProcessor's](https://twitter.com/sadprocessor) awesome [BloodHound workshop](https://github.com/SadProcessor/HandsOnBloodHound).

Get the full image from [dockerhub](https://hub.docker.com/r/peterhgombos/bloodhounddemo).

To run the database with the password "BloodHound", run
```docker run -p 7474:7474 -p 7687:7687 --env NEO4J_AUTH=neo4j/BloodHound --name bloodhound -d peterhgombos/bloodhounddemo```
