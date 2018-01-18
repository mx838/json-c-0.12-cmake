
### Build instructions:

`json-c` GitHub repo: https://github.com/json-c/json-c

```sh
$ git clone https://github.com/json-c/json-c.git
$ cd json-c
$ sh autogen.sh
```

followed by

```sh
$ ./configure
$ make
$ make install
```

To build and run the test programs:

```sh
$ make check
```
