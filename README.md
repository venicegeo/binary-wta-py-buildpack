# WTA-py Binary Buildpack

This buildpack contains binaries of the bfalg_WTA implementation (available at https://github.com/venicegeo/bfalg_WTA).  For more details on binary buildpacks, please see the README-BUILDPACK.md file, found in this directory.  The actual OSSIM code used by this buildpack is stored in the ndwi-py.zip file in the vendor directory.

The simplest way to update this buildpack to the latest bfalg_WTA build:
- make sure that you've pulled the latest version of this buildpack.
- navigate to binary-wta-py-buildpack/vendor in a non-macintosh command-line interface with docker installed (macs have a known docker issue that causes errors)
- run `docker-compose build`
- run `docker-compose run package`
- commit and push the result.


## Reporting Issues

To report an issue with the buildpack, open an issue on this GitHub repo.
