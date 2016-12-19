# ios-tensorflow-lib
Tensorflow compiled library

This repo contains link to tensorflow static library for iOS.

## how to use this repo

1. download from [Dropbox](https://www.dropbox.com/sh/n7w73hj8upvyfmn/AADw__tZwuUIeCIqJIvISf9ga?dl=0) a folder lib.
2. folder contains 2 files
  - lib/iphone/libtensorflow-core.a for architectures `armv7` `armv7s` and `arm64`
  - lib/simulator/libtensorflow-core.a for `i386` and `x86_64`
3. include those 2 folders from 2nd step to your project's `Library Search Paths`
4. How to setup rest of your iOS project is described in [tensorflow original repo](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/ios_examples/)
