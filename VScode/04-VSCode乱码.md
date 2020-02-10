# VSCode中Output输出乱码

安装Code Runner插件，出现output中输出乱码

## Python乱码

1、方法一

在每个python文件前添加如下内容

```python
import io
import sys
#改变标准输出的默认编码
sys.stdout=io.TextIOWrapper(sys.stdout.buffer,encoding='utf8')
```



## Java乱码