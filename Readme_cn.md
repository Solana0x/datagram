# Datagram 节点 

![image](https://github.com/user-attachments/assets/727f2c92-7017-4e64-807f-6f643952f09f)

## 步骤 1：注册 Datagram 账户

在运行节点之前，您需要注册账户并获取您的 API 密钥。

1. 访问注册页面：**[https://dashboard.datagram.network?ref=183600408](https://dashboard.datagram.network?ref=183600408)**
2. 使用您的**电子邮件地址**注册。
3. 登录后，从仪表板**复制您的 API 密钥**。

---

## 步骤 2：创建文件夹并下载 Datagram CLI

1. 下载 `datagram-cli` 二进制文件：
```bash
wget -O datagram-cli https://github.com/Datagram-Group/datagram-cli-release/releases/latest/download/datagram-cli-x86_64-linux
```

2. 使文件可执行：
```bash
chmod +x datagram-cli
```

---

## 步骤 3：使用您的 API 密钥运行 Datagram CLI

1. 启动新的 `screen` 会话以保持程序在后台运行：
```bash
screen -S datagram
```

2. 使用您的 API 密钥运行 CLI（将 `YOUR_API_KEY` 替换为您的密钥）：
```bash
./datagram-cli run -- -key YOUR_API_KEY
```

3. 要在不停止进程的情况下脱离屏幕会话：
按下：
```
Ctrl + A 然后按 D
```

4. 要重新连接到屏幕会话：
```bash
screen -r datagram
```

---

## 附加说明

- 确保您的 API 密钥有效且处于活动状态。
- 使用 `screen` 以便节点在您注销后仍能保持运行。
- 您可以随时重新连接到屏幕来监控节点。

## 如需任何帮助，请联系：

Discord 上的 `0xphatom`  
https://discord.com/users/979641024215416842

# 社交媒体

## Telegram
[https://t.me/phantomoalpha](https://t.me/phantomoalpha)

## Discord
[https://discord.gg/pGJSPtp9zz](https://discord.gg/pGJSPtp9zz)
