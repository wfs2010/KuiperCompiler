# KuiperCompiler
一个AI编译器的实现, A DIY deep learning compiler framework.

# ??
从0到1，实现一个类似TVM的编译器

起步阶段
1. 创建一个IR module 类，获得来自不同格式模型的计算图
2. 创建一个算子类， 作为IR module的成员变量，实现具体的算子实现
3. 创建 scheduer 类实现对算子实现进行变换，以适应不同的平台，通过一系列操作函数直接对算子实现做变换


first goal！
1. 对onnx模型进行解析
2. 实现基本的算子
3. 。。。。。。

# other
量化模块

支持dynamic shape

在算子的优化上考虑到一些软硬件的结合

引入MLIR的dialect conversion概念，

用户可以自己构建类似cuda的核函数的部分

。。。。


# reference
1. tensorflow
2. mhlo
3. XLAtfrt
4. torch-mlir
5. onnx-mlir
6. iree
7. circt
8. flang
9. polygeist