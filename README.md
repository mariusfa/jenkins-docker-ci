# jenkins-docker-ci
Jenkins in docker building, testing all in docker

## Run an instance
```bash
docker run -d -v /var/run/docker.sock:/var/run/docker.sock -p 8085:8080 --name jenkins jenkins-marius
```
Starts a container that is accessible on `localhost:8085`. `docker logs -f jenkins` to see admin password.
