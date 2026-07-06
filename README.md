# POE2 攻略版本库

《流放之路：降临》（Path of Exile 2）攻略资料仓库。

## 游戏下载

| 服务 | 下载 / 官网 |
|------|-------------|
| **国服（WeGame）** | 官网 <https://poe2.qq.com> · WeGame 商店 <https://www.wegame.com.cn/store/2002052/Path_of_Exile_2> |
| **国际服（Global）** | 独立客户端 <https://pathofexile2.com/download> · 官网 <https://www.pathofexile.com>（亦可 Steam / Epic 库中安装） |

本仓库按 **服务版本** 分分支维护：国际服与国服（WeGame）版本节奏、译名、经济等可能不同，请勿混用分支内容。

---

## 分支一览

| 分支 | 用途 | 说明 |
|------|------|------|
| **`main`** | 仓库入口说明（本文件） | 不含具体攻略正文 |
| **`cn-wegame`** | 国服 WeGame 攻略维护 | 对应 `cn-wegame/` 目录 |
| **`global`** | 国际服（Global）攻略维护 | 对应 `global/` 目录 |

```
main          →  仓库说明（起始分支）
cn-wegame     →  cn-wegame/  目录下的国服文档
global        →  global/     目录下的国际服文档
```

---

## 如何获取攻略

### 国服

```bash
git clone -b cn-wegame https://github.com/chengduyangyongxin/POE2.git
cd POE2
git pull origin cn-wegame
```

### 国际服

```bash
git clone -b global https://github.com/chengduyangyongxin/POE2.git
cd POE2
git pull origin global
```

克隆后进入对应分支上的 `cn-wegame/` 或 `global/` 目录阅读文档。若默认克隆 `main` 分支，需手动切换至 `cn-wegame` 或 `global` 后方可阅读攻略正文。

---

## 目录约定（各维护分支内相同）

路径规则：

| 类型 | 路径 |
|------|------|
| 赛季攻略 | `服务版本目录 / 赛季名 / 玩法 / 职业 /` |
| 新手攻略 | `服务版本目录 / 新手攻略 /` |

玩法目录常见分类：`开荒/`、`刷图/`、`Boss/`、`速刷/`、`交易/`。

---

## 协作与权限

- 仓库地址：<https://github.com/chengduyangyongxin/POE2>
- **只看 / clone / pull**：公开仓库无需添加协作者。
- **需要 push**：GitHub → 仓库 **Settings** → **Collaborators** → **Add people**（权限级别：**Write**）。
- 国服文档在 **`cn-wegame`** 分支提交；国际服文档在 **`global`** 分支提交。

---

## 本地资料（不纳入 Git）

从网络搜集的参考草稿可放在仓库根目录 `资料/`（已 `.gitignore`），定稿后再写入对应维护分支。
