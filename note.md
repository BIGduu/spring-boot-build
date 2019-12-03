# spring 源代码阅读笔记

## spring boot初始化流程
![](.note_images/SpringApplication构造器.png)
### 其中最主要的的是getSpringFactoriesInstances方法
* 通过源码的解读我们知道了,Spring这里的命名原则是
   * getSpringFactoriesInstances => createSpringFactoriesInstances
   * 例子:
    ![](.note_images/getSpringFactoriesInstances方法的命名和实现.png)
   



