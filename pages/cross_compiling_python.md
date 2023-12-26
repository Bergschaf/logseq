- #python
- args for ./configure
  --prefix=/home/bergschaf/riscv64_python/architecture_independent
  --exec-prefix=/home/bergschaf/riscv64_python/architecture_dependent
  --host=riscv64-unknown-linux-gnu
  CC=riscv64-unknown-linux-gnu-gcc
  LDFLAGS="-L/opt/riscv/lib/
  LIBS="-l:libc.a"
  --disable-ipv6
   config site dings https://unix.stackexchange.com/questions/342925/cross-compiling-python
- turned off: blibz2 (oder so), lzma, blake2