# 常见问题列表

## **提示缺少.NET Framework**

运行至少需要.NET Framework 3.5 Client Win7以下系统需自行安装

[http://www.microsoft.com/zh-cn/download/details.aspx?id=14037](http://www.microsoft.com/zh-cn/download/details.aspx?id=14037)

## **提示“Read "labelplus\_config.xml" Error!”  **

**      
**检查配置文件是否存在，确保其书写格式正确（参照labelplus\_config\_example.xml）。

## **想要用PS脚本作其他用途, 希望了解翻译文本的格式**

请参考[github中的一条issue](https://github.com/LabelPlus/PS-Script/issues/27)

## **PS脚本工作不正常**

| 异常 | 排障方法 |
| :--- | :--- |
| 执行过程中提示“错误8000: 无法打开文件” | 确认PS是否能打开该文件，如果无法打开，请确认图片文件名后缀是否与其实际格式相匹配 |
| 点击“导入”后，莫名其妙地弹出了“打开文件”的窗口 | PS CC 2017开始出现的问题，原因不明，但可以通过以下方式解决：1. 用 "文件-脚本-浏览" 的方式执行脚本；2. 把脚本放到PS安装目录下的"Presets\Scripts"文件夹里，通过“文件-脚本”菜单执行脚本（详见本文档“快速上手”-"嵌字"部分） |



若问题还没能解决请依次尝试：

1. 检查翻译文本文件格式
2. 获取[最新的PS脚本](https://github.com/LabelPlus/PS-Script/releases)
3. 使用完整版PS
4. 与[作者](https://github.com/noodlefighter)取得联系

## 我是MacOS用户, 如何使用LabelPlus

目前MacOS无法使用LabelPlus但是可以使用PS导入脚本, 它是跨平台的.

同时, [LabelPlus的Web版](https://moetra.com)也是一个可用的替代.

## 常见问题列表里没有我遇到的问题/我有更好的idea

请在Github上发Issue: [LabelPlus相关](https://github.com/LabelPlus/LabelPlus/issues) [PS脚本相关](https://github.com/LabelPlus/PS-Script), 或者直接发邮件\(noodlefighter\#gmail.com\)与我取得联系.

