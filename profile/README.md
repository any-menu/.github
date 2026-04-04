# AnyMenu

## 介绍

- en
  - AnyMenu —— Powerful input method assistant / editor assistant
- zh
  - AnyMenu —— 一款强大的输入法助手/编辑器助手

这里会包含:

- AnyMenu 的跨平台App版本仓库
- AnyMenu 作为Obsidian/VScode等软件的插件版本仓库
- AnyMenu 的各种自定义词库、自定义脚本

## [AnyMenu](https://github.com/any-menu/any-menu/)

[any-menu](https://github.com/any-menu/any-menu/) 为 App 和插件版本所在仓库

## 插件开发模板

- 纯 js 模板: [dict_exampl](https://github.com/any-menu/any-menu/blob/main/store/dict_example/)。
  适用于简单的、功能单一的脚本。无需编译，修改快捷。但不利于复杂插件的开发
- ts 简单模板: [example-plugin-simple](https://github.com/any-menu/example-plugin-simple), 模板产物 Size: 1.04KB
- 带 Svelte 依赖的模板: [example-plugin-svelte](https://github.com/any-menu/example-plugin-svelte), 模板产物 Size: 39.1KB
- 带 Vue 依赖的模板: [example-plugin-vue](https://github.com/any-menu/example-plugin-vue), 模板产物 Size: 146.00KB
- 带 React 依赖的模板: [example-plugin-react](https://github.com/any-menu/example-plugin-react), 模板产物 Size: 253.57KB

> 大小仅供参考，其实在插件开发场景中，插件大小的变化并不是很敏感 (与网络加载不同)，选择你熟悉的技术栈即可
