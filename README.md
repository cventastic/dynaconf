# dynaconf
### Smol helper service to keep whitelist up to date
### Usage:
```docker-compose up -d```
### Curls:
Create: ```curl -XPOST -H "Content-Type: application/json" http://127.0.0.1:5000/create -d '{"name":"frontend", "ip":"10.0.0.10"}```

Update: ```curl -XPOST -H "Content-Type: application/json" http://127.0.0.1:5000/update -d '{"name":"frontend", "ip":"10.0.0.110"}```

Delete: ```curl -XPOST -H "Content-Type: application/json" http://127.0.0.1:5000/delete -d '{"name":"frontend"```

get all entries: ```curl http://127.0.0.1:5000/storage```
