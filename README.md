# # 7z



## 介绍

* 官网: https://sparanoid.com/lab/7z/7z.html

  

**7z** 是一种全新的压缩格式，它拥有极高的压缩比。

**7z** 格式的主要特征：

- 开放的结构
- 高压缩比
- 强大的 AES-256 加密
- 能够兼容任意压缩、转换、加密算法
- 最高支持 16000000000 GB 的文件压缩
- 以 Unicode 为标准的文件名
- 支持固实压缩
- 支持文件头压缩

**7z** 已公开了结构编辑功能，所以它可以支持任何一种新的压缩算法。到目前为止，下列压缩算法已被整合到了 **7z** 中：

| 压缩算法 | 备注                              |
| -------- | --------------------------------- |
| LZMA     | 改良与优化后的 LZ77 算法          |
| LZMA2    | 改良的 LZMA 算法                  |
| PPMD     | 基于 Dmitry Shkarin 的 PPMdH 算法 |
| BCJ      | 32 位 x86 可执行文件转换程序      |
| BCJ2     | 32 位 x86 可执行文件转换程序      |
| BZip2    | 标准 BWT 算法                     |
| Deflate  | 标准 LZ77-based 算法              |

**LZMA** 算法是 **7z** 格式的默认算法。**LZMA** 算法具有以下主要特征：

- 高压缩比
- 可变字典大小（最大 4 GB）
- 压缩速度：运行于 2 GHz 的处理器可达到 1 MB/秒
- 解压缩速度：运行于 2 GHz 的处理器可达到 10-20 MB/秒
- 较小的解压缩内存需求（取决于字典大小）
- 较小的解压缩代码：约 5 KB
- 支持 Pentium 4 的超线程（Hyper-Threading）技术及多处理器

**LZMA** 压缩算法非常适于应用程序的内嵌。**LZMA** 发布于 GNU LGPL 许可协议之下，如果您想使用 **LZMA** 的代码，您可以通过 [发送信息到 LZMA 开发部](https://sparanoid.com/lab/7z/support.html) 来咨询和自定义设计代码及制定开发者的使用许可。您也可以点击此处来查看有关 LZMA SDK 的信息： [LZMA SDK](https://sparanoid.com/lab/7z/sdk.html).

**7z** 是 [7-Zip](https://sparanoid.com/lab/7z/) 发布于 GNU LGPL 许可下的子程序。您可从 [下载页面](https://sparanoid.com/lab/7z/download.html) 下载 **7-Zip** 的源代码。

支持 **7z** 压缩格式的应用程序：WinRAR、PowerArchiver、TUGZip、IZArc。

相关链接：

- [Wikipedia 的 7z 页面](https://en.wikipedia.org/wiki/7z)



## 许可证



**7-Zip** 是一款 **开源** 的 **免费** 软件。大多数源代码都基于 **GNU LGPL** 许可协议下发布。部分代码基于 BSD 3 句条款（BSD 3-clause）许可协议发布。并且，部分代码受到了 unRAR 许可协议的限制。更多许可信息请查看：[7-Zip 许可](https://github.com/sparanoid/7z/blob/master/zh-cn/License.txt)。

您可以在任何一台计算机上使用 7-Zip ，包括用在商业用途的计算机。不对 7-Zip 进行注册或支付费用并不影响您的使用。

