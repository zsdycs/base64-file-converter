# base64FileConverter

这是一个基于网页的文件转换工具，使用浏览器直接打开 index.html 即可使用。

提供两个功能：

1. 文件转 Base64 文本
   - 支持大文件分片处理
   - 显示转换进度
   - 自动将转换后的 Base64 文本保存为 txt 文件
2. Base64 文本转文件
   - 多分片文件同时处理
   - 无损还原原始文件
   - 显示转换进度
   - 自动下载还原后的文件

Base64 文件转换工具，支持大文件的分片转换为 Base64 编码的文本文件，

也可以将转换出来的 Base64 文本文件还原为原始文件。

采用 Web Worker 技术实现异步处理，确保大文件转换时不会阻塞界面，并提供实时的进度显示。
