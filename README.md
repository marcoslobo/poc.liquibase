# poc.liquibase
Proof of concept for liquibase migrations

1- Run docker compose for the database
```bash
Docker-compose -f docker-compose.database.yml up
```

2- Run docker compose for the Liquibase migration
```bash
Docker-compose -f docker-compose.liquibase.yml up
```

All scripts inside /scripts folder will be executed on target database
