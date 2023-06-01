# Go-Hello-HuangWending
Go语言打印Hello,HuangWending程序
package main：这行代码定义了一个名为main的包。在Go语言中，main包是可执行程序的入口包。

import "fmt"：这行代码导入了fmt包，该包提供了格式化输入输出的函数。

func main() { ... }：这是程序的入口函数。在Go语言中，每个可执行程序必须包含一个名为main的入口函数，它在程序启动时被自动调用。

name := "HuangWending"：这行代码声明了一个名为name的变量，并将字符串"HuangWending"赋值给它。在Go语言中，使用:=进行短变量声明，可以同时声明和初始化变量。

fmt.Printf("Hello, %s\n", name)：这行代码使用fmt.Printf函数打印出一个问候语。Printf函数是fmt包中的一个函数，用于格式化输出。在这里，我们使用%s作为占位符，表示字符串类型的参数，并使用name变量的值替换占位符。
在控制台打印出"Hello, HuangWending"。我们通过声明一个变量来存储名字，然后使用fmt.Printf函数进行格式化输出，将问候黄文定的字符串与名字进行拼接，并输出到控制台。
