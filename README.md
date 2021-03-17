# SUMMARY
Mini OS experiment. Runs on QEMU, build on Docker.


# NOTES
docker build buildenv -t my_mini_os-buildenv
docker run --rm -it -v $pwd:/root/env my_mini_os-buildenv
    ($pwd doesn't seem to work, replace with actual path)

make build-x86_64 (build project from docker container)
