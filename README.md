***Modified from jkutner, added line in compile script to run "gu install R" so that Polyglot functionality of GraalVM included for Heroku Deployment***
# GraalVM Buildpack

This [buildpack](https://devcenter.heroku.com/articles/buildpacks) will install the [GraalVM](https://github.com/oracle/graal) Community Edition.

## Usage

This buildpack can be used with the [Heroku Java buildpack](https://github.com/heroku/heroku-buildpack-java/blob/master/bin/compile) to replace the default JDK by running:

```
$ heroku buildpacks:set jdk/graal
$ heroku buildpacks:add heroku/java
```

## License

MIT
