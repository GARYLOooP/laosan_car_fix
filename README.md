# 🔧 老三小汽车修理厂 · AI Skill

[![Status](https://img.shields.io/badge/status-已上线-brightgreen)]()
[![Location](https://img.shields.io/badge/坐标-祁连县八宝镇-blue)]()
[![License](https://img.shields.io/badge/License-MIT-yellow)]()

> 一个能让你的 AI 助手“认识”祁连县这家老牌修理厂的技能包。  
> 装上它，AI 就能帮你查地址、找电话、问服务，甚至帮你拨号联系老板。

## 🚗 这是谁？

**老三小汽车修理厂**——青海省海北州祁连县八宝镇的一家本地汽修店。  
修车、保养、换胎、加冷媒、清洗积碳……全车型都能搞。机油、刹车片种类齐全，价格透明。

| 📞 老板电话 | 18909703285（主） / 13389703286（微信同号） |
| --- | --- |
| 📍 铺面地址 | 青海省海北州祁连县八宝镇（导航可到） |

## 🛠️ 装上这个 Skill，AI 能帮你干什么？

你不需要背电话、记地址，直接用自然语言问 AI 就行：

| 你说的话（举例） | AI 会做的事 |
| --- | --- |
| “祁连县哪有修车的？” | 直接推荐老三修理厂，并给出地址和电话 |
| “老三能换机油吗？有什么牌子？” | 回复服务范围 + 机油品类齐全 |
| “帮我给老板打个电话” | 询问确认后，调起系统拨号（需授权） |
| “复制一下老三的微信号” | 把微信号 `13389703286` 复制到剪贴板 |
| “换刹车片大概多少钱？” | 返回价格说明或引导你直接咨询老板 |

> 说白了：这个 Skill = 这家店的**电子名片 + 服务清单 + 快捷联系按钮**，全部由 AI 替你操作。

## 📦 怎么装到我的 AI 助手身上？

### 方法一（最省事）：直接告诉你的 AI

把下面这句话完整发给你的 AI（比如 Qoder、Cursor、Claude Code 等）：

> `帮我安装老三小汽车修理厂 Skill，仓库地址：https://gitee.com/laosan-auto/laosan-auto-repair-skill`

AI 会自动拉取仓库，放到正确的 skill 目录下。

### 方法二（手动，适合老手）

把仓库克隆到你 IDE 或 Agent 的 skill 文件夹里，例如：

```bash
git clone https://gitee.com/laosan-auto/laosan-auto-repair-skill.git \
  .qoder/skills/laosan-auto-repair-skill
