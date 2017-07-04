# docker-markdown-pdf

[![License](https://img.shields.io/github/license/uchida/docker-markdown-pdf.svg?maxAge=2592000)](https://tldrlegal.com/license/creative-commons-cc0-1.0-universal)
[![MicroBadger](https://images.microbadger.com/badges/image/auchida/markdown-pdf.svg)](http://microbadger.com/images/auchida/markdown-pdf)

markdown-pdf installed docker image to convert markdown to pdf, including Noto CJK fonts.

Docker image is available as [auchida/markdown-pdf](https://hub.docker.com/r/auchida/markdown-pdf/) in Docker Hub.

## Image tags

- `latest`

## Usage

```console
$ docker run -v $PWD:/opt/docs auchida/markdown-pdf markdown-pdf -o docs.pdf docs.md
```

see [README for markdown-pdf](https://github.com/alanshaw/markdown-pdf) for more information about `markdown-pdf`.

## License

Contents on this repository are dedicated to [![CC0 public domain](http://i.creativecommons.org/p/zero/1.0/80x15.png "CC0 public domain")](https://creativecommons.org/publicdomain/zero/1.0/).
No rights reserved.

License for distributed Docker images follows one of [Debian Project](https://www.debian.org/legal/licenses/), [NodeJS](https://github.com/nodejs/node/blob/master/LICENSE), [PhantomJS](https://github.com/ariya/phantomjs/blob/master/LICENSE.BSD) and [its dependencies](https://github.com/ariya/phantomjs/blob/master/third-party.txt), [Noto fonts](https://github.com/googlei18n/noto-cjk/blob/master/LICENSE), [markdown-pdf](https://github.com/alanshaw/markdown-pdf/blob/master/LICENCE) and its dependencies.
