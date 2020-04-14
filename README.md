# Continuously Deploying Django to DigitalOcean with Docker and GitHub Actions

Configure GitHub Actions to continuously deploy a Django and Docker application to DigitalOcean.

## Want to learn how to build this?

Check out the [post](https://testdriven.io/blog/deploying-django-to-digitalocean-with-docker-and-github-actions/).

## Want to use this project?

### Development

Run locally:

```sh
$ docker-compose up -d --build
```

Verify [http://localhost:8000/](http://localhost:8000/) works as expected:

```json
{
  "hello": "world"
}
```

### CI and Production

See the blog [post](https://testdriven.io/blog/deploying-django-to-digitalocean-with-docker-and-github-actions/).
