# website
- create https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages
- build https://github.com/ObrienlabsDev/ObrienlabsDev.github.io/deployments/github-pages
- url https://obrienlabsdev.github.io

## Downloading

```
gsutil -m cp \
  "gs://obrienlabs-dev-website/error.html" \
  "gs://obrienlabs-dev-website/index.html" \
  "gs://obrienlabs-dev-website/styles.css" \
  .
```
## Uploading

## Local run via Docker container
```
docker run -d --rm --name apache -p 8080:80 -v ${PWD}:/usr/local/apache2/htdocs/ httpd:latest
```

