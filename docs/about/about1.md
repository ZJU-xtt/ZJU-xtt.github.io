## 第零步：打开ccnocc的博客找到他的write up

#### 最重要的一步

链接导航：[ccnocc的write up](https://zjuccnocc.github.io/BlogWriteup/Mkdocs使用Writeup/)

我会补充一点我这边不太一样的东西

## 第一步：环境配置

暂时分析应该是我之前电脑上因为装conda，把原本的py卸掉了，所以没办法进行终端命令，后面下一个最新版的python就好了，顺带一提，今天是2024.6.30，他六月份更新了3.12

在你的电脑上下一个py，并且将系统的环境变量配置到你的python.exe文件路径和Script的文件路径

```C
pip install mkdocs
```

然后cd到你所在的操作路径，其余一样

- 另外补充一下，那个项目名可以随便命名，反正有TAB大法

- 然后一步步配置下来就一个地方出现了问题，就是我直接赋值cc的配置文件后发现会有报错，然后我把报错给了gpt，他告诉我language不能是chinese，改为zh后就好了
