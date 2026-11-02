# CET 诊断原型

四六级 710 分加权诊断的静态原型（单文件，无构建、无依赖）。

## 打开

双击 index.html，或直接部署到静态托管。

## 换皮（卖给不同机构）

源码顶部有 BRANDS 配置：

- 默认：index.html
- 换皮示例：index.html?brand=demo

改 
ame / sub / colors 即可。颜色会覆盖 CSS 变量（--brass / --brass-hi / --bg / --panel）。

## 数据

成绩记录只存在浏览器 localStorage，key 带品牌名，多机构互不干扰。
支持导出 / 导入 JSON（cet-diagnosis:v1:<brand> 结构），以后接后端可直接复用这个 schema。

## 作者

Hikelz · 2026