# Go cross compiler (xgo): Go 1.13.13
# Copyright (c) 2019 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM vegaprotocol/xgo-base:latest

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11313

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.13.13.linux-amd64.tar.gz   && \
  export ROOT_DIST_SHA=0b8573c2335bebef53e819ab8d323456dc2b94838bebdbd8cc6623bb8a6d77b7 && \
  \
  $BOOTSTRAP_PURE
