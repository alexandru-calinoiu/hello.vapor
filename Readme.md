# Developing

Run

```
docker-compose build app_dev
```

Up it

```
docker-compose up app_dev
```

Find the docker pid with `docker ps` and attach to it via `docker attach $pid`. This should drop you in a shell.

Run:

```
swift run --enable-test-discovery Run serve -b 0.0.0.0
```

Navigate in your browser to `localhost:8080`
