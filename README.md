# Ruby 学习指南

- 对象
  - 一切皆是对象
  - 实例变量
    - 查看实例变量 (instance_variables)
    - 添加实例变量 (@)
    - 专属实例变量 (instance_eval)
  - 方法
    - 查看方法 (methods)
    - 添加方法
- 类
  - 定义类 (class / Class.new)
  - 实例变量
    - attr_accessor
  - 实例方法
    - 查看实例方法 (instance_methods(false))
    - 添加实例方法
  - 类本身也是对象
    - 类方法
    - 类变量 (@ vs @@)
- 隐藏的元类
  - 逮捕元类
  - 查看实例方法
  - 添加实例方法
- 模块
  - include / extend
  - 钩子 (self.included(base))
- 作用域
  - 变量作用域
   - 局部变量作用域
   - 实例变量作用域
   - 全局变量作用域
   - 常量作用域
  - 方法作用域
    - 方法查找
- 代码块
  - 不是对象的代码块 (匿名参数)
  - 是对象的代码块 (匿名函数)
  - proc vs lambda
  - 穿透局部变量作用域
- 元编程
  - method_missing
  - 环绕别名 (alias_method)
