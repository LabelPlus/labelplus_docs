# 常见问题列表

## **提示缺少.NET Framework**

LabelPlus v1.2.4之前版本请安装[.NET Framework 3.5 Client Profile](http://www.microsoft.com/zh-cn/download/details.aspx?id=14037)，之后的版本请安装[.NET Framework 4 Client Profile](https://www.microsoft.com/zh-CN/download/details.aspx?id=24872)

## **提示“Read "labelplus\_config.xml" Error!”**  

****检查配置文件是否存在，确保其书写格式正确（参照labelplus\_config\_example.xml）。

## **想要用PS脚本作其他用途, 希望了解翻译文本的格式**

请参考[github中的一条issue](https://github.com/LabelPlus/PS-Script/issues/27)

## **PS脚本工作不正常**

| 异常 | 排障方法 |
| :--- | :--- |
| 执行过程中提示“错误8000: 无法打开文件” | 确认PS是否能打开该文件，如果无法打开，请确认图片文件名后缀是否与其实际格式相匹配 |
| 执行过程中出现莫名其妙的错误 | 尝试重置PS首选项（具体方法见注1） |
| 点击“导入”后，莫名其妙地弹出了“打开文件”的窗口 | PS CC 2017开始出现的问题，原因不明，但可以通过以下方式解决：1. 用 "文件-脚本-浏览" 的方式执行脚本；2. 把脚本放到PS安装目录下的"Presets\Scripts"文件夹里，通过“文件-脚本”菜单执行脚本（详见本文档“快速上手”-"嵌字"部分） |
| 导入时提示error: xxx open fail failed | 1. 检查图片文件名是否正确，常见的是后缀名错误 2. 检查图片路径是否正确，图片默认存放在翻译文本同级目录，更换路径需要手动设置 3. 手动在Photoshop中打开这个图片文件，如果打开失败，在MacOS下可以在命令行下使用file命令查看这个文件的真实格式，修改后缀名可以让PS正确处理图片 |

若问题还没能解决请依次尝试：

1. 检查翻译文本文件格式
2. 获取[最新的PS脚本](https://github.com/LabelPlus/PS-Script/releases)
3. 重置Photoshop首选项（具体方法见注1）
4. 使用完整版Photoshop
5. 与[作者](https://github.com/noodlefighter)取得联系

注1: 重置首选项的方法是，编辑菜单 - 首选项 - 常规，点击“在退出时重置首选项”按钮

## 我是MacOS用户, 如何使用LabelPlus

目前MacOS无法使用LabelPlus但是可以使用PS导入脚本, 它是跨平台的.

同时, [LabelPlus的Web版](https://moeflow.com)也是一个可用的替代.

## 常见问题列表里没有我遇到的问题/我有更好的idea

请在Github上发Issue: [LabelPlus相关](https://github.com/LabelPlus/LabelPlus/issues) [PS脚本相关](https://github.com/LabelPlus/PS-Script), 或者直接发邮件\(noodlefighter\#gmail.com\)与我取得联系.

