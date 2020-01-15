# imagemagick-buildpack

This buildpack compiles ImageMagick from the source, allowing you to install
additional delegates. The compilation artifacts are cached for future builds.

### Installation

To add this buildpack to your application run:

```sh
heroku buildpacks:add https://github.com/digitalnomadx/imagemagick-buildpack --app APP_NAME
```

When the application is next pushed, the new buildpack will be used.
