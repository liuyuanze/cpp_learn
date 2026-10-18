# cpp_learn

用于 C++ 基础学习的练习仓库，记录学习过程中编写的语法示例和练习代码。后续会随着学习进度，持续添加对应的 `.cpp` 文件。

## 当前练习

| 文件 | 练习内容 |
| --- | --- |
| [hello_world.cpp](hello_world.cpp) | 程序基本结构与 Hello World 输出 |
| [cout_learn.cpp](cout_learn.cpp) | `cout` 输出、`endl` 换行与算术表达式 |

## 后续学习内容

- 变量、常量与基本数据类型
- 运算符、表达式与输入输出
- 条件判断与循环
- 数组与字符串
- 函数、指针与引用
- 结构体、类与对象等基础知识

## 文件组织

每个 `.cpp` 文件围绕一个知识点或练习主题编写，使用能体现内容的文件名，便于查找和复习。包含 `main()` 的练习文件应单独编译运行。

仓库主要管理 C++ 源代码和学习说明。Visual Studio 解决方案、项目配置、本机缓存及编译产物通过 `.gitignore` 排除，可按需在本地创建。

## 编译运行

可使用支持 C++ 的编译器或开发环境。以安装了 GCC 的环境为例，编译并运行一个练习：

```sh
g++ hello_world.cpp -o hello_world
```

Windows PowerShell：

```powershell
.\hello_world.exe
```

Linux / macOS：

```sh
./hello_world
```

学习其他练习时，将编译命令中的源文件名和输出文件名替换为对应名称即可。
