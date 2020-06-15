# Singularity XCrySDen

[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/4445)
[![GitHub License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

Singularity image for [XCrysDen](http://www.xcrysden.org/Download.html). It was built on top of the base Docker image [ubuntu](https://hub.docker.com/_/ubuntu).

## Build

You can build a local Singularity image named `xcrysden.sif` with:

```sh
sudo singularity build xcrysden.sif Singularity
```

## Deploy

Instead of building it yourself you can download the pre-built image from [Singularity Hub](https://www.singularity-hub.org) with:

```sh
singularity pull xcrysden.sif shub://OSC/sa_singularity_xcrysden
```

## Run

### Start XCrysDen
XCrysDen is started using the default run command:
```sh
singularity run xcrysden.sif
```
or as a native command
```sh
./xcrysden.sif
```


## License

The code is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
