# 特性列表

## 发射器发射龙息（dispensersFireDragonBreath）

龙息可以在发射器里被发射

- 类型: `boolean`
- 数值：`true`

## 蠹虫掉落沙砾（silverFishDropGravel）

杀死蠹虫掉落沙砾

- 类型: `boolean`
- 数值: `true`

## 监视器更新间隔（HUDLoggerUpdateInterval）

覆写Carpet Mod HUD监视器的更新间隔，单位为`gametick`

- 类型: `int`
- 数值: `2`

## 可再生龙首（renewableDragonHead）

当末影龙被闪电苦力怕炸死，掉落龙首

- 类型: `boolean`
- 数值: `true`

## 语言（language）

设置地毯端语言

- 类型: `String`
- 数值: `zh_cn`

## 寻路AI(commandTrackAI)

允许通过`/track`命令跟踪怪物AI

- 类型: `boolean`
- 数值: `false`

## 距离测量（commandDistance）

启用`/distance`命令来测量游戏中点之间的距离

- 类型: `boolean`
- 数值: `false`

## 袭击追踪（commandRaid）

启用 `/raid` 命令用于追踪袭击信息

- 类型: `boolean`
- 数值: `false`

## 假人相关（commandPlayer）

启用`/player`命令来控制或生成玩家

- 类型: `boolean`
- 数值: `true`

## 龙蛋破基岩修复（dragonEggBedrockBreaking）

修复龙蛋用于破基岩

- 类型: `boolean`
- 数值: `true`

## 缺失工具修复（missingTools）

补全方块对应的破坏工具

- 类型: `boolean`
- 数值: `true`

## 漏斗计数器（hopperCounters）

统计物品效率

- 类型: `boolean`
- 数值: `true`

## 生成相关（commandSpawn）

启用`/spawn`命令跟踪生物生成

- 类型: `boolean`
- 数值: `false`

## 推容（movableBlockEntities）

活塞可推动箱子、漏斗等容器

- 类型: `boolean`
- 数值: `true`

## 可再生珊瑚（renewableCoral）

可以使用骨粉使珊瑚再生

- 类型: `boolean`
- 数值: `true`

## 潜影贝再生（shulkerSpawningInEndCities）

潜影贝会在末地城重新生成

- 类型: `boolean`
- 数值: `true`

## 假人后缀（fakePlayerNameSuffix）

使用`/player`召唤假人自动添加后缀

- 类型: `String`
- 数值: `_bot`

## 客户端平滑动画（smoothClientAnimations）

平滑客户端动画

- 类型: `boolean`
- 数值: `true`

## 自动合成（autoCraftingDropper）

投掷器面朝工作台并给出一次脉冲，会以投掷器的3*3为配方合成

- 类型: `boolean`
- 数值: `true`

## 矿车填充（dispensersFillMinecarts）

矿车可以装满漏斗、箱子、tnt和熔炉

- 类型: `boolean`
- 数值: `true`

## 刷沙机修复（sandDupingFix）

禁用使用末地门的刷沙机以及刷重力方块机

- 类型: `boolean`
- 数值: `true`

## 默认监视器（defaultLoggers）

为所有新玩家订阅监视器

- 类型: `String`
- 数值: `mobcaps,tps`

## TNT爆炸优化（optimizedTNT）

TNT在同一地点和液体中爆炸时，会产生较少的卡顿

- 类型: `boolean`
- 数值: `true`

## 楼梯方向放置修复（placementRotationFix）

修正了当玩家在放置楼梯时的旋转问题

- 类型: `boolean`
- 数值: `true`

## 方块状态同步（blockStateSyncing）

修复了某些块在F3调试模式下未更新的块状态

- 类型: `boolean`
- 数值: `true`

## TNT复制修复（tntDupingFix）

禁用TNT、地毯以及部分铁轨的复制机

- 类型: `boolean`
- 数值: `ture`

## 订阅监视器（commandLog）

启用`/log`命令来订阅监视器

- 类型: `boolean`
- 数值: `true`

## 合成修复（ctrlQCraftingFix）

可以使用`ctrlQ`来扔出整组待合成物品

- 类型: `boolean`
- 数值: `true`

## 堆积冰（renewablePackedIce）

可以使用下落的铁砧将多块冰压缩成浮冰

- 类型: `boolean`
- 数值: `true`

## 红石粉优化（fastRedstoneDust）

红石粉的卡顿优化

- 类型: `boolean`
- 数值: `true`

## 可再生鞘翅（renewableElytra）

当幻翼被潜影贝杀死时有给定概率掉落鞘翅

- 类型: `double`
- 数值: `0.2`

## 旋转方块（rotatorBlock）

当仙人掌在发射器里并激活，可以选择前面的方块（类似仙人掌扳手）

- 类型: `boolean`
- 数值: `true`

## 海绵可再生（renewableSponges）

当守卫者被闪电劈中，变为远古守卫者

- 类型: `boolean`
- 数值: `true`

## 怪物修复（reloadSuffocationFix）

不会让怪物在重新加载时出现故障。修复MC-2025

- 类型: `boolean`
- 数值: `true`

## 反作弊修复（antiCheatDisabled）

防止玩家在`moving too fast`和`flying`被踢出服务器

允许玩家的挖掘距离到32

- 类型: `boolean`
- 数值: `true`

## 树苗干枯（desertShrubs）

当树苗在没有水源的地方活炎热的地方变成枯死的灌木

- 类型: `boolean`
- 数值: `true`

## 尸壳生成（huskSpawningInTemples）

只有尸壳在沙漠神殿生成

- 类型: `boolean`
- 数值: `true`

## 时钟读取（comparatorReadsClock）

允许比较器读取白天，而不是旋转的时钟

- 类型: `boolean`
- 数值: `true`

## Tick相关（commandTick）

允许使用`/tick`命令来控制游戏时间

- 类型: `boolean`
- 数值: `false`

## 绘制（commandDraw）

启用`/draw`命令，允许绘制简单的形状或其他形状，这些形状通常很难完成

- 类型: `boolean`
- 数值: `false`

## 传送门窒息修复（portalSuffocationFix）

地狱门正确的传送实体，不会再黑曜石中窒息

- 类型: `boolean`
- 数值: `true`

## 沙子再生（renewableSand）

下落的铁砧可以将圆石变为沙子

- 类型: `boolean`
- 数值: `true`

## 方块信息（commandInfo）

为方块启用`/info`命令

- 类型: `boolean`
- 数值: `false`

## 可再生龙蛋（renewableDragonEgg）

让龙蛋变得可再生

当龙蛋处于龙息效果云内时，龙蛋有一定概率吸收龙息并“召唤”出一个新的龙蛋

可与选项 `dispenserFireDragonBreath`联动

- 类型: `boolean`
- 数值: `true`

## 仙人掌扳手（flippinCactus）

可以使用仙人掌来旋转方块

- 类型: `boolean`
- 数值: `true`

## 生成卡顿优化（lagFreeSpawning）

减少生成所需的CPU和内存

- 类型: `boolean`
- 数值: `true`

## 苦力怕生成（creeperSpawningInJungleTemples）

只有苦力怕会生成在丛林神庙

- 类型: `boolean`
- 数值: `true`

## 单人睡觉（onePlayerSleeping）

只要有一个玩家在睡觉即可跳过夜晚

- 类型: `boolean`
- 数值: `true`
