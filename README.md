# Studip Connect website

## Local development
After running the following command a local instance of the website is available at [localhost:4000]
```
docker run --rm   --volume="$PWD:/srv/jekyll:Z"   -p 127.0.0.1:4000:4000   jekyll/jekyll:3.8   jekyll serve
```