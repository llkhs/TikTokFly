# Quantumult X 解锁 Tiktok
### 规则对于 TikTok v19.6.0 有效
### 需要美区下载的TikTok，其它区本规则可能无效，（港区已停止运营）


**操作步骤**

1、打开 `Quantumult X`  

2、开启 `MitM` - `允许`安装描述文件 - iOS `设置`- 看到`已下载描述文件` - `安装Quantumult X证书`，
    并在`设置`-`通用`-`关于本机`-`证书信任设置`-找到`Quantumult X Custom Root Certificate...`-`信任根证书`

3、引用分流：

```
https://raw.githubusercontent.com/llkhs/TikTokFly/main/QuantumultX/ruleset_tiktok_list.conf
```

4、引用重写(使用时4选1)：

·日本
```
https://raw.githubusercontent.com/llkhs/TikTokFly/main/QuantumultX/TikTok-JP.conf
```

·台湾
```
https://raw.githubusercontent.com/llkhs/TikTokFly/main/QuantumultX/TikTok-TW.conf
```

·韩国
```
https://raw.githubusercontent.com/llkhs/TikTokFly/main/QuantumultX/TikTok-KR.conf
```

·美国
```
https://raw.githubusercontent.com/llkhs/TikTokFly/main/QuantumultX/TikTok-US.conf
```
