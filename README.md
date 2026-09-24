# jichangdingyue
GitHub 上的完整机场订阅仓库模板，包括 README、Clash/Mihomo、sing-box、订阅转换和 GitHub Actions 自动更新。

# Airport Subscription Config

个人代理订阅配置仓库。

支持：

- Clash Meta / Mihomo
- sing-box
- Subconverter
- GitHub Actions 自动更新

---

## 使用方式

### Clash Meta

导入：
https://raw.githubusercontent.com/USER/airport-subscription/main/clash/config.yaml

---

### sing-box

导入：
https://raw.githubusercontent.com/USER/airport-subscription/main/sing-box/config.json
---

## 自动更新

GitHub Actions 每 6 小时同步一次订阅。

修改：subscriptions/urls.yaml

添加你的订阅地址。

---

## 文件说明
subscriptions/
机场订阅源

clash/
Clash Meta 配置

sing-box/
sing-box 配置

rules/
分流规则

converter/
订阅转换配置

---

## License

MIT
