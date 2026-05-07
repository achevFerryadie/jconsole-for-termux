[jconsole](https://code.jsoftware.com/wiki/Guides/jconsole) for Termux. This is a fork of [jsource](https://github.com/jsoftware/jsource) to build on Termux.

## Requirements

```sh
pkg install clang make
```

## Build

```sh
jplatform=raspberry j64x=j64 ./make2/build_libj.sh
jplatform=raspberry j64x=j64 ./make2/build_jconsole.sh
cp jlibrary/bin/profile.ijs bin/raspberry/j64/
```

The results will be in `/bin/raspberry/j64/`.

## Acknowledgement

1. I may have missed deleting irrelevant files from the `jsource` (such as sources for other platforms), or accidentally deleted important ones.
Please let me know or fix it yourself if you notice.
2. I'm not going to mantain this.
This was just a solution of my own problem and I want to share it in case someone has the same problem.
