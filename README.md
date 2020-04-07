# Team Docs

Team notes and documentation

## Requirements

* [Hugo](https://gohugo.io/)
* [Node.js](https://nodejs.org) / [npm](https://www.npmjs.com/)

## Setup Environment

```bash
git clone --recurse-submodules --depth 1 --jobs 2

# if already cloned or to update submodules
git submodule update --init --recursive --depth 1 --jobs 2

npm install -D
```

## Local with Drafts

```bash
# Build Static Files to _public
hugo -D

# Server Locally
hugo server -D
```
