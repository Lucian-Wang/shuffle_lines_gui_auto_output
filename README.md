# 文本行随机打乱工具

使用 Python Tkinter 选择 UTF-8 文本文件，随机打乱全部行，在原文件目录生成 `原文件名_shuffled_时间戳.txt`。原文件保留，末尾缺少换行符的行会补上换行。

## 安装与运行

```bash
git clone https://github.com/Lucian-Wang/shuffle_lines_gui_auto_output.git
cd shuffle_lines_gui_auto_output
python shuffle_lines_gui_auto_output.py
```

需要 Python 3 和 Tkinter，其他依赖均为标准库。旧二进制已移除，请按源码运行或自行打包。

## 使用

点击“浏览”选择输入文件，再点击“开始打乱”。完成弹窗会显示输出文件的完整路径。当前界面通过文件选择输入，不提供粘贴文本或复制结果按钮。

## 许可说明

原 README 声明 MIT License；当前仓库未包含独立 LICENSE 文件。

## 维护与反馈

维护者：[Lucian](https://lucian.wang/) · 邮箱：im@lucian.wang · [问题反馈](https://github.com/Lucian-Wang/shuffle_lines_gui_auto_output/issues)
