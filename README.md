# 假面骑士 · 全系列立绘库

东映官方图鉴（[kamen-rider-official.com/zukan](https://www.kamen-rider-official.com/zukan)）全量立绘整理，**10,623 张**，按五类分组，纯英文 ID 路径，可直接当图床引用。

## 在线浏览

**https://hykhxy.github.io/kamen-rider-archive/**

支持中文名／日文原名／系列名搜索，可按类别、系列、时代筛选；点开任意一张可复制直链。

## 图片直链

jsDelivr（推荐，全球 CDN）：

```
https://cdn.jsdelivr.net/gh/hykhxy/kamen-rider-archive@main/{类别}/{ID}.webp
```

类别目录：`rider` 骑士 · `form` 形态 · `char` 人物 · `monster` 怪人 · `item` 道具

例：

```
https://cdn.jsdelivr.net/gh/hykhxy/kamen-rider-archive@main/rider/179.webp
https://cdn.jsdelivr.net/gh/hykhxy/kamen-rider-archive@main/monster/744.webp
```

也可用 GitHub 原生地址：

```
https://raw.githubusercontent.com/hykhxy/kamen-rider-archive/main/rider/179.webp
```

> jsDelivr 有 CDN 缓存；更新图片后想立刻生效，请把 URL 里的 `@main` 换成具体的 commit SHA。

## 数量

| 目录 | 类别 | 张数 |
|---|---|---:|
| `rider/` | 骑士（主骑／副骑／番外／量产） | 443 |
| `form/` | 形态（基础／强化／最终） | 1,428 |
| `char/` | 人物（主角团／配角／反派干部） | 4,038 |
| `monster/` | 怪人 | 1,983 |
| `item/` | 道具（变身器／武器／媒介／载具） | 2,731 |
| | **合计** | **10,623** |

## 索引

- `data.json`：全部条目的元数据（ID／类别／中文名／日文原名／系列／年份／时代／路径／官方页）
- `index.html`：画廊页（纯静态，无后端）

元数据字段：

```json
{"i":179,"c":"骑士","p":"rider/179.webp","n":"假面骑士1号","j":"仮面ライダー1号",
 "s":"假面骑士（初代）","y":1971,"e":"昭和",
 "u":"https://www.kamen-rider-official.com/zukan/kamen_rider_members/179"}
```

## 规格

- 格式 WebP，宽度 520px，质量 84，单张 15–135 KB
- 全库约 318 MB
- 文件名即官方图鉴 ID，与官方页一一对应

## 版权

图片来源 © 石森プロ・テレビ朝日・ADK EM・東映。

本仓库为**非商业同人资料整理**，仅供学习、研究与个人创作参考；请勿用于商业用途，请勿二次打包分发。若版权方要求，将立即删除。
