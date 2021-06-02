# action-install-nodejs
dead simple nodejs binary installation


example workflow:

```yaml
jobs:
  myjob:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/dead-simple-nodejs@v1
        with:
          NODE_VERSION: 16.1.0
          NODE_DISTRO: linux-x64 # optional
      - uses: actions/checkout@v2
```
