PDF 批量转 EPUB
只用于非图片版，但转出来因为原文档大小产生了很多强制换行（比如右边一半都是空的）

https://zukuxi.github.io/pdf2epub-reflow/

功能

- 批量导入多个 PDF 文件。
- 调整文件顺序、删除文件。
- 提取文字型 PDF 中的正文并合并。
- 自动识别常见章节标题并生成 EPUB 目录。
- 支持按 PDF 保留独立章节。
- 清理部分多余空格及英文断词。
- 优化小说正文的段落与对话分段。
- 在浏览器中处理文件，无需上传到自己的服务器。

使用方法

1. 打开部署后的网页。
2. 选择一个或多个 PDF 文件。
3. 调整文件顺序并设置书名、作者。
4. 选择是否保留独立章节及自动识别章节标题。
5. 点击“开始转换并下载 EPUB”。

注意事项

- 本工具主要面向文字可选中、可复制的 PDF。
- 扫描图片型 PDF 不提供 OCR 识别。
- 文件较多或体积较大时，浏览器可能因内存不足而中断。建议关闭其他占用内存较大的程序，或分批转换。
- 转换结果取决于原 PDF 的文字布局、字体编码及排版结构，建议检查生成的 EPUB。

使用的第三方库

- "PDF.js" (https://github.com/mozilla/pdf.js)：读取和提取 PDF 文字。
- "JSZip" (https://github.com/Stuk/jszip)：生成 EPUB 所需的 ZIP 文件结构。

本项目使用上述第三方库时，应遵守各自适用的许可证。

许可证与来源

如果本项目基于其他开源项目修改，请在此处注明原项目名称、仓库链接、版权声明及适用许可证，并保留原项目要求的声明文件。

本项目的具体许可证及代码来源应以实际使用的代码和相关许可证文件为准。


PDF to EPUB Reflow

A browser-based tool for batch-converting text-based PDF files into EPUB ebooks, with text cleanup and automatic table-of-contents generation.

Features

- Batch import multiple PDF files.
- Reorder or remove files before conversion.
- Extract and combine text from multiple PDFs.
- Automatically detect common chapter headings and generate an EPUB table of contents.
- Optionally preserve separate sections for each source PDF.
- Clean up extra spaces and some line-break artifacts.
- Improve paragraph formatting and dialogue separation for novels.
- Process files locally in the browser without uploading them to a server.

Limitations

- Designed primarily for text-based PDFs with selectable and copyable text.
- Scanned, image-only PDFs are not supported by OCR.
- PDF page layouts may introduce unwanted line breaks. The tool attempts to clean up some formatting artifacts, but it cannot reliably reconstruct every original paragraph.
- Large batches may exceed available browser memory. Closing other applications or converting fewer files at a time may help.

Usage

1. Open the deployed GitHub Pages website.
2. Select one or more PDF files.
3. Arrange the files and set the book title and author.
4. Choose the chapter detection and section options.
5. Click Start Conversion and Download EPUB.

Third-Party Libraries

- "PDF.js" (https://github.com/mozilla/pdf.js) — PDF text extraction.
- "JSZip" (https://github.com/Stuk/jszip) — ZIP archive generation for EPUB files.

Please refer to the respective projects for their license terms and notices.

License and Attribution

If this project incorporates or modifies code from other projects, their copyright notices and applicable license requirements should be preserved. The applicable license for this project depends on its actual source code and included third-party components.
