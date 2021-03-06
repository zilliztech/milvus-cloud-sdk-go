## Milvus Go SDK

Go SDK for [Milvus](https://github.com/milvus-io/milvus). To contribute code to this project, please read our [contribution guidelines](https://github.com/milvus-io/milvus/blob/master/CONTRIBUTING.md) first.

|Milvus version| Recommended Go SDK version |
|:-----:|:-----:|
| experimental | 0.5.1|
| 0.10.6 | 0.4.6|
| 0.10.5 | 0.4.5|
| 0.10.4 | 0.4.4|
| 0.10.3 | 0.4.4|
| 0.10.2 | 0.4.4|
| 0.10.1 | 0.4.3|
| 0.10.0 | 0.4.2|
| 0.9.1 | 0.4.1|
| 0.9.0 | 0.4.0|
| 0.8.0 | 0.3.0|
| 0.7.1 | 0.2.0|
| 0.7.0 | 0.1.0|

### Getting started

#### Prerequisites

Go 1.12 or higher

#### Install Milvus Go SDK

1. Use `go get` to install the latest version of the Milvus Go SDK and dependencies:

   ```shell
   go get -u github.com/zilliztech/milvus-cloud-sdk-go/milvus
   ```

2. Include the Milvus Go SDK in your application:

   ```shell
   import "github.com/zilliztech/milvus-cloud-sdk-go/milvus"
   ```

#### Try an example

```shell
cd [milvus-cloud-sdk-go root path]/examples
go run MilvusClientExample.go
```

### API Documentation

Refer to [https://godoc.org/github.com/zilliztech/milvus-cloud-sdk-go/milvus](https://godoc.org/github.com/zilliztech/milvus-cloud-sdk-go/milvus) for the GO SDK API documentation.

### Code format

The Go source code is formatted using gofmt and golint.
