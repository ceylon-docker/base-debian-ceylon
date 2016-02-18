# Base Debian image + Ceylon user

The following images/tags are available:

 - `java7` ([base-debian-ceylon/Dockerfile](https://github.com/ceylon-docker/base-debian-ceylon/blob/master/Dockerfile))

 Sets up a basic Debian image using `ceylon/base-debian` and adds to that a Ceylon user with `sudo` rights and an `/output` volume. Specifically meant as a base image for doing build-related tasks.
