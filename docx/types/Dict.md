# Dict

字典是另一种可变容器模型，且可存储任意类型对象。

* 键(key)必须是唯一的，可以用数字，字符串或元组充当，而用列表就不行。

* 同一个键出现两次，最后出现的会更新前一个的值。

## 常用方式

字典的每个键值 `key:value` 对用冒号`:`分割，每个键值对之间用逗号`,`分割，整个字典包括在花括号 `{}` 中 ,格式如下所示：

````python

tel = {'jack': 4098, 'sape': 4139}
````