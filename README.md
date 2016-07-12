# r-shiny-cf-demo

This project contains working example of deploying R Shiny to Cloud Foundry.
The code contains originals adapted from:
- https://github.com/alexkago/insurance_demo
- https://hub.jazz.net/git/elinaj/R.on.Bluemix

## Usage
```
$ cf set-health-check r-shiny-cf-demo none
$ cf push r-prototype -b https://github.com/chinling/cf-buildpack-r
```

Note that health check must be turned off, otherwise the push would not be
successful due to timeout

## Miscellaneous
- Instruction on building R from source
-- http://kbroman.org/pkg_primer/pages/build.html

- Instruction on how to build a R binary for CF buildpack
-- https://github.com/chinling/r-buildpack-binary

