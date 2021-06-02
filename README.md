# Dead Simple NodeJS Binary Installation

## Goals

1. Minimal Code
2. Minimal Dependencies
3. Fast

## FAQ

#### Is it fast?
 Yes.
 
 Unscientific proof:

 <img width="568" alt="its-fast" src="https://user-images.githubusercontent.com/42952/120550982-c6b0c280-c3b2-11eb-945c-7db35105abd4.png">

Example workflow:

```yaml
jobs:
  myjob:
    runs-on: ubuntu-latest
    steps:
      - uses: dreamcodez/dead-simple-nodejs@1
        with:
          NODE_VERSION: 16.1.0
          NODE_DISTRO: linux-x64 # optional
```
