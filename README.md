# KuiperCompiler
一个AI编译器的实现, A DIY deep learning compiler framework.

# ??
从0到1，实现一个类似TVM的编译器

我觉得有必要实现一个量化的功能，先看看怎么写

1. 创建一个IR module 类，获得来自不同格式模型的计算图
2. 创建一个算子类， 作为IR module的成员变量，实现具体的算子实现
3. 创建 scheduer 类实现对算子实现进行变换，以适应不同的平台，通过一系列操作函数直接对算子实现做变换


first goal！
1. 对onnx模型进行解析
2. 实现基本的算子
3. 。。。。。。