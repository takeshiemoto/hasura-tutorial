# Hasura Tutorial

## Documents

- [Hasura CLI](https://hasura.io/docs/latest/graphql/core/hasura-cli/)

## Migration

```bash
hasura init <DEV_ENDPOINT>
```

```bash
hasura metadata export --envfile .dev.env
```

```bash
hasura migrate create <NAME> --envfile .dev.env
```

```bash
hasura metaadta apply --envfile .prod.env
```

```bash
hasura migrate apply --envfile .prod.env
```
