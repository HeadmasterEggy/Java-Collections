# ArrayList

`ArrayList`空参构造

```java
public ArrayList() {
    this.elementData = DEFAULTCAPACITY_EMPTY_ELEMENTDATA;
}
```

`DEFAULTCAPACITY_EMPTY_ELEMENTDATA`实际上是一个size为0的数组

```java
private static final Object[] DEFAULTCAPACITY_EMPTY_ELEMENTDATA = {};
```

使用空参创建ArrayList对象时，底层会创建一个长度为0的数组