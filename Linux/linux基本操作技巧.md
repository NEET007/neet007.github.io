﻿**linux基本操作技巧**

----------
1 切换用户：

```
# su -
# su - root
# su - 用户名
```

切忌：`# su`或`# su root`或`# su 用户名`（只切换用户名，而不改变相应环境变量）

----------
2 删除文件或目录：

```
# rm -f *
# rm -rf *
```
----------
3 *.tar.gz压缩包，解压缩：

```
# tar -xzf *.tar.gz -C 指定路径
```