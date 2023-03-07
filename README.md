# setup

1. Clone repo
2. Copy .env_template to .env
3. Edit .env accordinly
4. Docker compose run



## commands summary

```bash
cp .env_template .env
nano .env

docker-compose up -d
```

`NB: mysql_data created can be backed up as it contains all databases and their settings. `

`Next time when starting, just place mysql_data folder in the directory to be mounted instead of created and thus restore the previous state.`
