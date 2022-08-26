# PermissionX
第一行代码（第三版）编写并发布一个开源库

添加如何配置将PermissionX引入到你的项目中

```groovy
dependencies{
    ...
    implementation 'com.permissionx.guolindev:permissionx:1.0.0'
}
```

然后就可以用如下语法来申请运行时权限

```kotlin
PermissionX.request()
```
