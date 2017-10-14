# CPP
## 1.基础知识
- 变量的初始化：直接初始化（`int x(12) `）和复制初始化（` int x = 12 `）；
- 命名空间：使用命名空间(`using namespace NAME`)，定义命名空间（`namespace NAME`）；
- 引用：就是变量的别名、外号；必须绑定到具体的对象（变量）才有意义；
- c++函数新特性：默认参数，函数重载，内联函数（inline）
- 内存申请：**申请和释放的方式要对应**
``` c++
    // 申请一个类型的内存
    int *a = new int;
    // 检查申请是否成功
    if(NULL == a){
    
    }
    delete a;
    // 申请一块内存
    int *b = new int[10];
    delete []b ;
```
- 