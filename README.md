# kLua
Lua的自用增强版

## 修改内容
* 基于Lua 5.4
* 支持class对象，对类成员函数调用进行编译优化
```c
class A {
  function fa()
  end;
};
local a = new A;
a.fa();
```
* 支持switch、continue语法
  ```c
  switch x do
  case "1":
    break;
  case 2:
    break;
  else
    --todo
  end;
  ```
* 支持注释语法
  ```c
  //注释
  /*注释*/
  ```
* 支持自运算语法
  ```c
  i++;
  i--;
  i += x;
  i -= x;
  i *= y;
  i /= y;
  ```
  




