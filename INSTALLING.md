## <a name="binary"></a>Binary Releases

Pre-built binaries (`nsqd`, `nsqlookupd`, `nsqadmin`, and all example apps) for linux and darwin are
available for download:

 * [nsq-0.2.19.darwin-amd64.tar.gz][0.2.19_darwin]
 * [nsq-0.2.19.linux-amd64.tar.gz][0.2.19_linux]
 * [nsq-0.2.18.darwin-amd64.tar.gz][0.2.18_darwin]
 * [nsq-0.2.18.linux-amd64.tar.gz][0.2.18_linux]
 * [nsq-0.2.17.darwin-amd64.tar.gz][0.2.17_darwin]
 * [nsq-0.2.17.linux-amd64.tar.gz][0.2.17_linux]
 * [nsq-0.2.16.darwin-amd64.tar.gz][0.2.16_darwin]
 * [nsq-0.2.16.linux-amd64.tar.gz][0.2.16_linux]
 * [nsq-0.2.15.darwin-amd64.tar.gz][0.2.15_darwin]
 * [nsq-0.2.15.linux-amd64.tar.gz][0.2.15_linux]

## Building From Source

### Pre-requisites

**golang** http://golang.org/doc/install - **version `1.0.3+` is required**

**hostpool** https://github.com/bitly/go-hostpool

**simplejson** https://github.com/bitly/go-simplejson

**assert** https://github.com/bmizerany/assert - required for running tests

Running ``go get`` as described in the _Compiling_ section will automatically download and install
simplejson and hostpool.

### Compiling

Use ``go get`` do download and compile the packages and binaries:

    $ go get github.com/bitly/nsq/...

Go package for building Go readers is ``github.com/bitly/nsq/nsq``.

Python module (for building Python readers)

    $ pip install pynsq

## Testing

    $ ./test.sh

## Running in Production

See [production notes](docs/production.md).

[0.2.19_darwin]: https://s3.amazonaws.com/bitly-downloads/nsq/nsq-0.2.19.darwin-amd64.tar.gz
[0.2.19_linux]: https://s3.amazonaws.com/bitly-downloads/nsq/nsq-0.2.19.linux-amd64.tar.gz
[0.2.18_darwin]: https://s3.amazonaws.com/bitly-downloads/nsq/nsq-0.2.18.darwin-amd64.tar.gz
[0.2.18_linux]: https://s3.amazonaws.com/bitly-downloads/nsq/nsq-0.2.18.linux-amd64.tar.gz
[0.2.17_darwin]: https://s3.amazonaws.com/bitly-downloads/nsq/nsq-0.2.17.darwin-amd64.tar.gz
[0.2.17_linux]: https://s3.amazonaws.com/bitly-downloads/nsq/nsq-0.2.17.linux-amd64.tar.gz
[0.2.16_darwin]: https://s3.amazonaws.com/bitly-downloads/nsq/nsq-0.2.16.darwin-amd64.tar.gz
[0.2.16_linux]: https://s3.amazonaws.com/bitly-downloads/nsq/nsq-0.2.16.linux-amd64.tar.gz
[0.2.15_darwin]: https://s3.amazonaws.com/bitly-downloads/nsq/nsq-0.2.15.darwin-amd64.tar.gz
[0.2.15_linux]: https://s3.amazonaws.com/bitly-downloads/nsq/nsq-0.2.15.linux-amd64.tar.gz
