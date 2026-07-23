# 任务一 完整版开源项目 README.md 框架
### Markdown-Learn 学习仓库
- [![License](https://img.shields.io/badge/license-MIT-blue.svg)]()
- [![Version](https://img.shields.io/badge/version-v1.0.0-green.svg)]()
- [![GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)]()
## 项目简介
- 仅为新手学习`markdown`语法，遵循开源项目 `README` 标准结构，覆盖标题、列表、代码块、引用等基础元素，作为学习模板使用[^1]

## 环境要求
- 编辑器：`VS Code`
- 文件格式：`.md`

## 安装步骤
1. 将文档保存至本地文件夹
2. 使用支持Markdown的编辑器打开
3. 开启实时预览功能查看渲染效果
4. 编完以后导出PDF或者HTML验证排版

## 代码示例
```python
# 主程序运行示例
def main():
    msg = "欢迎使用 HlProject"
    print(msg)

if __name__ == "__main__":
    main()
```

# 任务二 添加脚注（扩展）
[^1]: Markdown 最初由 John Gruber 在 2004 年设计，目标实现"易读、易写"。

# 任务三 列表与代码块缩进规范
### 操作步骤:
- 在有序列表中插入代码块：列表项下空一行，然后缩进八个空格或一个 Tab，再放置围栏代码块，确保代码块是列表的一部分。练习列表内包含多段文字、引用块等复杂情况。

各种不同语言的hello world程序
1. c#

         using System;
         namespace HelloWorld
         {
           class Program
           {
             static void Main(string[] args)
            {
           Console.WriteLine("Hello World!");
           }
         }
       }

2. java

       public class HelloWorld {
         public static void main(String[] args) {
           System.out.println("HelloWorld");
         }
       }

3. C语言
        
         #include <stdio.h> // Include standard   input-output library
        
         int main() {
         // Print message to console
         printf("Hello, World!\n");
         return 0; // Indicate successful program   termination
       }

4. java语言的特色

> 一次编写到处运行、面向对象、兼具安全性与跨平台特性的通用编译型编程语言。

1. 严格区分大小写，变量、关键字大小写不能混用
2. 所有语句以分号结尾，类和代码块大括号配对完整
3. 主程序入口固定为main方法，格式不可随意改动



