# For recover database from SQL file

| cat ./backups/embold.sql | docker exec -i docker-postgresql_db_1 psql -U postgres -d embold

| https://gist.github.com/gilyes/525cc0f471aafae18c3857c27519fc4b
