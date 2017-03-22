| [UW-Hydro/bmorph](https://github.com/UW-Hydro/bmorph) | [![Build status](https://travis-ci.org/UW-Hydro/bmorph.svg?branch=master)](https://travis-ci.org/UW-Hydro/bmorph) |
|----|----|

# bmorph
Bias correction for streamflow time series

Install by running
`python setup.py install`
in the top level directory

`./scripts/bmorph_tip304` contains an implementation of the method for the
TIP304 project. The script can be run as:

`bmorph_tip304 --cfg <configuration file> --verbose`

There is a sample configuration file in `./config`
