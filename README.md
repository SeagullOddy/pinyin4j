pinyin4j
========

http://sourceforge.net/projects/pinyin4j 的复制版本。

### Download ###

1. 下载 jar 文件，放到项目的 lib 文件中；

2. 通过 maven 或 gradle 添加依赖（具体方法可以百度“maven/gradle 添加本地依赖”）。

### QQ Group ###

QQ群：479540440

### 多音字识别 ###

在pinyin4j的基础上添加了多音字识别，带近一万个多音词，但是这远远不够，所以用户可设置外挂词库

### 外挂多音词库 ###

用户配置的外挂词库会覆盖系统中相同词的读音,可用于纠错

配置方式很简单,只需要配置路径即可

```
MultiPinyinConfig.multiPinyinPath="/Users/yiboliu/my_multi_pinyin.txt"
```

格式同系统的多音词库,如:

```
吸血鬼日记 (xi1,xue4,gui3,ri4,ji4)
```