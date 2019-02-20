1. 工厂模式的优势：
vins-mono定义了一个父类Camera，以及其多个子类CataCamera、PinholeCamera、EquidistantCamera、ScaramuzzaCamera，假设不使用工厂模式，当使用不同的camera时，需要在程序代码中修改实例化camera的代码。

2. 使用范围：
根据第一条可知，在不同的情况下需要使用不同的子类，此时可以使用工厂模式。

3. 工厂模式类型：
a. 简单工厂模式：只需要一个工厂类，子类的实例化在工厂类的函数中实现，使用较多。
b. 工厂方法模式
c. 抽象工厂模式