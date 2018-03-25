# Synology minimal package.

This package is depend on Synology toolkit framework.
This package is a template package, users can modify this package to generate their own packages.

Please setup the toolkit by following [pkgscripts-ng](https://github.com/SynologyOpenSource/pkgscripts-ng)

## Build package.
After setup toolkit environment, you can create minimalPkg by command:
```
pkgscripts-ng/PkgCreate.py [-p {platforms}] -c minimalPkg

e.g
pkgscripts-ng/PkgCreate.py -p 6281 -c minimalPkg # will generate package for platform 6281
pkgscripts-ng/PkgCreate.py -c minimalPkg # will generate package for all platforms in build_env
```

You can find generated packages in result_spk directory.
