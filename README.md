# rpi-rust-compiler
Docker container to cross compile rust program for raspberry pi

To use:

```bash
docker run --rm -it -v `pwd`:/home/cross/project hourd/rpi-rust-compiler build --release
```

This will product a source binary in the target directory.
