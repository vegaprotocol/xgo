# Go cross compiler (xgo): Go 1.13.15
# Copyright (c) 2019 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM vegaprotocol/xgo:base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11315

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.13.15.linux-amd64.tar.gz   && \
  export ROOT_DIST_SHA=01cc3ddf6273900eba3e2bf311238828b7168b822bb57a9ccab4d7aa2acd6028 && \
  \
  $BOOTSTRAP_PURE
