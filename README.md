MVS 3.8j - GLIBC 2.39 Compatible Build

Fork of MVS 3.8j modified to work with GLIBC 2.39+ (Ubuntu 24.04, Linux Mint 22, and newer distributions).

This fixes the common "GLIBC_2.38 not found" error that prevents the original Docker image from running on modern Linux systems.

I hope it can help someone facing the same compatibility issues! 😁

## What's Changed
- Rebuilt Hercules for GLIBC 2.39 compatibility
- Updated base Docker image to Ubuntu 24.04
- All original MVS 3.8j functionality preserved

# How to load with docker

This will load the image

``` bash
docker load -i mvsce-glibc-fix.tar
```


