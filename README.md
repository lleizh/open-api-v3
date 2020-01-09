---
tags: [swagger, stoplight]
---

open stoplight or use prism start mock server.

use prism

- `npm install -g @stoplight/prism-cli`

- `prism mock reference/hello.v1.yaml `

or

`docker run --init --rm -p 4010:4010 -v $(pwd):/tmp stoplight/prism:3 mock -h 0.0.0.0 "/tmp/reference/hello.v1.yaml"`

# open-api-v3
