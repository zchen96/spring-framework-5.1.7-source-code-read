 - IoC
    - [Spring IoC 特性](document/ioc/1.Spring%20IoC%20特性.md)
    - [BeanDefinition 初始化与注册](2.BeanDefinition%20初始化与注册.md)
    - [IoC 容器启动流程](document/ioc/3.IoC%20容器启动流程.md)
    - [Spring 事件发布机制原理分析](document/ioc/4.Spring%20事件发布机制原理分析.md)
    - [bean 创建流程分析](document/ioc/5.bean%20创建流程分析.md)
    - [getBean 流程分析](document/ioc/6.getBean%20流程分析.md)

 - AOP
    - [解析 aop 配置信息](document/aop/1.解析aop配置信息.md)
    - [aop 代理类入口分析](document/aop/2.AOP代理类入口分析.md)
    - [创建代理 bean](document/aop/3.创建代理bean.md)
    - [拦截器链执行流程](document/aop/4.拦截器链执行流程.md)

### IoC 导图

#### BeanDefinition 初始化与注册
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200327192621819.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2NvZGVqYXM=,size_16,color_FFFFFF,t_70)
#### IoC 启动流程
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200327192639571.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2NvZGVqYXM=,size_16,color_FFFFFF,t_70)
#### Bean 实例化流程
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200327192651596.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2NvZGVqYXM=,size_16,color_FFFFFF,t_70)
图片来源：[Spring bean的生命流程](http://www.tianxiaobo.com/2018/01/19/Spring-bean%E7%9A%84%E7%94%9F%E5%91%BD%E6%B5%81%E7%A8%8B/) by 田小波
#### 循环依赖
![在这里插入图片描述](https://img-blog.csdnimg.cn/2020032719270448.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2NvZGVqYXM=,size_16,color_FFFFFF,t_70)
#### getBean 流程分析
![在这里插入图片描述](https://img-blog.csdnimg.cn/2020032719272053.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2NvZGVqYXM=,size_16,color_FFFFFF,t_70)
图片参考：[Spring IOC 容器源码分析 - 获取单例 bean](http://www.tianxiaobo.com/2018/06/01/Spring-IOC-%E5%AE%B9%E5%99%A8%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90-%E8%8E%B7%E5%8F%96%E5%8D%95%E4%BE%8B-bean/) by 田小波
