# 开发tampermonkey脚本

## 使用webpack开发

webpack可以打包css到js
只需要和平常一样使用webpack,把打包后的文件内容复制到你的脚本中即可使用

## 使用vite开发(不添加vue)

vite一般会把css和js分开

需要打包为iife模式,把js内容复制到tampermonkey,然后在jsdelivr引用打包后的css即可

## 使用vue-vite开发

见[说明](./monkey-vue/README.md)
