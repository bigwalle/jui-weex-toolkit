# jui-weex-toolkit

> jui-weex-toolkit 是 配合 jui-weex 框架使用的命令行工具

# 命令行使用

## 安装

```bash
npm install -g jui-weex-toolkit
```

## 使用

```bash
jui-weex -v // 查看当前toolkit版本

jui-weex -h // 命令帮助信息

jui-weex create <projectName> [version] // 创建bui-weex示例工程，可以指定版本

jui-weex list // 显示可用的版本

jui-weex list-template // 显示模版工程里可用的模版

```

# API 使用

## 安装

```bash
npm install jui-weex-toolkit --save
```

## 使用

除了全局安装在命令行使用，你也可以在代码中调用 API 使用，例如

```js
const TemplateRelease = require('jui-weex-toolkit').TemplateRelease;
const templateRelease = new TemplateRelease('jui-weex', 'https://api.github.com/repos/welcome112s/jui-weex-template/releases');
// templateRelease.fetchRelease(...)
```
