[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/kindle-drm.svg)](https://hub.docker.com/r/rubygem/kindle-drm/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/kindle-drm.svg)](https://hub.docker.com/r/rubygem/kindle-drm/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/kindle-drm.svg)](https://hub.docker.com/r/rubygem/kindle-drm/)
[![Gem Downloads](https://img.shields.io/gem/dt/kindle-drm.svg)](https://rubygems.org/gems/kindle-drm/)
# kindle-drm

Auto-Generated Docker image for kindle-drm to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/kindle-drm`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/kindle-drm`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/kindle-drm`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/kindle-drm/)
