# httpbin(1): HTTP Request & Response Service


A [Kenneth Reitz](http://kennethreitz.org/bitcoin) Project.

![ice cream](http://farm1.staticflickr.com/572/32514669683_4daf2ab7bc_k_d.jpg)

Run locally:
```sh
docker pull dockeryounger123/tools:httpbin
docker run -p 8099:8099 dockeryounger123/tools:httpbin
```

Or build image:
```sh
git clone https://github.com/young-0/httpbin.git
cd httpbin
docker build -t httpbin ./
```

See http://httpbin.org for more information.

## Officially Deployed at:

- http://httpbin.org
- https://httpbin.org
- https://hub.docker.com/r/kennethreitz/httpbin/


## SEE ALSO

- http://requestb.in
- http://python-requests.org
- https://grpcb.in/

## Build Status

[![Build Status](https://travis-ci.org/requests/httpbin.svg?branch=master)](https://travis-ci.org/requests/httpbin)
