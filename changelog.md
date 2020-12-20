### Linux

```shell
curl -L https://github.com/jenkins-x/jx-gitops/releases/download/v0.0.497/jx-gitops-linux-amd64.tar.gz | tar xzv 
sudo mv jx-gitops /usr/local/bin
```

### macOS

```shell
curl -L  https://github.com/jenkins-x/jx-gitops/releases/download/v0.0.497/jx-gitops-darwin-amd64.tar.gz | tar xzv
sudo mv jx-gitops /usr/local/bin
```

## Changes

### Bug Fixes

* gitops variables to default a branch (James Strachan)
* ensure we have a branch name (James Strachan)
* upgrade deps (James Strachan)
* polish the log output (James Strachan)
