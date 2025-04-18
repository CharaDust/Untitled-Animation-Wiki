# Chara Dust（角色）

本文章介绍的是一名原创可操控角色。关于其他同名条目，请参考[消歧义页面](../Disambiguation/Chara_Dust.md)  

> Muestra #25565, esta debe ser una de las mejores muestras en términos de aptitud física y capacidad de lucha, y debería ser más que suficiente para manejar algunos enemigos alfa. Es una lástima que esta muestra se estrelló en el cráter no hace mucho tiempo.  
> 第25565号样本，这应该是身体机能和战斗能力最出色的样本之一，应付一些首领敌人应该绰绰有余。只可惜，这个样本在不久之前坠入了火山口，你知道的。  
> —— Chara Dust (#33897)

Chara Dust 是一名具有快速对敌方施加负面效果能力的辅助型可操控角色，能够在快速削弱敌方的同时兼具有一定输出能力。

## 面板参数

- 品质类型：强力（`S`）  
- [生物种族](../Concept/Bioethnic.md)：异象（人类）  
  - [灵魂特质](Soul.md)：仇恨（![#000000](https://via.placeholder.com/12/000000/000000?text=+) `#000000`）  
- [容器类型](../Concept/Container.md)：张力（TP）

| 项目名称  | 基础值 | 升级加成 |
| ----- | --: | ---: |
| 生命指示值 |   1 |    0 |
| 攻击能力  |   1 |    0 |
| 防御力   |   1 |    0 |
Chara Dust 的基础攻击能力取决于同队伍中其他队员基础攻击能力均值的80%，若队伍中只包含 Chara Dust 一名角色，则其基础攻击能力为所持有武器的60%

## 天赋模板
### 天赋树升级项目

| 项目名称 | 基础值 | 升级加成 | 最大等级 | 最大值 |
| ---- | --: | ---: | ---: | --: |
| 暴击加成 |  0% |   3% |   20 | 60% |
| 迅捷   | 144 |  3.2 |   10 | 176 |
| 伤害穿透 |  0% |  2.4 |   10 | 24% |
| 暴击几率 | 50% |   2% |    5 | 60% |
### 特有属性升级项目

| 项目名称 | 基础值 | 升级加成 | 最大等级 | 最大值 |
| ---- | --: | ---: | ---: | --: |
|      |     |      |      |     |

## 技能模板 `ACT`

### 制式攻击

当 Chara Dust 装备特定武器（百般变化之刃）时施放的攻击模组

| 攻击类型 | 攻击阶段 | [伤害类型](../Concept/Damage.md) |            倍率 |        强化加成 | 强化等级 |
| ---- | ---- | ---------------------------- | ------------: | ----------: | ---: |
| 普通攻击 | 1 段  | 机械力 - 突刺                     |           43% |        2.2% |   20 |
| 普通攻击 | 2 段  | 机械力 - 切割                     |           52% |        2.4% |   20 |
| 普通攻击 | 3 段  | 机械力 - 碰撞                     |           61% |        4.2% |   20 |
| 普通攻击 | 4 段  | 机械力 - 切割                     |           58% |        3.6% |   20 |
| 普通攻击 | 5 段  | 机械力 - 突刺                     |     38% + 35% |  1.8% /ARGU |   20 |
| 普通攻击 | 6 段  | 机械力 - 碰撞                     |           80% |          6% |   20 |
| 重击   | 任意   | 取决于普通攻击类型                    |  1.75x 普通攻击倍率 |             |   20 |
| 冲击   | 总计   | 机械力 - 碰撞                     |   1.4x 普通攻击倍率 |             |   20 |
| 下落攻击 | 总计   | 机械力 - 碰撞                     | 99% + 290x 动量 | 12.5% + 12x |   20 |

| 攻击类型 | 攻击阶段 | 制式         |
| ---- | ---- | ---------- |
| 普通攻击 | 1 段  | **X**      |
| 普通攻击 | 2 段  | X**X**     |
| 普通攻击 | 3 段  | XX**X**    |
| 普通攻击 | 4 段  | XXX**X**   |
| 普通攻击 | 5 段  | XXXX**X**  |
| 普通攻击 | 6 段  | XXXXX**X** |
| 重击   | 任意   | X**Y**     |
| 冲击   | ---  | B**Y**     |
| 下落攻击 | ---  | A**X**     |

### 非制式攻击

当 Chara Dust 未装备特定武器时施放的攻击模组

| 攻击类型 | 攻击阶段 | 伤害类型     |  倍率 | 强化加成 | 强化等级 |
| ---- | ---- | -------- | --: | ---: | ---: |
| 普通攻击 | 1 段  | 机械力 - 碰撞 | 50% |      |      |
| 普通攻击 | 2 段  | 机械力 - 碰撞 | 50% |      |      |

### 主动技能 - 重现 · 接管掌政

Chara Dust 转换为风尘执政状态，在风尘执政状态下：
- 记录释放技能前最后一段攻击的段数作为技能动作参考
- 在制式攻击中的普通攻击和下落攻击造成机械力伤害后，同时附加业力打击伤害
  - 伤害频率由打击频率决定，与武器挥舞无关
  - 业力打击实质上为生命指示值转化
    - 不能视为伤害
    - 不计算暴击加成
- 无法施放重击与冲击

| 攻击类型 | 攻击阶段 | 伤害类型 |    属性值/倍率 | 强化加成 | 强化等级 |
| ---- | ---- | ---- | --------: | ---: | ---: |
| 普通攻击 | （任意） | 业力打击 | 5.4x 角色等级 | 0.6x |   20 |
| 下落攻击 | （总计） | 业力打击 |   7x 角色等级 |   1x |   20 |

| 属性        |  属性值/倍率 |  强化加成 | 强化等级 |
| --------- | ------: | ----: | ---: |
| 打击频率（BPM） |  83% 敏捷 |  3.2% |   20 |
| 打击频率加成    | 52% 暴击率 | 10.4% |   20 |
| 持续时间      |    12 秒 | 0.4 秒 |   20 |
| 冷却时间      |    25 秒 |       |      |

### 终结技能 - 压轴 · 引力节拍

Chara Dust 对前方敌人进行高频率的爆发攻击，同时获得 1 点个人黑洞力场充能，转换为风尘执政状态

| 攻击类型 | 攻击阶段 | 伤害类型 |    属性值/倍率 | 强化加成 | 强化等级 |
| ---- | ---- | ---- | --------: | ---: | ---: |
| 技能伤害 |      | 业力打击 | 6.2x 角色等级 | 0.8x |   20 |

| 属性        |   属性值/倍率 |  强化加成 | 强化等级 |
| --------- | -------: | ----: | ---: |
| 打击频率（BPM） |  136% 敏捷 |  5.2% |   20 |
| 打击频率加成    |  64% 暴击率 |   12% |   20 |
| 技能伤害加成    | 72% 暴击伤害 |   16% |   20 |
| 技能消耗      | 1000 mTP |       |      |
| 持续时间      |      1 秒 | 0.2 秒 |   20 |
| 冷却时间      |     17 秒 |       |      |

### 被动技能 - 黑洞 · 防御力场

Chara Dust 开启个人黑洞力场以免受到意外伤害
- 充能上限为 2 点，每受到一次伤害，使得该伤害效果无效，并消耗 1 点充能
  - 若处于高温环境，则额外消耗 1 点充能
  - 每抵御一次伤害，将向周围物体和角色作用一次吸引力，并对周围敌方角色以及攻击者进行业力打击（若有）

| 攻击类型 | 攻击阶段 | 伤害类型 |        属性值/倍率 | 强化加成 | 强化等级 |
| ---- | ---- | ---- | ------------: | ---: | ---: |
| 引力伤害 |      | 业力打击 |     351% 角色等级 |  17% |   10 |
| 反馈伤害 |      | 业力打击 | 14% 指定生命指示值上限 | 2.1% |   10 |

## 技能模板 `RND`

## 星级

### 星级 I

### 星级 II

### 星级 III

<!-- 仅品质为普通及以上的角色可用 -->
### 星级 IV

<!-- 仅品质为强力的角色可用 -->
### 星级 V
## 模拟等价属性
此处列出 Chara Dust 在其他游戏作品模拟的属性值

| 游戏作品常用名称                      | 属性键  | 属性值 |
| ----------------------------- | ---- | --- |
| 原神（`Genshin Impact`）          | 神之眼  | 雷   |
| 原神（`Genshin Impact`）          | 武器   | 单手剑 |
| 星穹铁道（`Star Rail`）             | 战斗属性 | 雷   |
| 星穹铁道（`Star Rail`）             | 战斗命途 | 虚无  |
| 绝区零（`Zenless Zone Zero`）      | 元素属性 | 以太  |
| 绝区零（`Zenless Zone Zero`）      | 特性   | 支援  |
| 我的世界地下城（`Minecraft Dungeons`） | 伤害类型 | 灵魂  |
| 明日方舟（`Arknights`）             | 职业   | 特殊  |
| 明日方舟（`Arknights`）             | 部署位置 | 近战位 |
|                               |      |     |

