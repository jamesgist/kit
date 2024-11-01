

```bash
curl -XPOST -d'{"s":"hello, world"}' localhost:8000/uppercase
```

```bash
curl -XPOST -d'{"s":"hello, world"}' localhost:8000/count
```

- `source ~/.aws/setcredentials.rc`
- `prometheus --config.file=prometheus.yaml --storage.tsdb.path=$HOME/tmp/data`