# 用到的内容记录
## 使用LFS各个语句的含义
```
    filter=lfs：使用 Git LFS 管理 .pkl 文件。
    diff=lfs：使用 LFS 的 diff 驱动程序，这通常意味着不会对二进制大文件进行详细比较。
    merge=lfs：使用 LFS 的 merge 驱动程序来处理合并，这对二进制大文件非常重要。
    -text：指示这些文件是二进制文件，而不是文本文件。
```