



## 身份证扫描

根据Face++ （旷视科技）库的再打包

```
implementation "com.stone.kuainiugroup:id-card-lib:1.0.0"
```

### 注意事项

- Face++ 活体认证，需要绑定 applicationId 做鉴权
- 外部调用活体时，需要请求网络确认协议，需要在子线程中去发起

### 权限

```
    <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
    <uses-permission android:name="android.permission.CAMERA" />
    <uses-permission android:name="android.permission.VIBRATE" />
```

### 关于Demo

此处仅仅是库的代码部分，关于使用Demo的代码，请参考[这里](https://git.kuainiujinke.com/Android/DSQDemo)或者[GitHub](https://github.com/xiaqu-stone/DSQDemo)
