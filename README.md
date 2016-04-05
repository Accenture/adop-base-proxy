#Supported tags and respective Dockerfile links

- [`0.1.0`, `0.1.0` (*0.1.0/Dockerfile*)](https://github.com/Accenture/adop-base-proxy/blob/master/Dockerfile.md)

# What is adop-base-proxy?

adop-base-proxy is a nginx docker image which can be extended and used to proxy adop stack. 

# How to use this image

The easiest way to run adop-base-proxy image is as follow:
```
docker run --name <your-container-name> -d -p 80:80 adop/adop-base-proxy:VERSION
```
after the above proxy will be available at: http://localhost:80

# License
Please view [licence information](https://github.com/Accenture/adop-base-proxy/blob/master/LICENSE.md) for the software contained on this image.

#Supported Docker versions

This image is officially supported on Docker version 1.10.
Support for older versions (down to 1.6) is provided on a best-effort basis.

# User feedback

## Documentation

## Issues
If you have any problems with or questions about this image, please contact us through a [GitHub issue](https://github.com/Accenture/adop-base-proxy/issues).

## Contribute
You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a [GitHub issue](https://github.com/Accenture/adop-base-proxy/issues), especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.
