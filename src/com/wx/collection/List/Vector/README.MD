## Vector总结
1.底层采用数组存储数据，所以数据是有序可重复的。
2.如果采用无参构造函数创建实例，则默认容量是10，增量是0，是在构造函数里确定的；
  数组采用无参构造函数创建实例时，默认容量是10，是在第一次添加元素确定。
3.如果增量是0，按照2倍增长，如果采用了有参构造函数，并且设置了增量大于0，则按照增量来扩容。
4.因为Vector的操作方法都被synchronized修饰，所以线程是安全的。