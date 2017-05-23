# golang-arm

This Docker image is based on the official image `golang` and contains   cross compiler for arm.



# Supported tags

* `1.8`
* `1.7`

# How to use this image

```dockerfile
FROM gridx/golang-arm:1.8

ENV CC arm-linux-gnueabi-gcc
ENV GOARCH arm

COPY . .
...
```

# Maintained by

[gridX GmbH, Germany](https://gridx.de/)
