# iOS一百天学习笔记：
## day20: iOS 关联对象笔记

```objective-c
void objc_setAssociatedObject(id object, const void*key, id value,objc_AssociationPolicy policy);
id objc_getAssociatedObject(id object, const void*key);
void objc_removeAssociatedObjects(id object);
```

###### 三个方法的作用分别是：

- 以键值对形式添加关联对象
- 根据 key 获取关联对象
- 移除所有关联对象

使用场景：下面AFN的一个例子

**注意：对于key的写法有很多种参考下面链接，个人比较喜欢上述的写法**

```objective-c
- (AFImageDownloadReceipt *)af_activeImageDownloadReceipt {
  return (AFImageDownloadReceipt *)objc_getAssociatedObject(self, @selector(af_activeImageDownloadReceipt));
}
```

