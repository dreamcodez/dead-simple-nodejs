# Dead Simple NodeJS Binary Installation

## Goals

1. Minimal Code
2. Minimal Dependencies
3. Fast

Example workflow:

```yaml
jobs:
  myjob:
    runs-on: ubuntu-latest
    steps:
      - uses: dreamcodez/dead-simple-nodejs@v1
        with:
          NODE_VERSION: 16.1.0
          NODE_DISTRO: linux-x64 # optional
```
