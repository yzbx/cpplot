# make error

```
$ make
[  8%] Building CXX object CMakeFiles/cpplot.dir/src/cpplot.cpp.o
In file included from /home/yzbx/git/cpplot/include/cpplot.hpp:23:0,
                 from /home/yzbx/git/cpplot/src/cpplot.cpp:12:
/home/yzbx/git/cpplot/include/cpplot_common.hpp:40:19: fatal error: gl2ps.h: 没有那个文件或目录
 #include "gl2ps.h"
                   ^
compilation terminated.
make[2]: *** [CMakeFiles/cpplot.dir/src/cpplot.cpp.o] 错误 1
make[1]: *** [CMakeFiles/cpplot.dir/all] 错误 2
make: *** [all] 错误 2
```
