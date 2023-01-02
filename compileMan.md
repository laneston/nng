# 交叉编译

## cmake

1. 静态库
```
cmake .. -DCMAKE_TOOLCHAIN_FILE=../toolchain_mtk.cmake -DCMAKE_INSTALL_PREFIX=../__install -DCMAKE_SYSTEM_NAME="Linux" 
```
2. 动态库
```
cmake .. -DCMAKE_TOOLCHAIN_FILE=../toolchain_mtk.cmake -DCMAKE_INSTALL_PREFIX=../__install -DCMAKE_SYSTEM_NAME="Linux" -DBUILD_SHARED_LIBS=ON
```

## make

```
make && make install
```