#!/bin/bash

## Generate ts files from proto file using the below command in cmd

yarn proto-loader-gen-types --grpcLib=@grpc/grpc-js --outDir=proto/ proto/random.proto