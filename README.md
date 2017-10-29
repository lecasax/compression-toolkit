# Docker Compression Toolkit

A lightweight Ubuntu **docker** with toolkit for compressing and decompressing files.


### Toolkit
 - **tar**
 - **zip**
 - **gzip**
 - **p7zip-full**
 - **p7zip-rar**
 - **bzip2**
 - **xz-utils**
 - **lzma**
 - **pax**
 - **sharutils**
 - **unrar**
 - **kgb**


### Usage

#### Compress a file
```sh
docker run --rm -it -v $(pwd):$(pwd) compression-toolkit zip $(pwd)/file.zip $(pwd)/file.txt
```
#### Decompress a file
```sh
docker run --rm -it -v $(pwd):$(pwd) compression-toolkit unzip $(pwd)/file.zip
```
