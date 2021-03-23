# VS Code MarkDown Formatter

This repository will host a VS Code extension for formatting MarkDown documents
such that paragraphs are limited to 80/120 (as per configured rulers) characters
and are word-broken automatically to meet this limit. Non-block elements, such
as headings, links etc. will be left alone even if they exceed the line length
limit.

VS Code has a formatter API that can be used to implement this:
- https://code.visualstudio.com/blogs/2016/11/15/formatters-best-practices
- https://github.com/jrieken/vscode-formatter-sample
- https://code.visualstudio.com/api/references/vscode-api#registerDocumentFormattingEditProvider
