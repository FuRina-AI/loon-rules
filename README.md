# Loon Rules

## Talkatone

### Bottom Ad Block

```text
https://raw.githubusercontent.com/FuRina-AI/loon-rules/main/talkatone-bottom-ad.plugin
```

### Stable-IP Route for Registration

把 Talkatone / Google OAuth / hCaptcha 注册链路固定到同一个策略组，减少分流/换 IP/MITM 导致的风控失败。

导入前请把插件里的策略名 `TalkatoneProxy` 改成你 Loon 里实际的节点或策略组名；注册时不要对这些域名启用 MITM。

```text
https://raw.githubusercontent.com/FuRina-AI/loon-rules/main/talkatone-stable-ip.plugin
```
