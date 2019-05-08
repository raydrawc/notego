# Go 基础

## 基础结构
```golang
// 当前程序的包名
package main

// 导入其他包
import . "fmt"  // 缺失调用
import fmt2 "fmt" //  fmt取别名为fmt2

// 常量定义
const PI = 3.14

// 全局变量的声明和赋值
var name = "gopher"

// 一般类型声明
type newType int

// 结构的声明
type gopher struct{}

// 接口的声明
type golang interface{}

// 由main函数作为程序入口点启动
func main() {
    Println("Hello World!")
}
```
GO 是通过 `package` 组织程序结构  
只有`package`名称为 `main` 的包  可以包含 `main`函数  
一个可执行程序有且仅有一个`main`包  

## 数据类型
### Boolean 布尔型
只能是true or false 
eg: var b bool = true

### number
* int int8 int16 int32 int64
* uint uint8 uint16 uint32 uint64
* 
* float32
* float64
* 复数
位运算采用补码

### string 
UTF-8 编码unicode 

### 派生类型
* 指针 pointer
* 数组 array
* 结构化类型 struct
* channel 类型
* 函数类型  fun 
* 切片类型
* 接口类型 interface
* Map 类型