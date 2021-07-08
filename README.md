# heroku-buildpack-apt

This buildpack adds support for apt-based dependencies during both compile and runtime.

## Install

```bash
# Add the buildpack
heroku buildpacks:add --index 1 https://github.com/thatcleanlife/heroku-buildpack-apt.git

# Deploy
git push heroku master
```

## Aptfile

Include a list of apt package names to be installed in a file named `Aptfile`:

```bash
libssl1.0.0
```
