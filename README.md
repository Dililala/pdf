malice-pdf
==========

[![Circle CI](https://circleci.com/gh/maliceio/malice-pdf.png?style=shield)](https://circleci.com/gh/maliceio/malice-pdf) [![License](http://img.shields.io/:license-mit-blue.svg)](http://doge.mit-license.org) [![Docker Stars](https://img.shields.io/docker/stars/malice/pdf.svg)](https://hub.docker.com/r/malice/pdf/) [![Docker Pulls](https://img.shields.io/docker/pulls/malice/pdf.svg)](https://hub.docker.com/r/malice/pdf/) [![Docker Image](https://img.shields.io/badge/docker image-44.9 MB-blue.svg)](https://hub.docker.com/r/malice/pdf/)

Malice PDF Plugin

This repository contains a **Dockerfile** of **malice/pdf** for [Docker](https://www.docker.io/)'s [trusted build](https://index.docker.io/u/malice/pdf/) published to the public [DockerHub](https://index.docker.io/).

### Dependencies

-	[malice/alpine](https://hub.docker.com/r/malice/alpine/)

### Installation

1.	Install [Docker](https://www.docker.io/).
2.	Download [trusted build](https://hub.docker.com/r/malice/pdf/) from public [DockerHub](https://hub.docker.com): `docker pull malice/pdf`

### Usage

```
docker run --rm malice/pdf PDFFILE
```

```bash

```

This will output to stdout and POST to malice results API webhook endpoint.

### Sample Output **sandbox** JSON:

```json
{
  "pdf": {
  }
}
```

### Sample Output **sandbox** (Markdown Table):

---

#### pdf

---

Documentation
-------------

-	[To write results to ElasticSearch](https://github.com/maliceio/malice-pdf/blob/master/docs/elasticsearch.md)
-	[To create a PDF scan micro-service](https://github.com/maliceio/malice-pdf/blob/master/docs/web.md)
-	[To post results to a webhook](https://github.com/maliceio/malice-pdf/blob/master/docs/callback.md)

### Issues

Find a bug? Want more features? Find something missing in the documentation? Let me know! Please don't hesitate to [file an issue](https://github.com/maliceio/malice-pdf/issues/new)

### CHANGELOG

See [`CHANGELOG.md`](https://github.com/maliceio/malice-pdf/blob/master/CHANGELOG.md)

### Contributing

[See all contributors on GitHub](https://github.com/maliceio/malice-pdf/graphs/contributors).

Please update the [CHANGELOG.md](https://github.com/maliceio/malice-pdf/blob/master/CHANGELOG)

### Credits

Heavily (if not entirely) influenced by the [viper PDF module](https://github.com/viper-framework/viper/blob/master/viper/modules/pdf.py)

### License

MIT Copyright (c) 2016-2017 **blacktop**
