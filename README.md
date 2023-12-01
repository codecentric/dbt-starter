# Picard dbt starter

## Requirements
A working installation of [dbt](https://docs.getdbt.com/docs/get-started/installation). Install dbt-postgres.
Check with
```bash
dbt --version
installed version: 1.0.0
   latest version: 1.0.0

Up to date!

Plugins:
  - postgres: 1.0.0```
```

The DB connection has to be setup in a `profiles.yml` file oryin the root of this reposit which can be generated using the
provided [profiles_template.yml](profiles_template.yml).

### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
