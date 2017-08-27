# TAO Docker Image

Docker container for running the [TAO Testing](https://www.taotesting.com) platform.

## Summary

This is a TAO image based on the latest php-5 official image and uses the latest release from the [Official TAO Packages](http://www.taotesting.com/get-tao/official-tao-packages/), version 3.1 RC7.

This container contains only the php application and runs on port 9000. To build a full working application you should use [docker-tao-env](https://github.com/don-smith/docker-tao-env), which uses this image together with nginx and mysql images.
