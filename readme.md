# minimum viable cypher snippets
The goal of this repo is to keep a folder for each language and each Neo4j Cypher-supporting driver, along with a sample Cypher "hello world" program. Tested with the latest Neo4j!

[![Build Status](https://travis-ci.org/wfreeman/mvcs.png?branch=master)](https://travis-ci.org/wfreeman/mvcs)

I don't profess to be an expert in all of these languages. Please, if you have a more idiomatic hello Cypher test, submit a PR. Ideally, make sure it runs in the .travis.yml as well. If your driver is not here yet, it probably means I haven't gotten to it yet; let me know if you're going to submit a PR because I may already be working on it.

Thank you [contributors!](https://github.com/wfreeman/mvcs/graphs/contributors)

a baby dataset for our hello Cypher query:
```
merge (u:User {screenName:"wefreema"}) 
merge (u)-[:FOLLOWS]->(j:User {screenName:"JnBrymn"}) 
merge (u)-[:FOLLOWS]->(n:User {screenName:"technige"});
```

driver list - sorted alphabetically by language and then driver name:

### clojure
[neocons](/clojure/neocons/)
### java
[Neo4j API - embedded](/java/embedded/)
### jruby
### go
[cq](/go/cq/)
### haskell
### node.js
[philippkueng.node-neo4j](/node.js/philippkueng.node-neo4j/)  
[thingdom.node-neo4j](/node.js/thingdom.node-neo4j/)  
### perl
### php
### python
[py2neo](/python/py2neo/)
### ruby
### scala
[AnormCypher](/scala/anormcypher/)
