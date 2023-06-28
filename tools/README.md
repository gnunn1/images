### Introduction

An image with a bunch of common tools in it typically used in Tekton tasks

### Building

To build the image, you will need to source a binary copy of ksuid (https://github.com/segmentio/ksuid) and copy it into this directory. After that run:

```
podman build . -t quay.io/gnunn/tools:latest
```

To build the image
