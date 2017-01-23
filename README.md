[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/action_profiler.svg)](https://hub.docker.com/r/rubygem/action_profiler/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/action_profiler.svg)](https://hub.docker.com/r/rubygem/action_profiler/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/action_profiler.svg)](https://hub.docker.com/r/rubygem/action_profiler/)
[![Gem Downloads](https://img.shields.io/gem/dt/action_profiler.svg)](https://rubygems.org/gems/action_profiler/)
# action_profiler

Auto-Generated Docker image for action_profiler to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/action_profiler`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/action_profiler`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/action_profiler`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/action_profiler/)
