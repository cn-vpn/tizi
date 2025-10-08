# 🌐 梯子工具全指南：Clash / V2Ray 下载、配置与使用教程

科学上网（俗称“翻墙”）已成为许多人访问全球互联网的重要工具。  
目前常见的代理协议与核心包括：

> **Shadowsocks (SS)** · **Trojan** · **NaiveProxy** · **Hysteria / TUIC** · **WireGuard / Outline** · **Clash / Clash.Meta** · **V2Ray / V2Fly**

其中，**Clash** 和 **V2Ray** 是目前最主流、兼容性最强的两个核心。  
本文将带你了解它们的区别，并教你如何从 GitHub 下载、配置和使用这些客户端，实现科学上网。

---

## 💎 推荐机场（支持 Clash / V2Ray）

| 机场名称 | 特点与亮点 | 注册入口 |
|-----------|-------------|-----------|
| **大哥云** | 💰 年付仅 7 元/月 · 5年老牌 · 国内中转加密隧道 · 海外团队稳定可靠 | [👉 点击注册](https://smalldogqing.25ge.com/#/register?code=N2NWojow) |
| **扬帆云** | 🚀 月付 15 元 · 100GB大流量包 · 高速稳定 · 多端支持 · 专业团队维护 | [🔥 推荐注册](https://yftg1.net/register?code=B3wIZGxR) |

> ⚠️ **温馨提示**：以上机场长期稳定运营，均支持 **Clash / V2Ray / Shadowrocket** 等客户端。  
> 🧭 **建议：** 注册后复制订阅链接导入客户端，即可一键使用。

---

## 🚀 一、快速上手：科学上网的五个步骤

| 步骤 | 内容说明 |
|:----:|-----------|
| **① 获取订阅链接** | 注册机场 → 获取你的 **订阅地址（URL）** |
| **② 下载客户端工具** | 按操作系统选择对应客户端（如 **v2rayN / NekoRay / v2rayNG / Clash Verge**） |
| **③ 导入订阅链接** | 打开客户端 → 找到「订阅」或「配置」页面 → 粘贴订阅并更新 |
| **④ 启动代理服务** | 启用 **系统代理** 或 **HTTP / SOCKS5** 模式 |
| **⑤ 测试是否成功** | 打开 [ip111.cn](https://ip111.cn) 或访问 **Google / YouTube** 检查是否变为海外 IP |

> 💡 **提示**：如果 IP 未变化，可尝试切换节点或关闭系统代理后重新连接。

---

## 💻 二、主流客户端推荐与下载

| 操作系统 | 推荐客户端 | 核心 | GitHub 下载地址 |
|-----------|--------------|--------|----------------|
| **Windows** | [v2rayN](https://github.com/2dust/v2rayN) / [Clash Verge Rev](https://github.com/Clash-Verge-Rev/clash-verge-rev) | V2Ray / Clash.Meta | ✅ |
| **macOS** | [NekoRay](https://github.com/MatsuriDayo/NekoRay) / [ClashX](https://github.com/yichengchen/clashX) | V2Ray / Clash | ✅ |
| **Linux** | [NekoRay](https://github.com/MatsuriDayo/NekoRay) / [Clash.Meta](https://github.com/MetaCubeX/Clash.Meta) | V2Ray / Clash.Meta | ✅ |
| **Android** | [v2rayNG](https://github.com/2dust/v2rayNG) / [Clash Meta for Android](https://github.com/MetaCubeX/ClashMetaForAndroid) | V2Ray / Clash.Meta | ✅ |
| **iOS** | Shadowrocket / Stash / Quantumult X | 多核心支持 | ⚠️ 需美区 Apple ID |

---

## ⚙️ 三、V2Ray / Clash 的配置思路

### 🧩 V2Ray 系客户端
- 支持多种协议（VMess / VLess / Trojan / Shadowsocks）
- 通常需要导入机场提供的订阅链接
- 推荐客户端：
  - Windows：**v2rayN**
  - Android：**v2rayNG**
  - macOS / Linux：**NekoRay**

### 🧭 Clash 系客户端
- 基于 **Clash / Clash.Meta** 内核
- 使用 YAML 格式配置文件（或机场提供的 Clash 订阅）
- 推荐客户端：
  - Windows / macOS：**Clash Verge Rev**
  - Android：**Clash Meta for Android**

---

## 🧠 四、常见问题（FAQ）

**Q：订阅导入后无法更新节点怎么办？**  
A：检查订阅链接是否可访问，或机场是否支持你的客户端类型。

**Q：系统代理打开后仍然无法访问 Google？**  
A：可能是浏览器未走系统代理，可尝试切换为「全局模式」。

**Q：Clash 和 V2Ray 有什么区别？**  
A：Clash 更注重「多协议聚合」与「规则分流」，V2Ray 则更灵活、可自定义配置。

---

## 📚 五、更多参考与资源

- [V2Ray 官方项目](https://github.com/v2fly/v2ray-core)  
- [Clash.Meta 核心](https://github.com/MetaCubeX/Clash.Meta)  

---

### ✅ 总结

如果你是新手，建议先使用 **Clash Verge Rev（Windows）** 或 **v2rayNG（Android）**。  
这两款工具配置简单、兼容性强，几乎可以一键导入机场订阅，实现稳定的科学上网体验。
