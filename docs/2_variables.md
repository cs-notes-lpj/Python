
```py
x = 2
y = x
print(y)
```

#### 以下两种写法等同

```py
# 写法一
x = 2
y = 3
z = 5
```

```py
# 写法二
x, y, z = 2, 3, 5 # 但是，大多数情况下，写法一比较好，因为变量名和其值的对应关系清晰，便于阅读代码
```

#### 变量命名的注意事项

1. 变量名只能以字母 或 下划线开头

2. 变量名只可包含 `字母`、`数字`、`下划线`

3. 变量名应有意义，方便人的阅读和理解

```py
py_population = 123123
py_area = 456456
py_density = py_population / py_area
print(py_density)
```

4. 变量名全部使用小写字母，并用下划线区分单词

```py
views_per_day # ✅
viewsPerDay   # ❌
```

5. 保留字 和 内置标识符不可用作变量名（下图是保留字的表格）

![image-20220422212525890](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/by-picgo/image-20220422212525890.png)
