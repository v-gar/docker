## OpenSSH client Docker image

This image provides a Debian-based image with an OpenSSH client.

Developed for usage in CI/CD systems like GitLab.

### Pulling

Pulling is very simple. Just install Docker and run

```bash
docker pull vgar/ssh-client:latest
```

for the latest (Debian) image.

### Running

Running is easy too. Just run

```bash
docker run -ti vgar/ssh-client
```

or

```bash
docker run vgar/ssh-client:latest ssh
```
