# Kaplan Steve（角色）

<!-- 如果你需要编写一名具有不同功能的同名角色，请使用下面的文段跳转到相应的消歧义页面 -->
本文章介绍的是一名原创可操控角色。关于其他同名条目，请参考[消歧义页面](../Disambiguation/.example.md)

<!-- 这是角色的引言，如果你设定的角色源自于其他国家或地区，请编写一段对应语言的名言并附上中文翻译；若你设定的角色源自中国，则只需要编写中文 -->
> Raw Introductory  
> 名人名言。  
> —— 示例角色 (可能存在的修饰语)

Kaplan Steve 是一名针对特定负面效果具有高爆发输出能力的可操控角色，能够在战斗中为敌方施加两种不同的负面效果，且根据施加的效果增幅自身伤害。

## 面板参数

- 品质：强力（`S`）
- [生物种族](../Concept/Bioethnic.md)：异象（人类）  
  - [灵魂特质](Soul.md)：毅力（![#d535d9](https://via.placeholder.com/12/d535d9/000000?text=+) `#d535d9`）  
- [容器类型](../Concept/Container.md)：游离灵魂（SL）

|项目名称|基础值|升级加成|
|---|---:|---:|
|生命指示值|1000|40|
|攻击能力|100|4|
|防御力|100|4|
%%

| 项目名称  | 基础值 | 强化加成 | 强化点 I | 强化点 II | 强化点 III |
| ----- | --: | ---: | ----- | ------ | ------- |
| 暴击率   |  5% | 2.5% | Lv.25 | Lv.50  | Lv.75   |
| 暴击伤害  | 50% |   5% | Lv.25 | Lv.50  | Lv.75   |
| 灵力通识  |  50 |   10 | Lv.50 |        |         |
| 迅捷    |  50 |   10 | Lv.50 |        |         |
| 战斗精通  |  10 |    5 | Lv.33 | Lv.66  |         |
| 自定义数值 | 100 |   10 | Lv.50 |        |         |
%%
## 武器装备

示例角色擅长使用什么类型的武器，习惯如何使用武器

### 武器配装槽位
主要武器：

|      | 刀剑   | 枪棍  | 锤斧  | 连枷  |
| ---- | ---- | --- | --- | --- |
| 轻型   |      |     |     |     |
| 中型   | TRUE |     |     |     |
| 重型   |      |     |     |     |
| 特殊尺寸 |      |     |     |     |

<!-- 如果该角色有特殊携带武器的需求，请使用以下内容，对于角色特有的专用武器可以使用 #ad_hoc 变量标签；对于待定名字的标签，可以使用 #null 标签 -->
此外，该角色可以携带带有以下标签的武器：
- `#katana`
- `#null`

## 天赋模板
### 天赋树升级项目

| 项目名称 |  基础值 | 升级加成 | 最大等级 |  最大值 |
| ---- | ---: | ---: | ---: | ---: |
| 充能效率 | 100% |   4% |   20 | 180% |
| 战术精通 |    0 |   10 |   10 |  100 |
| 暴击加成 |  50% |   3% |   10 |  80% |
| 暴击几率 |   5% |   2% |    5 |  15% |
### 特有属性升级项目

| 项目名称 | 基础值 | 升级加成 | 最大等级 | 最大值 |
| ---- | --: | ---: | ---: | --: |
|      |     |      |      |     |

### 星级升级项目

| 星级    | 描述                                      |
| ----- | --------------------------------------- |
| ★     |                                         |
| ★★    | Kaplan 的主动技能热阈值提高20%，并移除满阈值下的额外冷却时间（暂定） |
| ★★★   | Kaplan 在场时，提高连携队友基于自身10%的充能效率（暂定）       |
| ★★★★  |                                         |
| ★★★★★ | Kaplan 的充能槽位数量提升至4个（暂定）                 |


<!-- 这是角色的技能参数，技能参数的升级一般在天赋树中升级 -->
## 技能模板 `ACT`

### 制式攻击

当 示例角色 装备特定武器时施放的攻击模组

| 攻击类型 | 攻击阶段 | [伤害类型](../Concept/Damage.md) |                 倍率 |       强化加成 | 强化等级 |
| ---- | ---- | ---------------------------- | -----------------: | ---------: | ---: |
| 普通攻击 | 1 段  | 机械力 - 切割                     |          100% 攻击能力 |       2.5% |   20 |
| 普通攻击 | 2 段  | 机械力 - 突刺                     |          100% 攻击能力 |       2.5% |   20 |
| 普通攻击 | 3 段  | 机械力 - 切割                     |          100% 攻击能力 |       2.5% |   20 |
| 重击   | （总计） | 霆雷                           |          150% 攻击能力 |         4% |   20 |
| 冲击   | （总计） | 霆雷                           |          125% 攻击能力 |         3% |   20 |
| 下落攻击 | （总计） | 霆雷                           | 175% 攻击能力 + 50x 落差 | 12.5% + 1x |   20 |

| 攻击类型 | 攻击阶段 | 制式      |
| ---- | ---- | ------- |
| 普通攻击 | 1 段  | **X**   |
| 普通攻击 | 2 段  | X**X**  |
| 普通攻击 | 3 段  | XX**X** |
| 重击   | 任意   | X**Y**  |
| 冲击   | ---  | B**Y**  |
| 下落攻击 | ---  | A**X**  |

### 非制式攻击

当 示例角色 未装备特定武器时施放的攻击模组

| 攻击类型 | 攻击阶段 | 伤害类型    |        倍率 | 强化加成 | 强化等级 |
| ---- | ---- | ------- | --------: | ---: | ---: |
| 普通攻击 | 1 段  | 物理 - 碰撞 | 100% 攻击能力 |      |      |
| 普通攻击 | 2 段  | 物理 - 碰撞 | 100% 攻击能力 |      |      |

### 主动技能 - 即使存乎梦田

Kaplan Steve 首先向前斩出一刀，随即快速蓄能并发动范围较大的居合斩：
- 首次斩出一刀的伤害类型为霆雷
- 蓄能居合斩的伤害类型将根据蓄能类型决定
	- 蓄能的伤害类型有：灼热、霜冻
	- 两种蓄能的类型随机抽取一个
- 蓄能居合斩将根据蓄能类型为攻击到的对象附加“崆峒之火”或者“幽咽之冰”效果
	- 两种效果可互相叠加，层数由被动效果决定
	- 重复施加将刷新持续时间
	- 持续时间由技能等级决定

| 攻击类型 | 攻击阶段  | 伤害类型  |    属性值/倍率 | 强化加成 | 强化等级 |
| ---- | ----- | ----- | --------: | ---: | ---: |
| 技能伤害 | 首刀    | 霆雷    | 150% 攻击能力 |   3% |   20 |
| 技能伤害 | 蓄能居合斩 | 灼热/霜冻 | 200% 攻击能力 | 2.5% |   20 |

| 属性              |    属性值/倍率 | 强化加成 | 强化等级 |
| --------------- | --------: | ---: | ---: |
| 属性 I            |  100% 防御力 | 2.5% |   20 |
| 属性 II           | 100% 战斗精通 | 2.5% |   20 |
| 技能消耗<!-- 可选 --> |       100 |      |      |
| 持续时间<!-- 可选 --> |      10 秒 |      |      |
| 热阈值             |       200 |      |      |
| 冷却率             |        10 |      |      |
| 抽象热量            |        90 |      |      |

### 终结技能 - 终将万物偕喜

示例角色 将怎么样施放这个技能，会发生什么：
- 会怎么样，发生什么事
- 在什么情况下会有另外的功能
  - 功能有什么特点
  - 如果满足条件会怎么样
- 有什么东西发生了改变

<!-- 下表填写技能伤害数据，如果这个技能不提供伤害，则可以删除此表格；此外，对于主动技能强化等级推荐为20，表示这个技能可以从0级升级到+20级 -->
|攻击类型|攻击阶段|伤害类型|属性值/倍率|强化加成|强化等级|
|---|---|---|---:|---:|---:|
|技能伤害||冲击波|200% 攻击能力|3%|20|
|其他伤害||火焰|75% 攻击能力|2.5%|20|

<!-- 下表填写技能属性数据 -->
|属性|属性值/倍率|强化加成|强化等级|
|---|---:|---:|---:|
|属性 I|100% 防御力|2.5%|20|
|属性 II|100% 战斗精通|2.5%|20|
|技能消耗<!-- 可选 -->|100|||
|持续时间<!-- 可选 -->|10 秒|||
|冷却时间|20 秒|||

### 终结技能 - 我们一心同体

Kaplan Steve 首先优化充能槽位的蓄能类型，并根据优化后的蓄能类型从身后施放速度极快的圆弧剑气，同时触发 Lydia 和 Firely 的连携终结技能
- 蓄能类型的优化会首先清除较少层数的蓄能类型，随后根据清除数量再次随机抽取蓄能
	- 如果已拥有的蓄能层数相等，则清除剩余时间最短的蓄能类型
	- 如果充能槽位未满，则会抽取到已满为止
- 圆弧剑气的基础伤害类型为 霆雷，在命中目标时还会根据目前的充能槽位的蓄能层数给目标叠加对应效果，并造成对应属性的附加伤害

| 攻击类型 | 攻击阶段   | 伤害类型  |    属性值/倍率 | 强化加成 | 强化等级 |
| ---- | ------ | ----- | --------: | ---: | ---: |
| 技能伤害 | 圆弧剑气   | 霆雷    | 200% 攻击能力 |   3% |   20 |
| 其他伤害 | 增益附加伤害 | 灼热/霜冻 |  75% 攻击能力 | 2.5% |   20 |

|属性|属性值/倍率|强化加成|强化等级|
|---|---:|---:|---:|
|属性 I|100% 防御力|2.5%|20|
|属性 II|100% 战斗精通|2.5%|20|
|技能消耗<!-- 可选 -->|1000|||
|持续时间<!-- 可选 -->|10 秒|||
|冷却时间|20 秒|||

### 被动技能 - 假如灾厄来临

Kaplan Steve 初始拥有3个充能槽位：
- 每当 Kaplan Steve 施放主动技能 I时，根据蓄能类型填充一个槽位
	- 槽位已满时，新蓄能的类型将取代旧的
- Kaplan Steve 的制式攻击得到强化
	- 充能槽位至少有1点充能时，Kaplan Steve 的普通攻击伤害将得到一定提升
		- 提升比例基于技能等级
	- 充能槽位至少有2点充能时，Kaplan Steve 的普通攻击伤害类型将变为霆雷
	- 充能槽位至少有3点充能时，Kaplan Steve 的普通攻击将会有几率为击中的HPV比例最高的目标施加与主动技能 I相同的负面效果
		- 施加几率取决于技能等级
		- 负面效果类型取决于槽位中最多的蓄能类型或最新的蓄能类型
		- 负面效果层数根据槽位填充的蓄能类型决定，不会覆写更高等级的同名效果和主动技能施加的同名效果
		- 拥有内置冷却时间，只有施加成功才会开始计时

| 属性       | 属性值/倍率 | 强化加成 | 强化等级 |
| -------- | -----: | ---: | ---: |
| 普通攻击伤害提升 |    20% | 2.5% |   10 |
| 效果命中     |    10% | 2.5% |   10 |


### 被动技能 - 我将报以赞歌

Kaplan Steve 的制式攻击命中带有“崆峒之火”或者“幽咽之冰”的目标并造成霆雷属性伤害时会产生如下效果：
- 每层“崆峒之火”将额外造成一次伤害
	- 本次伤害基础值取决于目标最大HPV的一定比例，比例取决于技能等级
	- 若以重击命中携带该效果的目标，则伤害基础值在原有基础上得到进一步提高
		- 此时该伤害可以暴击，取决于 Kaplan Steve 自身的属性
		- 造成伤害后将移除目标所有的“崆峒之火”效果
- 每层“幽咽之冰”将提升提升造成的伤害比例
	- 提升比例取决于技能等级
	- 若以冲击命中携带该效果的目标，则伤害提升比例在原有基础上得到进一步提高
		- 此时目标的防御力和抗性将会降低，取决于 Kaplan Steve 自身的属性
		- 造成伤害后将移除目标所有的“幽咽之冰”效果

| 攻击类型  | 攻击阶段 | 伤害类型 |   属性值/倍率 | 强化加成 | 强化等级 |
| ----- | ---- | ---- | -------: | ---: | ---: |
| 伤害基础值 |      | 灼热   | 1% 目标HPV | 0.1% |   10 |

| 属性        | 属性值/倍率 | 强化加成 | 强化等级 |
| --------- | -----: | ---: | ---: |
| 重击伤害基础值增幅 |   100% |   5% |   10 |
| 伤害提升比例    |    20% | 0.2% |   10 |
| 冲击伤害提升增幅  |    10% | 0.1% |   10 |
## 技能模板 `RND`

<!-- 这是角色的星级参数，可以获得额外能力，星级的提升一般在天赋树中升级 -->
## 星级

当 Kaplan Steve 等级提升到了Lv.100，可以消耗资源来提升星级
提升星级时会消耗角色等级，如星级 I 会消耗10级角色等级，星级 II 会消耗20级角色等级，但是获得一些额外能力。

### 星级 I

### 星级 II

### 星级 III

<!-- 仅品质为普通及以上的角色可用 -->
### 星级 IV

<!-- 仅品质为强力的角色可用 -->
### 星级 V

## 等价属性
此处列出 Kaplan Steve 在其他游戏作品模拟的属性值

| 游戏作品常用名称                      | 属性键  | 属性值 |
| ----------------------------- | ---- | --- |
| 原神（`Genshin Impact`）          | 神之眼  | 雷   |
| 原神（`Genshin Impact`）          | 武器   | 单手剑 |
| 星穹铁道（`Star Rail`）             | 战斗属性 | 雷   |
| 星穹铁道（`Star Rail`）             | 战斗命途 | 虚无  |
| 绝区零（`Zenless Zone Zero`）      | 属性   | 电属性 |
| 绝区零（`Zenless Zone Zero`）      | 特性   | 强攻  |
| 我的世界地下城（`Minecraft Dungeons`） | 伤害类型 | 雷电  |

