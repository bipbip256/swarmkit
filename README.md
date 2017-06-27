# dockzen uses v1.13.0
$ git checkout bump_v1.13.0

# build
-   Go 1.6 or higher
-   A [working golang](https://golang.org/doc/code.html) environment
-   [Protobuf 3.x or higher] (https://developers.google.com/protocol-buffers/docs/downloads) to regenerate protocol buffer files (e.g. using `make generate`)

**Protobuf**
```sh
$ unzip protobuf-3.0.0-linux-x86_64.zip -d protobuf-3.0.0
$ cd protobuf-3.0.0
protobuf-3.0.0 $ sudo mv bin/protoc /usr/local/bin/
protobuf-3.0.0 $ sudo mv include/google /usr/local/include/
protobuf-3.0.0 $ protoc --version
libprotoc 3.0.0 
```
**swarmkit build**
```sh
$ make binaries
$ make generate
```
