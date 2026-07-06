# POE2 国服攻略（WeGame）

《流放之路：降临》国服（WeGame）攻略文档，维护分支：**`cn-wegame`**，正文目录：**`cn-wegame/`**。

仓库总说明（分支划分、国际服索引）见 **`main`** 分支根目录 `README.md`。

## 游戏下载

| 项目 | 地址 |
|------|------|
| 国服官网 | <https://poe2.qq.com> |
| WeGame 商店页 | <https://www.wegame.com.cn/store/2002052/Path_of_Exile_2> |

## 获取本分支文档

仓库：<https://github.com/chengduyangyongxin/POE2>

```bash
git clone -b cn-wegame https://github.com/chengduyangyongxin/POE2.git
cd POE2
git pull origin cn-wegame
```

## 文档索引

| 路径 | 内容 |
|------|------|
| [`cn-wegame/README.md`](cn-wegame/README.md) | 国服目录结构、职业列表、玩法分类 |
| [`cn-wegame/新手攻略/README.md`](cn-wegame/新手攻略/README.md) | 入门、机制、FAQ（与赛季无关） |
| [`cn-wegame/0.5-奥杜尔秘符/开荒/README.md`](cn-wegame/0.5-奥杜尔秘符/开荒/README.md) | 当前赛季八职业开荒 BD 索引 |

## 目录结构

```
cn-wegame/
├── 新手攻略/              # 跨赛季基础说明
├── 赛季模板/              # 新赛季复制用
└── <赛季名>/
    └── <玩法>/            # 开荒、刷图、Boss 等
        └── <职业>/
            ├── README.md  # 职业机制说明
            └── BD*.md     # 具体构筑
```

路径规则：

| 类型 | 路径 |
|------|------|
| 赛季攻略 | `cn-wegame / 赛季名 / 玩法 / 职业 /` |
| 新手攻略 | `cn-wegame / 新手攻略 /` |

## 当前赛季

| 文件夹 | 大版本 | 赛季名 |
|--------|--------|--------|
| `0.5-奥杜尔秘符/` | 0.5 · 远古回响 | 奥杜尔秘符 |

## 文档格式

- 正文使用 Markdown（`.md`）
- 文件名示例：`BD01-升华-技能开荒.md`、`开荒路线.md`
- 单文件过长时按主题拆分

## 本地参考资料

搜集用草稿可放在仓库根目录 `资料/`（已 `.gitignore`），定稿后写入 `cn-wegame/` 对应路径。

## 协作

| 操作 | 说明 |
|------|------|
| clone / pull | 公开仓库，只读无需协作者权限 |
| push | GitHub → **Settings** → **Collaborators** → **Add people**（权限：**Write**） |
| 提交分支 | **`cn-wegame`** |
