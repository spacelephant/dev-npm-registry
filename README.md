# Our NPMJS registry for developments

Based on [Verdaccio](https://verdaccio.org).

# Usage

```shell
$ yarn
$ yarn start
```

# Local configuration

```shell
$ yarn config set strict-ssl false
$ yarn config set registry http://localhost:7000/ && npm config set registry http://localhost:7000/
```

# Configuration

See :
- https://verdaccio.org/docs/en/configuration
- [./config.yml](./config.yml)
