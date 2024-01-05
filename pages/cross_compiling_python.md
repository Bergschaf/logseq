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
- turned off: blibz2 (oder so), lzma, blake2, nis
-
- CC=riscv64-unknown-linux-gnu-gcc ./configure --host x86-linux CFLAGS="-fPIC" --prefix=/home/bergschaf/riscv64_local/ --libdir=/home/bergschaf/riscv64_local/lib/ --includedir=/home/bergschaf/riscv64_local/include/
-
- --disable-test-modules
- to?install>lzma bzlib zlib
- # OP Dokument vlt
  https://devguide.python.org/developer-workflow/porting/index.html