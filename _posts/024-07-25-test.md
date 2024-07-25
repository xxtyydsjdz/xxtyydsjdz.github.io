---
title: test
date: 2024-07-25 16:41:53 +0800
categories: [TOP_CATEGORIE, SUB_CATEGORIE]
tags: [test-tag]
---

# Neo4j
## 部署
### docker
```bash
docker pull neo4j:4.4-community
```

```bash
docker run \
    --publish=7474:7474 --publish=7687:7687 \
    --env NEO4J_AUTH=jdz/jdz123 \
    --volume /usr/local/docker_data/neo4j/data:/data \
    --volume /usr/local/docker_data/neo4j/logs:/logs \
    neo4j:4.4-community
```

>docker run --publish=7474:7474 --publish=7687:7687 --env NEO4J_AUTH=neo4j/jdz123  --volume /neo4j/data:/data --volume=/neo4j/logs:/logs neo4j:4.4-community

## 使用
### 增
create
