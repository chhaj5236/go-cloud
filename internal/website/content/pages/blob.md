---
title: "Blob"
---

Blobs are a common abstraction for storing unstructured data on cloud storage
providers and accessing them via HTTP.

Package `blob` provides an easy and portable way to interact with blobs within a
storage location ("bucket"). It supports operations like reading and writing
blobs (using standard interfaces from the `io` package), deleting blobs, and
listing blobs in a bucket.

Top-level package documentation: https://godoc.org/gocloud.dev/blob

Supported providers:

* [AWS S3 blob](https://godoc.org/gocloud.dev/blob/s3blob)
* [GCS blob](https://godoc.org/gocloud.dev/blob/gcsblob)
* [Azure blob](https://godoc.org/gocloud.dev/blob/azureblob)
* [In-memory local blob](https://godoc.org/gocloud.dev/blob/memblob) - mainly
  useful for local testing
* [File local blob](https://godoc.org/gocloud.dev/blob/fileblob) - local blob
  implementation using the file system

Usage samples:

* [Tutorial
  sample](https://github.com/google/go-cloud/tree/master/samples/tutorial)
* [Guestbook
  sample](https://github.com/google/go-cloud/tree/master/samples/guestbook)
* [blob package examples](https://godoc.org/gocloud.dev/blob#pkg-examples)

