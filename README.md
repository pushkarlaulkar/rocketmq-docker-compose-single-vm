Execute below commands first

```
mkdir conf data
chown 3000:3000 conf/ -R
chown 3000:3000 data/ -R
mkdir -p ./data/broker/store/config
chown -R 3000:3000 ./data/broker/store/
```

Then run the ` docker compose up -d ` command.
