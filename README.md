# 【正义之怒】内容扩展型MOD收集计划
-------------------------------------------

+ 本文档用于收集整理为开拓者正义之怒提供内容扩充（新增或者修改职业、变体、专长、法术等游戏内容）的MOD，并尽量保持时效性。
+ ToyBox、Bubble Buffs等功能性MOD不在本文档介绍范围。
+ 特别注意，本文档作者的游戏理解还是新手，很可能评价并不贴切。
+ 强烈建议先行阅读[正义之怒MOD教程](https://github.com/1onepower/KM-WotR_Modding_Wiki/blob/main/%E4%B8%AD%E6%96%87%E7%89%88.md) （1onepower）。该文档含有详细的**UMM安装教程**和部分MOD介绍，但文档时间较早，部分MOD可能已经失效。

## 目录
[TOC]
- [基础知识](#前置安装)
  - [UMM的安装](#UMM的安装)
  - [MOD须知](#MOD须知)
  - [ModFinder工具](#ModFinder工具)
  - [GITHUB访问和MOD下载](#GITHUB访问和MOD下载)
  - [Nexus访问和MOD下载](#Nexus访问和MOD下载)
  - [前置MOD](#前置MOD)
  - [汉化修正文件](#汉化修正文件)
- [MOD列表](#MOD列表)

## 基础知识

### UMM的安装
+ UMM是**Unity Mod Manager**的简称，用于很多Unity游戏的MOD管理。对正义之怒UMM基本属于必需的前置MOD管理工具。你需要先安装UMM来启用MOD，并可对MOD进行统一管理。
+ 大部分MOD都通过UMM来进行安装和管理。少部分例外我会特别提示。
+ 关于UMM的安装，[上面链接](https://github.com/1onepower/KM-WotR_Modding_Wiki/blob/main/%E4%B8%AD%E6%96%87%E7%89%88.md) 已经有非常详细的阐述，在此不再赘述。

### MOD须知
+ 特别注意。目前绝大多数内容扩充MOD都可以随时在游戏中途新增并**正常添加内容**。
+ 但是绝对不要在游戏**中途移除内容扩充MOD**，通常这都会由于新增特性的丢失导致**存档无法载入**。如果遇到这种情况，**通常加回MOD可以解决**。
+ 绝大多数内容扩充MOD会提供**MOD选项**，可以用于单独开启或者关闭某一项特性。通常这个选项在UMM中，如果前置有**ModMenu**，则在游戏选项中的MOD页面。
+ 一般来说，修改性质的选项（比如TTT对专长的相关修改），都可以随时开关（但都需要**重启游戏才能生效**）。但是新增内容（比如增加专长）一旦已经有人物使用后关闭，很可能同样导致**存档无法载入**。**一般重新启用选项可以解决**。

### ModFinder工具
+ ModFinder是一个非必需的第三方工具，可以便捷的管理正义之怒MOD，检查MOD更新情况（包括在Github和Nexus更新的MOD），快速下载和安装（可以替代部分UMM功能）
+ ModFinder可以在[这里](https://github.com/Pathfinder-WOTR-Modding-Community/ModFinder)下载。
+ ModFinder为绿色工具，可以在任何路径打开（但是最好不要用中文路径），会自动识别正义之怒的安装位置。
+ ModFinder在启动时可能会出现弹框错误，发生此种情况多半是Github访问失败的导致的，请参照下一节解决。

### GITHUB访问和MOD下载
+ 在国内很多网络环境，Github访问都存在一定抽风现象，会出现时不时打开失败。通常刷新就可以解决。如果实在问题严重，[Watt Toolkit](https://steampp.net/)可以帮到你。
+ 给予完全萌新的提示：大部分MOD发布页中，直接点击右侧**Releases** 按钮即打开下载页面，Assets中第一项即为MOD。下载后不需要解压缩，直接使用UMM或者ModFinder安装。

### Nexus访问和MOD下载
+ Nexus的MOD在标题右方的Manual按钮即可直接下载。如果有额外文件会在FILES标签中。
+ Nexus目前需要注册用户才能下载。

### 前置MOD
目前正义之怒所需主要前置MOD有两个：
1. [TabletopTweaks-Core](https://github.com/Vek17/TabletopTweaks-Core)（**核心必备**，绝大部分MOD的基础框架，本身不会进行任何改动。）
2. [ModMenu](https://github.com/WittleWolfie/ModMenu)（**非必备**，一部分MOD使用的基础框架。会在游戏中选项里添加一个新的页面来进行MOD功能调整。）

### 汉化修正文件
+ 本文档上方会收集一些个人提供的MOD汉化或汉化修正文件，不定时更新。
+ 可以点击上方code按钮中的Download Zip打包下载。
+ 一般*UMM安装*的MOD，汉化文件的使用方法是直接替换游戏目录下\mods\对应mod名称\Localization\中同名文件即可。
+ 但是某些MOD没有语言文件，有些替换后无效，我就不知道咋办了。
+ 文档作者是代码盲，需要大佬协助233

-------------------------------------------

## MOD列表
**本列表中MOD均在2.0.7版本测试通过**
-------------------------------------------
### [TabletopTweaks-Base](https://github.com/Vek17/TabletopTweaks-Base)
> *前置：* TabletopTweaks-Core<br>
> *中文：* 自带中文（部分内容没更新）<br>
> *安装方式：* UMM<br>
> *修改内容：* UI、核心规则、法术、专长、职业特性、神话能力、神话专长，等<br>
> *新增内容：* 变体、巅峰、法术、专长、种族、背景，等<br>
+ 简称**TTT**，提到正义之怒MOD就必定会提到TTT，基本上也是大部分人第一个玩的内容型MOD。
+ 新增了海量的游戏内容，让游戏完全变了个样的同时，也提供了很多新的选项。
> 例如，新增的重甲系两个神话专长可以进一步提升重甲提供的AC，同时降低重甲的惩罚，让玩家在无甲+大法师护甲外有了额外选项。<br>
> 新增的奥术发现专长可以让法师的变化系法术（动物园系列）提供额外属性加成，20级达到+8，是的玩家拥有属性头带腰带外的大量选择。<br>
> 新增的巅峰系统给很多纯职都提供了福利
+ 特别需要注意的是，TTT对原版做出了大量修改，尤其是**良性BUG**方面。
> 典型的包括<br>
> **甄选法术不能再对持续性AOE法术生效**<br>
> **扩充战法不能再由多系专攻获得大量DC**<br>
> **游荡者天赋中额外战斗专长只能选一次**<br>
> **AOE法术不会在释放时额外触发一次**<br>
> 等等<br>
+ 如果你习惯了原版体系和构建，可能用了TTT会有极大怨言。好在这些修复都是可以关闭的<br>
+ （友情提示，但是由于新增了大量内容，关闭这些修复很容易导致过于滥强）<br>
+ TTT的更新过于庞杂海量，建议有一定英文基础和游戏基础再玩（虽然内容已经汉化但是选项菜单无法汉化）

<table>
<tr><th colspan="2">新增内容列表</th></tr> 
<tr><td>基础能力</td>
    <td>单手持用：在加载TableTopTweaks后，许多需要你空出一只手的能力*真的*需要你空出一只手。激活此能力以强制单手握持你的武器，你会因此只能将1倍调整值应用在伤害上而不是1.5倍。</td>
</tr> 
<tr><td rowspan="7">变体</td>
      <td>Arcanist - Elemental Master 奥能师 - 元素大师</td></tr>
  <tr><td>Bloodrager - Metamagic Rager 血怒者 - 超魔狂怒者</td></tr>
  <tr><td>Cleric - Channeler Of The Unknown 牧师 - 熵化导能师</td></tr>
  <tr><td>Magus - Blade Bound 魔战士 - 剑缚者</td></tr>
  <tr><td>Druid - NatureFang 德鲁伊 - 自然之牙</td></tr>
  <tr><td>Warpriest - Divine Commander 战争祭祀 - 神圣骑手</td></tr>
  <tr><td>Witch - Cauldron Witch 巫师 - 炼药巫师</td></tr>
<tr><td>巅峰</td>
      <td>TTT新增，当一个角色在某一职业上达到20级可以选择一个巅峰奖励。部分巅峰只供特定职业选择，另外一些则为通用。<br>
        原版游戏中已经有不少职业拥有所谓“20级大招”。在TTT中将其与巅峰进行了整合。你可以在选择巅峰时选择原有“20级大招”，但是如此你便不能选择其他巅峰奖励。<br>
        <b>重要</b>：若角色通过变体更换了职业原本的“20级大招”，那么他也无法选择其他巅峰，这条规则对<b>其他MOD职业</b>同样适用<br>
      <b>完化身心</b>：通用巅峰。角色属性总值增加8点。可以自由选择加点。<br>
      <b>伟兽</b>：通用巅峰。拥有动物伙伴可以选择。动物伙伴的力量、敏捷、体质与智慧各增加4。<br>
      <b>推陈出新</b>：通用巅峰。职业具有至少4个奖励战斗专长可以选择。再获得4个奖励战斗专长。<br>
      其他职业还各自有不同的巅峰选择，例如法师可以获得额外法术位，在此不再一一列出。
      </td></tr>
<tr><td rowspan="6">法术</td>
      <td>Cloak of Winds 风之斗篷：敌方远程攻击受到惩罚</td></tr>
  <tr><td>Long Arm 长臂咒：增加触及</td></tr>
  <tr><td>Mage's Disjunction <b>法师裂解术</b>：无豁免驱散/过穿戴者意志豁免使得魔法物品失效，逆天</td></tr>
  <tr><td>Shadow Enchantment 阴影惑控：幻术系模拟惑控</td></tr>
  <tr><td>Shadow Enchantment Greater 高等阴影惑控：楼上的高级版</td></tr>
  <tr><td>Stunning Barrier Greater 重型重创壁垒：防御法术</td></tr>
<tr><td rowspan="59">专长</td>
  <tr><td>Metamagic (Burning Spell) 超魔（燃烧法术）</td></tr>
  <tr><td>Metamagic (Encouraging Spell) 超魔（激励法术）</td></tr>
  <tr><td>Metamagic (Flaring Spell) 超魔（闪耀法术）</td></tr>
  <tr><td>Metamagic (Intensified Spell) 超魔（强化法术）</td></tr>
  <tr><td>Metamagic (Piercing Spell) 超魔（法术穿刺）</td></tr>
  <tr><td>Metamagic (Rime Spell) 超魔（霜冻法术）</td></tr>
  <tr><td>Metamagic (Solid Shadows) 超魔（真实阴影）</td></tr>
  <tr><td>Metamagic (Elemental Spell) 超魔（元素魔法）</td></tr>
  <tr><td>Ability Focus - Stunning Fist </td></tr>
  <tr><td>Animal Ally </td></tr>
  <tr><td>Celestial Servant </td></tr>
  <tr><td>Dervish Dance </td></tr>
  <tr><td>Dispel Focus </td></tr>
  <tr><td>Greater Dispel Focus </td></tr>
  <tr><td>Erastil's Blessing </td></tr>
  <tr><td>Expanded Spell Kenning </td></tr>
  <tr><td>Extra Arcana </td></tr>
  <tr><td>Extra Arcanist Exploit </td></tr>
  <tr><td>Extra Discovery </td></tr>
  <tr><td>Extra Hex </td></tr>
  <tr><td>Extra Ki </td></tr>
  <tr><td>Extra Mercy </td></tr>
  <tr><td>Extra Reservoir </td></tr>
  <tr><td>Extra Revelation </td></tr>
  <tr><td>Extra Rogue Talent </td></tr>
  <tr><td>Extra Slayer Talent </td></tr>
  <tr><td>Graceful Athlete </td></tr>
  <tr><td>Improved Channel </td></tr>
  <tr><td>Lunge </td></tr>
  <tr><td>Lunging Spell Touch </td></tr>
  <tr><td>Magical Aptitude </td></tr>
  <tr><td>Mantis Style </td></tr>
  <tr><td>Mantis Wisdom </td></tr>
  <tr><td>Mantis Torment </td></tr>
  <tr><td>Mounted Skirmisher </td></tr>
  <tr><td>Nature Soul </td></tr>
  <tr><td>Two-Weapon Defense </td></tr>
  <tr><td>Quick Channel </td></tr>
  <tr><td>Quick Draw </td></tr>
  <tr><td>Quicken Blessing </td></tr>
  <tr><td>Riving Strike </td></tr>
  <tr><td>Scholar </td></tr>
  <tr><td>Self-Sufficient </td></tr>
  <tr><td>Shingle Runner </td></tr>
  <tr><td>Greater Spell Specialization </td></tr>
  <tr><td>Stalwart </td></tr>
  <tr><td>Improved Stalwart </td></tr>
  <tr><td>Trick Riding </td></tr>
  <tr><td>Undersized Mount </td></tr>
  <tr><td>Varisian Tattoo </td></tr>
  <tr><td>Armor Mastery Feats - Intense Blows</td></tr>
  <tr><td>Armor Mastery Feats - Knocking Blows</td></tr>
  <tr><td>Armor Mastery Feats - Secured Armor</td></tr>
  <tr><td>Armor Mastery Feats - Sprightly Armor</td></tr>
  <tr><td>Defended Movement </td></tr>
  <tr><td>Stumbling Bash </td></tr>
  <tr><td>Toppling Bash </td></tr>
  <tr><td>Tower Shield Specialist </td></tr>  
</table>

-------------------------------------------
### [TabletopTweaks-Reworks](https://github.com/Vek17/TabletopTweaks-Reworks)
> *前置：* TabletopTweaks-Core<br>
> *中文：* 自带中文（存在小问题）<br>
> *安装方式：* UMM<br>
> *修改内容：* 神话能力、神话专长，道途等<br>
+ **TTT**的扩展附件，主要集中在**神话道途**的修改
+ 对神话能力、神话专长、道途均有修改，也导致很多人不习惯
> 比较重点（坑爹）的修改：<br>
> **充裕施法**数量减半<br>
> **高等持久法术**现在只能对持续10分钟以上法术生效，再也没法轮级常驻了<br>
+ 其他还包括对神话偷袭的修改（从多1骰变为骰子放大1级）。对御衡、灵使、巫妖、诡计均有修改，尤其是诡计几乎大变样
> 目前发现问题：灵使惊世神力改为了其他加值，但是文本描述依然是士气加值
