# Proxy-rules
个人分流规则合集(仅用于个人使用)
# 个人分流规则合集

适用于：**Loon / Shadowrocket / Surge / Quantumult X / Clash Meta** 等工具的远程规则订阅

## 规则说明

- 全部规则使用 `DOMAIN-SUFFIX`、`DOMAIN-KEYWORD`、`IP-CIDR` 格式
- policy 字段统一使用 `PROXY`（可自行替换为 DIRECT / REJECT / 策略组名）
- 每日/每周手动或自动更新

## 订阅地址（直接复制到工具中使用）

***Meta_SocialMedia***       
  https://raw.githubusercontent.com/karlyum/Proxy-rules/refs/heads/main/rules/meta_social_rules.list

***Tinder***       
  https://raw.githubusercontent.com/karlyum/Proxy-rules/refs/heads/main/rules/Tinder_rules.list

## 使用方法

1. 在 Loon → 配置 → 远程规则 → 新建 → 粘贴链接 → 类型选 "Rule"
2. Shadowrocket → 设置 → 规则 → 添加远程文件 → 粘贴 Raw 链接
3. 建议：把 policy 替换成你自己的策略组名（如 HK、US、DIRECT 等）

最后更新：2026-01-16
