# docker-github-changelog-generator

This repository contains a collection of templated `Dockerfile` for image variants designed to build GitHub Changelogs using the [github-changelog-generator](https://github.com/azavea/github-changelog-generator).

## Usage

### Template Variables

- `GCG_VERSION` - Version number of the GitHub Changelog Generator

### Testing

An example of how to use `cibuild` to build and test an image:

```bash
$ CI=1 GCG_VERSION=v1.14.3 ./scripts/cibuild
```
