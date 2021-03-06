# AshArmsData
Repository containing the data for the game Ash Arms.

# Bugs(zh-CN)

**修復良性 Bug 前請審慎評估將對代理人造成之影響**
有發現任何其餘 Bug 歡迎 PR

Bug 暫時分類為以下三種 Tag
* 惡性
  * 正面效果無法發動，導致收益不如預期。
  * 實際效果低於文本效果
* 中性
  * 效果錯誤，失去預期效果但帶來額外收益
* 良性
  * 負面效果無法發動，導致收益優於預期。
  * 實際效果優於文本效果

敘述為格式如下
```
## Doll/Item Name
* Skill Set
  * Tag
  * Expected
  * Actual
  * Comment(Optional)
```

### 制空(職能)
* ~~能量猎杀~~(Fix in 12/08)
 * 中性
 * [暴露][强袭][势能α][突击]
 高空对空射击技能。本次攻击自身【暴击概率】大幅上升。如自身【反应值】高于目标，攻击后可追加一次攻击。攻击后，变为低空形态，自身【机动性】大幅提升。赋予自身【被标记】状态，持续1回合。自身前进1格。
 * [暴露][强袭][势能α][突击]
 高空对空射击技能。本次攻击自身【暴击概率】大幅上升。攻击后可追加一次攻击。攻击后，变为低空形态。赋予自身【被标记】状态，持续1回合。自身前进1格。

### IL-2M3
* 断钢神剑I
  * 惡性
  * 造成敌人堆叠减少时,自身火力值中幅提升（2回合不可叠加）
  * 造成敌人堆叠减少时,自身對空火力值中幅提升（2回合不可叠加）
* 断钢神剑II
  * 惡性
  * 造成敌人堆叠减少时,自身火力值中幅提升（2回合不可叠加）攻击轻型单位时小幅增加火力值
  * 造成敌人堆叠减少时,自身對空火力值中幅提升（2回合不可叠加）攻击轻型单位时小幅增加對空火力值

### 迅捷怒火
* 迅捷怒火Ⅰ
  * 惡性
  * 装备者的【暴击概率】每回合提升3%（最高9%）；攻击造成暴击时，【暴击伤害】提升15%，持续3回合。
  * 装备者的【暴击概率】每回合提升3%（最高9%）；攻击造成暴击时，【暴击伤害】提升0%，持续3回合。
* 迅捷怒火ⅠⅠ
  * 惡性
  * 装备者的【暴击概率】每回合提升5%（最高15%）；攻击造成暴击时，【暴击伤害】提升25%，持续3回合。
  * 装备者的【暴击概率】每回合提升5%（最高15%）；攻击造成暴击时，【暴击伤害】提升0%，持续3回合。
* 迅捷怒火ⅠⅠⅠ
  * 惡性
  * 装备者的【暴击概率】每回合提升10%（最高30%）；攻击造成暴击时，【暴击伤害】提升35%，持续3回合。
  * 装备者的【暴击概率】每回合提升10%（最高30%）；攻击造成暴击时，【暴击伤害】提升0%，持续3回合。

### AD-4 天袭者
* 全弹发射·改
  * 良性
  * 超强力对地射击技能。本次攻击自身【对地火力】大幅提升。攻击后，自身对地【火力】大幅降低，持续1回合，且自身【对地火力】无法再次提升。
  * 超强力对地射击技能。本次攻击自身【对地火力】大幅提升。攻击后，自身对地【火力】大幅降低，持续1回合。
 
### XF2M
* 轻战集群·改
  * 良性
  * 己方回合开始时，如自身与其他轻型战斗机单位相邻，自身所处区域上所有轻型战斗机【对空命中】提升10%，持续1回合，不可叠加。
  * 己方回合开始时，如自身与其他轻型战斗机单位相邻，自身所处区域上所有轻型战斗机【对空命中】提升10%，【爆击概率】提升，持续1回合，不可叠加。
  * 僅列出滿級數據

### P-51D 野马
* 轻战集群·改
  * 良性
  * 己方回合开始时，如自身与其他轻型战斗机单位相邻，自身所处区域上所有轻型战斗机【对空命中】提升10%，持续1回合，不可叠加。
  * 己方回合开始时，如自身与其他轻型战斗机单位相邻，自身所处区域上所有轻型战斗机【对空命中】提升10%，【爆击概率】提升，持续1回合，不可叠加。
  * 僅列出滿級數據
 
### B-24D 解放者
* 轰炸引导·专业
  * 良性
  * 己方回合开始时，所有星尘联邦学联空中单位【对地火力】和【命中】提升15%。
  * 己方回合开始时，所有己方空中单位【对地火力】和【命中】提升15%。
  * 僅列出滿級數據
 
### Do-335A-0
* 天外飞箭（钝头）
  * 良性
  * 对目标进行强力射击，如果本回合向前移动两格或以上距离，使目标【瘫痪】，持续1回合。
  * 对目标进行强力射击，如果本回合向前移动两格或以上距离，攻击后选取攻击范围内一个目标赋予【瘫痪】，持续1回合。
 
### P-47D 雷电
* 高速时代
  * 良性
  * 自身被攻击时，若空中目标【反应】低于自身，则自身【机动】提升20%，同时星尘联邦学联战斗机【对空火力】提升11%。
  * 自身被攻击时，若目标【反应】低于自身，则自身【机动】提升20%，同时星尘联邦学联战斗机【对空火力】提升11%。
  * 僅列出滿級數據
