# 小说下载器 README

这是一个用于下载小说的Python应用程序。它提供了两个不同的书源，允许用户输入小说名称并下载小说内容。以下是有关该应用程序的详细信息和使用说明。

## 功能特点

- 提供两个不同的书源，以便用户选择。
- 允许用户输入小说名称进行搜索。
- 显示小说的章节列表，供用户选择。
- 显示选定章节的内容。
- 可选项：将小说内容下载到当前目录下。

## 如何使用

1. 打开应用程序后，您将看到一个窗口，窗口标题为 "小说下载器"。
2. 在窗口中，您可以看到一个文本框，用于输入小说名称。
3. 如果要将小说内容下载到当前目录下，请勾选 "是否下载小说内容到当前目录下" 复选框。
4. 您可以选择两个不同的书源之一，点击对应的 "获取(书源1<推荐>)" 或 "获取(书源2)" 按钮，开始搜索小说。
5. 在搜索完成后，您将在左侧看到一个章节列表框，其中包含了小说的章节列表。
6. 选择一个章节，您将在右侧看到该章节的内容。

## 高级选项

- 如果选择了 "是否下载小说内容到当前目录下" 复选框，小说内容将下载到当前目录下的以小说名称命名的文件夹中。
- 您可以选择不同的书源来搜索小说，每个书源可能会提供不同的搜索结果和内容格式。

## 注意事项

- 搜索结果和小说内容的可用性可能会受到书源网站的变化和限制的影响。
- 在下载小说内容时，请注意版权问题，并确保您有权下载和使用该内容。

## 系统要求

- 本应用程序需要安装Python，以及以下Python库：requests、threading、tkinter、lxml、bs4、selenium。
- 对于使用Selenium的书源1，还需要安装Chrome浏览器和对应的Chrome驱动。

## 如何运行应用程序

1. 打开命令行终端。
2. 进入应用程序的文件夹。
3. 运行以下命令启动应用程序：

```
python 文件名.py
```

- 请确保将 "文件名.py" 替换为您的Python文件的实际名称。

## 致谢

感谢您使用小说下载器应用程序！如有任何问题或反馈，请联系应用程序的开发者。希望您享受阅读小说的过程！