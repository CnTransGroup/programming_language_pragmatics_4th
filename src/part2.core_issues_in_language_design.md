在第一部分的基础上，我们现在来讨论大多数编程语言核心的问题：控制流，数据类型，以及控制和数据的抽象。

第6章讨论控制流，包括 expression evaluation, sequencing, selection, iteration, and recursion. 很多时候我们看到设计决策反映了对于互补或者竞争策略概念和效率上的权衡。引用和值的区别，提前或者懒惰计算问题会在后续章节反复出现。

接下来两章讨论类型。第7章包括类型系统和类型检查，包括等效型，兼容性和类型推断等概念。还讨论了显式和隐式形式的参数多态。第8章介绍了 compsite type 的最新研究，包括 records, variants, arrays, strings, sets, pointers, lists, files。指针部分介绍了垃圾收集技术。

控制和数据都可以抽象，即复杂性隐藏在简单以及定义明确的接口之后的过程。控制抽象是第9章的内容。subroutines 是最常见的控制抽象，但是我们也要考虑 exception 和 coroutine，然后简单回顾第6章介绍的 continuations and iterators。subroutines 主要包括调用顺序和参数传递机制。

第10章回到数据抽象。很多现代编程语言是面向对象的，通过封装机制，继承，和方法的动态分发（子类型多态）。我们对于面向对象编程语言的讨论主要包括构造器，访问控制，范型，闭包，以及 mix-in 和多继承。