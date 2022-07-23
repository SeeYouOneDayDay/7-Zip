# 更新日志



**LZMA 软件开发工具包**（以下简称 SDK）给开发客户提供文档、源代码以及几个使用 **LZMA** 压缩算法制作的应用程序的例子。

| 链接                                                         | 大小  | 日期       | 版本  | 描述                                              |
| ------------------------------------------------------------ | ----- | ---------- | ----- | ------------------------------------------------- |
| [下载](https://www.7-zip.org/a/lzma2200.7z) / [镜像下载](https://experiments-alicdn.sparanoid.net/7z/lzma2200.7z) | 1 MB  | 2022-06-15 | 22.00 | LZMA SDK C、C++、C#、Java 包含 Windows 二进制文件 |
| [下载](https://www.7-zip.org/a/lzma1900.7z) / [镜像下载](https://experiments-alicdn.sparanoid.net/7z/lzma1900.7z) | 1 MB  | 2019-02-21 | 19.00 |                                                   |
| [下载](https://www.7-zip.org/a/lzma1604.7z) / [镜像下载](https://experiments-alicdn.sparanoid.net/7z/lzma1604.7z) | 1 MB  | 2016-10-04 | 16.04 |                                                   |
| [下载](https://www.7-zip.org/a/lzma-specification.7z) / [镜像下载](https://experiments-alicdn.sparanoid.net/7z/lzma-specification.7z) | 12 KB | 2015-06-14 |       | LZMA 规范（草案）                                 |

注意：如果您使用 LZMA SDK 中的 XZ 代码，建议您从 15.05 beta 中升级到最新的 XZ 代码，新版本的 XZ 代码修复了一些 bug。

**工具包更新：**

- **21.07：**一些小改动和错误修复。
- **21.06：**修复了 LZMA 的编码函数。
- **21.03 beta：**LZMA 字典大小最大支持 4 GB。速度优化。
- **21.02 alpha：**支持 macOS 及 Linux。速度优化。
- **19.00：**加强 7z 压缩档案的加密强度。
- **18.06：**部分 LZMA/LZMA2 代码的速度优化。
- **18.05：**部分 LZMA/LZMA2 代码的速度优化。
- **18.01：**对 LZMA2/xz 多线程压缩代码进行部分改动。修复已知错误。
- **9.35：**修复已知错误，SDK 中新增 AES 源代码以及 SFX 模块。
- **9.20：**新增用于安装包的精简版 SFX 自释放模块。
- **9.11：**支持 PPMd。
- **9.04：**增加对 LZMA2 以及 XZ 的支持。
- **4.62：**修复小错误。LZMA SDK 隶属于 [公有领域](https://zh.wikipedia.org/wiki/公有领域)
- **4.58：**速度优化，为 LZMA 压缩提供了新的 ANSI-C 代码。
- **4.57：**速度优化，修复了一些小错误。
- **4.49：**完善 .7z ANSI-C 解码器。增加 C++ 的 .7z 压缩档案处理代码。

**LZMA** 是 **7-Zip** 程序中 [**7z 格式**](https://sparanoid.com/lab/7z/7z.html) 的默认压缩算法。**LZMA** 能提供给用户极高的压缩比及较快的压缩速度，它非常适合与应用程序集成。

**LZMA SDK** 包括：

- **LZMA** 编码器及解码器的 **C++** 源代码
- **.7z** 压缩与解压缩 **C++** 源代码（精简版）
- 兼容 **ANSI-C** 的 **LZMA / LZMA2 / XZ** 压缩及解压缩源代码
- 兼容 **ANSI-C** 的 **7z** 解压缩及相关例子的源代码
- **LZMA** 压缩及解压缩的 **C#** 源代码
- **LZMA** 压缩及解压缩的 **Java** 源代码
- **lzma.exe** 用于 .lzma 的压缩及解压缩
- **7zr.exe** 用于 7z 压缩包（7z.exe 的精简版）
- **SFX 模块** 可以用来创建自释放压缩包以及应用程序安装包

**ANSI-C LZMA** 解压缩代码是从原始的 C++ 源代码转换到 C。并简化和优化了代码的大小。但它依然和 **7-Zip** 的 **LZMA** 完全兼容。

**LZMA** 的主要特征：

- 压缩速度：在双核处理器上可以达到 2 MB/秒。
- 解压缩速度：
  - 在英特尔酷睿2 或 AMD 速龙 64 上可以达到 20-30 MB/秒。
  - 在 100 MHz ARM、MIPS、PowerPC 或其它精简指令集处理器上能达到 1-2MB/秒。
- 较小的解压缩内存需求：8-32 KB（依赖于字典大小）
- 较小的解压缩代码：2-8 KB

**LZMA** 解码器仅使用整数运算，可以在任何主流的 32 位处理器（或在一定条件下的 16 或处理器）下运行。

## 许可协议

**LZMA SDK** 隶属于 **公有领域**

## LZMA 相关链接

- [维基百科上的 LZMA 页面](https://zh.wikipedia.org/wiki/LZMA)（[英文](https://en.wikipedia.org/wiki/LZMA)）
- [面向 JAVA 独立开发者的 LZMA SDK 文档](https://sourceforge.net/projects/p7zip/)
- [面向 Pascal（Delphi、Kylix 以及 Freepascal）的 LZMA SDK 文档](http://www.birtles.org.uk/programming/)
- [PyLZMA: Python 绑定的 LZMA 算法](http://www.joachim-bauch.de/projects/python/pylzma/)
- [XZ 实用小工具 / LZMA 实用小工具](http://tukaani.org/xz/)
- [Java 中的 LZMA 压缩流](http://contrapunctus.net/league/haques/lzmajio/)
- [不同 CPU 上的 LZMA 基准测试](https://www.7-cpu.com/)