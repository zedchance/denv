# denv

Docker environments with personal configs

## env

A basic environment, with the current directory mapped to `/env`:

```
docker run -it --rm -v "$(pwd):/env" zedchance/env
```

## cenv

A environment for C development.

```
docker run -it --rm -v "$(pwd):/env" zedchance/cenv
```

