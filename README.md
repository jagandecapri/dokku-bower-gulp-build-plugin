# dokku-bower-gulp-build

dokku-bower-gulp-build is a fork of [thrashr888/dokku-bower-grunt-build-plugin](https://github.com/thrashr888/dokku-bower-grunt-build-plugin)

dokku-bower-gulp-build is a plugin for [dokku][dokku] that runs `bower install` and `gulp build` in a `post-release-buildstep` hook.
This is mostly useful for single page apps that have an extra build step but you don't want to alter your buildpack.

## Installation

On your dokku server:
```sh
git clone https://github.com/jagandecapri/dokku-bower-gulp-build-plugin.git /var/lib/dokku/plugins/dokku-bower-gulp-build
```

All future deployments will run bower and gulp after a release.

[dokku]: https://github.com/progrium/dokku
