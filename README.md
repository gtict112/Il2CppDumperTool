# Il2CppDumperTool
该脚本用来批量断点lil2cpp.so的函数
<pre>
1. dps.py

使用的python3版本，主要用来为Il2CppDumper生成的script.json提供一个关键字搜索，并转换为地址与名称对应关系，便于bpoints.js使用

2. bpoints.js

frida使用的js脚本，用到dlopen来获得加载时机，并注入断点
</pre>

###### python脚本的使用
![1.png](https://github.com/axhlzy/Il2CppDumperTool/blob/master/imgs/1.png "bpoints.js")
###### 这里举例的libmain.so，其他也一样
![2.png](https://github.com/axhlzy/Il2CppDumperTool/blob/master/imgs/2.png "dps.py")
