# Python知识点

[TOC]

## 一、注意点

`input` 方法接收到的所有数据都是字符串形式。可以通过int将字符串转换为数字类型。

```python
print("Welcome to use your first programme")
name = input("your name :")
age = int(input("your age :"))
sex = input("your sex :")

msg = '''
--------Personal Info --------
your name : %s
your age : %d
your sex : %s
-------------End--------------
''' %(name, age, sex)

print(msg)
if age > 20:
    print("you need to learn more")
else:
    print("Yes, you can pass")
```

