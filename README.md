# htpasswd

## Usage

To generate a password file:

```shell
docker run --rm -ti parkmo/htpasswd <username> <password> > htpasswd
```

This will use SHA1 encryption.
