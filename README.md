# the bonsai

- Authenticated WebDAV server
- qBittorrent

## Commands

### Password generation

```bash
$ podman run --rm -it docker.io/library/httpd htpasswd -n <username> <password> > ./nginx/htpasswd
```