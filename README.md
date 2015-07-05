![logo](https://i.imgur.com/qKqJ2pc.png)
# elastichoney
A Simple Elasticsearch Honeypot

### About
Elastichoney is a simple elasticsearch honeypot designed to catch attackers exploiting RCE vulnerabilities in elasticsearch.

### Installation
Binary distributions for most major systems are provided in the [Releases](https://github.com/jordan-wright/elastichoney/releases).

### Usage
```
$ ./elastichoney -h
Usage of elastichoney:
  -config="config.json": Location of the configuration file
  -log="elastichoney.log": Location of the log file
  -verbose=false: Output verbose logging to STDOUT
```

See the [blog post](http://jordan-wright.github.io/blog/2015/03/23/introducing-elastichoney-an-elasticsearch-honeypot/) for more details.

### Docker
If you would like to compile and run elastichoney using [Docker](https://github.com/docker/docker) and [Docker Compose](https://github.com/docker/compose),
you can do so by running:
```
mkdir logs
docker-compose build
docker-compose up
```

### License
```
The MIT License (MIT)

Copyright (c) 2015 Jordan Wright

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
