


验证

```
pod lib lint YourSDKName.podspec  # 本地验证
pod spec lint YourSDKName.podspec # 联网验证（含依赖检查）
```


```
pod repo push private-specs YourSDKName.podspec
```