md2bb
=====

Convert the Markdown guide files to BBCode ones
-----------------------------------------------
### with Docker
1. [Install Docker](https://docs.docker.com/installation/#installation)
2. Pull the image containing the runtime environment: `docker pull olbat/ws-strategies`
3. Run the script: `docker run -v $(pwd):/src olbat/ws-strategies`

### without Docker
1. [Install Ruby runtime environment](https://www.ruby-lang.org/en/documentation/installation/)
2. Run: `for f in */*.md; do ./md2bb < $f > ${f%.md}.bb; done`
