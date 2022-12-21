# 响应式流规范对Java9的偏爱

![image-20221221133315915](https://raw.githubusercontent.com/huxiaoning/img/master/202212211335393.png)

`FlowAdapters`提供了如下静态方法API:

- `toFlowProcessor`
- `toFlowPublisher`
- `toFlowSubscriber`
- `toProcessor`
- `toPublisher`
- `toSubscriber`

这些方法可以实现在RxJava流与Java9之间的对象互转。