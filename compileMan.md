# 交叉编译

```
cmake .. -DCMAKE_TOOLCHAIN_FILE=../toolchain_mtk.cmake -DCMAKE_INSTALL_PREFIX=../__install -DCMAKE_SYSTEM_NAME="Linux"
make
make install
```