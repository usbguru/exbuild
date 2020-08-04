**Example Build**

Building C++ Examples for Coral Development Board

build aarch64 files for c++ applications *classify_image* and *minimal*

usage:
make DOCKER_IMAGE=debian:stretch DOCKER_CPUS="aarch64" DOCKER_TARGETS="examples" docker-build

executables are placed here:
	out/aarch64/examples/


