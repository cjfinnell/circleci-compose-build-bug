# circleci-compose-build-bug
Recreating a CircleCI bug: failure to build via docker compose when using a docker executor

## The error

```
docker compose build

[+] Building 0.0s (0/0)                                                         
listing workers for Build: failed to list workers: Unavailable: connection error: desc = "transport: Error while dialing unable to upgrade to h2c, received 404"

Exited with code exit status 17
```
