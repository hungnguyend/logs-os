# logs-os
logs-os

```
    2  docker build -t elasticsearch .
    3  docker run -d -p 9200:9200 -p 9300:9300 elasticsearch
    
    3 docker build -t logstash .
    4  docker run -d -p 5601:5601 -p 5001:5001 -p 5000:5000 logstash
    
  ```
