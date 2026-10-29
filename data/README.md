# data · 数据说明

## agents.csv

已实装代理人 61 位（截至 3.3）。字段：

| 字段 | 说明 |
|---|---|
| `version` | 首次实装版本（1.0 为公测常驻/首批） |
| `name_cn` | 中文官方译名（含代号引号） |
| `name_en` | 英文名（Prydwen/国际服） |
| `rarity` | S / A |
| `attribute` | 游戏内属性；变体用括号标注（烈霜/玄墨/凛刃） |
| `specialty` | 强攻/击破/异常/支援/防护/命破/锋御 |
| `faction` | 所属阵营；不确定标「待确认」 |

> 用法：按 `attribute`/`specialty` 过滤即可做环境统计；按 `version` 排序可还原卡池节奏。

## versions.csv

21 个版本（1.0–3.3）。字段：

| 字段 | 说明 |
|---|---|
| `version` | 版本号 |
| `date` | 国服上线日期（YYYY-MM-DD） |
| `title` | 版本标题 |
| `new_agents` | 该版本首次实装代理人（顿号分隔） |
| `key_additions` | 关键系统/内容 |

> 日期为版本更新日；卡池具体起止可能相差数小时。2.5/2.6 受春节排期影响，周期与常规 6 周略有差异。

## 一致性

- 行数：agents 61、versions 21。
- 与 `06-代理人图鉴.md`、`05-版本编年史.md` 同步。
- 修改数据后请同步两份 md 与 `CHANGELOG.md`。
