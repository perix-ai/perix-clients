# Perix Clients

Perix 终端侧仓库。

## 仓库定位
承载所有终端与本地执行能力：
- iOS
- Android
- Desktop Agent
- Web Dashboard
- Shared client protocol / UI spec

## 目录结构
```text
ios/
android/
desktop/
web/
shared/
  client-protocol/
  ui-spec/
```

## 建议
- 客户端与云端独立发布
- 本地 runtime / MCP bridge / 权限管理放在本仓
- 各平台复用 shared 协议与交互规范
