# r-shiny-cf-demo

This project contains working example of deploying R Shiny to Cloud Foundry.
The code contains originals adapted from:
- https://github.com/alexkago/insurance_demo
- https://hub.jazz.net/git/elinaj/R.on.Bluemix

## Usage
```
$ cf push r-prototype -b https://github.com/chinling/cf-buildpack-r
$ cf set-health-check r-prototype none
```

## Miscellaneous
- Instruction on building R from source
-- http://kbroman.org/pkg_primer/pages/build.html

- Instruction on how to build a R binary for CF buildpack
-- https://github.com/chinling/r-buildpack-binary

