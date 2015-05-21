# ws-strategies

## Overview
This is a draft of a _French_ guide for Wildstar's Raids.

__Note__: this files are used to generate BBCode hosted on an external forum so this guide will probably not be updated.


## Convert the Markdown guide files to a BBCode one
### with Docker
1. [Install Docker](https://docs.docker.com/installation/#installation)
2. Pull the image containing the runtime environment: `docker pull olbat/ws-strategies`
3. Run the script: `docker run -v $(pwd):/src olbat/ws-strategies`

### without Docker
1. [Install Ruby runtime environment](https://www.ruby-lang.org/en/documentation/installation/)
2. Run: `for f in */*.md; do ./md2bb < $f > ${f%.md}.bb; done`
