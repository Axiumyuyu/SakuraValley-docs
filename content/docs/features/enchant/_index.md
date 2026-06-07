---
title: "附魔"
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
# bookHref: ''
# bookIcon: ''
---

我对原版的附魔做了一些调整，同时还增加了大量来自数据包的附魔，这些附魔会在探索中被逐渐发现，在附魔台中也可能被发现。

## 数据包附魔

几个主要数据包的附魔帮助链接

- [Enchantments Encore](https://wiki.explorerseden.eu/en/enchantments_encore/home)

- [Neo Enchant+](https://hardels-organization.gitbook.io/voxel/neo-enchant/enchantment)

## 原版附魔的改动

这里列出了一部分原版附魔的改动，同时大多数附魔的最大等级均已提升

查看[BeyondEnchant](https://modrinth.com/datapack/beyondenchant)获取等级列表

### 锋利和保护

这两个附魔的最大等级现在都是3，而且必须在武器已经拥有了任意攻击/防御属性（见[属性系统](../pve/battle/)）后，才可以使用这两个附魔，在此之前，你无法将一个没有属性的武器和护甲打上锋利或保护，不管是使用铁砧还是附魔台。

### 经验修补

最大等级上限扩展至 5 级，并引入了耐久上限损耗机制，当装备通过吸收经验来恢复当前耐久时，会有一定的概率永久扣除该装备的最大耐久上限。

经验修补的等级将直接影响修补的收益与风险：

- 随着附魔等级的提升，吸收同等经验所恢复的耐久值将呈线性增长

- 附魔等级越高，触发永久扣除最大耐久上限的概率越低

> 建议：**尽可能只使用高等级的经验修补附魔**

### 耐久

最大等级提升为10，针对护甲，耐久保护物品免受耐久度下降的概率现在为

下降概率 = 25% + (75%/耐久等级)

### 亡灵杀手

最大等级提升为10，同时每提升一级带来的伤害加成从2.5降为1.5



## 部分附魔的更改

Pull 附魔现在的功能为，固定消耗物品默认最大耐久的10%的最大耐久，在击杀指定生物时掉落一个该生物的刷怪蛋

以下附魔的功能被移除：

- Sacrifice 
- Bedrocker(基岩破坏者)
- Glunnoty