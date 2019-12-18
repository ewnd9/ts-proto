# `ts-proto`

## Install

```sh
$ yarn install
$ ./pbjs.sh
```

## Local testing

```sh
$ yarn build
$ protoc --plugin=./build/protoc-gen-ts_proto --ts_proto_out=demo ./simple.proto
```
