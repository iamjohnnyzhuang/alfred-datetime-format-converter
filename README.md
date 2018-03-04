alfred-datetime-format-converter
================================

基于开源插件 [alfred-datetime-format-converter](https://github.com/mwaterfall/alfred-datetime-format-converter) 重写。

主要改进点：
1. 完全基于内置datetime模块实现,删除第三方依赖包,使插件更加轻量化
2. 支持本土化,原插件时区从UTC开始,不方便本土使用,重写后时区为本机使用时间对应时区