# Sidestore-ClashMi
使用 ClashMi 替代 LocalDevVPN / StosVPN 。解决部分运营商对 gsa.apple.com 不友好的问题。


# 使用图文教程
1. 从外区苹果商店下载 [Clash Mi](https://apps.apple.com/us/app/clash-mi/id6744321968) 【免费软件】

   <img width="550" height="216" alt="image" src="https://github.com/user-attachments/assets/dab0e86c-6090-463f-a206-bc754a1c4b88" />

2. 添加你的机场订阅链接，然后连接上 VPN 。[如果没有可以在底部选购](#机场推荐)。如果你有多个机场订阅链接想合并使用可以[下载完整 proxy-providers 配置文件](https://github.com/tom-snow/Sidestore-ClashMi/raw/refs/heads/master/profile_full.yaml)

   <img width="384" height="661" alt="image" src="https://github.com/user-attachments/assets/27c09a4f-a740-4d6f-94bd-ededd96bd437" />

   <img width="384" height="661" alt="image" src="https://github.com/user-attachments/assets/89904122-24ce-4116-894d-3ed9d1a2fce6" />

3. 点 核心设置 -> 覆写 。（截图是电脑端的，界面略有不同，不影响）

   <img width="384" height="661" alt="image" src="https://github.com/user-attachments/assets/3ca7f71d-039b-4db2-9cdf-9ac9e472583e" />

   <img width="384" height="661" alt="image" src="https://github.com/user-attachments/assets/96a37d08-cb06-44b3-a22f-4140791f3ef3" />

4. 复制下面的链接，哪个都行。（也可以下载文件然后导入）

【推荐】核心覆写配置，文件小
```
https://github.com/tom-snow/Sidestore-ClashMi/raw/refs/heads/master/profile_overwrite_min.yaml
```

<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/9d65f2ee-1e25-4405-841a-f13d7f3965ca" />


~JS完整覆写配置，分流全~【Clash Mi 暂未支持JS覆写】
```
https://github.com/tom-snow/Sidestore-ClashMi/raw/refs/heads/master/overwrite_mihomo.js
```

完整 TUN 配置（部分参数可以自行下载修改）
```
https://github.com/tom-snow/Sidestore-ClashMi/raw/refs/heads/master/profile_overwrite_tun.yaml
```

5. 导入覆写配置（可以点 剪贴板导入 快速添加或者 添加配置链接 手动填写）并保存

   <img width="384" height="661" alt="image" src="https://github.com/user-attachments/assets/efbc9763-dea8-4bc3-afbe-8e9f18eec864" />

6. 启用覆写配置并【断开VPN】然后【重新连接】

   <img width="384" height="661" alt="image" src="https://github.com/user-attachments/assets/53927a26-ccac-45c9-ab9e-3c98b8960778" />


7. 打开 Sidestore 测试效果

PS: 如果提示 `The data couldn’t be read because it isn’t in the correct format.` 或者其他什么（签名时进度条没走到1/3后），主要检查网络连接，检查 `gsa.apple.com` 是否是通过了代理的，简单点就开全局模式。

# 常见问题

[【点这查看】](https://github.com/tom-snow/Sidestore-ClashMi/issues/5)


