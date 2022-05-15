# go-libxml2

This repository forked from [lestrrat-go/libxml2](https://github.com/lestrrat-go/libxml2) but statically link with
libxml2 and it's dependencies (like libicu, liblzma, libz etc).

Static link with libxml2 only be available for linux platform. For macOS(darwin) platform, go-libxml2 still need libxml2
dynamic lib which can ben installed by `brew install libxml2`