juicevm_gcc_embed_toolchains
============
build
```
git clone --recursive https://github.com/riscv/riscv-gnu-toolchain
cd riscv/riscv-gnu-toolchain
./configure --prefix=/mnt/ssd_prj/juicevm_gcc_embed_toolchains --with-arch=rv64ima --with-abi=lp64 --disable-linux --with-cmodel=medany
make -j
make install
```

email: juicemail@163.com
