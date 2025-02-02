# 龙骑士
<FloatTOC />

## 综合介绍

长枪是遍布艾欧泽亚的主要武器，枪术士行会所在的黑衣森林的住民就使用长枪狩猎，而伊修加德的龙骑士则使用长枪发展出在空中与龙交战的战技。

龙骑士是3.0的主角，苍天的伊修加德，苍天的龙骑士，整个龙诗战争就是人与龙之间的斗争。如果你有50级以上的龙骑士职业，那么你在3.0主线任务中，会有一部分NPC出现不同的台词。

龙骑的主要输出手段是使用蹦跳技能和常规5连击开启红龙血，并打出龙眼之力。因为这是在3个版本中逐渐开放的功能，所以50级、60级和70以上的龙骑会拥有3种节奏不同的输出手法。

相对于其他几个近战物理职业来说，龙骑机动性比较好，但他的技能有一定的身位要求，否则也无法打出完美的循环。龙骑的缺点同样来自于其机动性，因为他的所有蹦跳类技能的硬直动画都极长，导致不熟悉副本时间轴的龙骑（还有瞎78浪的龙骑）经常会在脚下出现BOSS攻击圈的时候，因为技能动画僵直而无法移动…然后惨惨地躺在地板上（或者浪操作一个后跳飞身坠落）。这也是龙骑经常被戏称为放LB的躺尸龙的主要原因之一。

龙骑在这个版本中已经有了极强的输出能力，加上自身的帅气加持，是各方面都很均衡，也是比较适合新人上手的职业。

## 龙骑入门

想以龙骑士开始游戏的玩家，可以在建号的时候选择==枪术师==进入游戏。其他玩家完成自己职业10级的职业任务之后，在格里达尼亚接任务<quest name="如何加入枪术师行会" />，并继续<quest name="开拓进取的枪术师" />任务，就可以获得长枪并转职为枪术师了。

完成枪术师30级职业任务<quest name="勇气的证明" type="plus" />，就会开启龙骑士的转职任务<quest name="龙眼" type="plus" />，完成任务获得<item name="龙骑士之证" />并装备上，就正式成为一名龙骑士了！

## 练级手法

龙骑的输出主要是2套5连GCD战技，然后依托巨龙怒目的档数（俗称龙眼），继而使用威力更大的技能。因此龙骑在54级掌握龙血之后，到68级掌握幻象冲之前的技能循环会有一些混乱。但是随着等级提升，围绕着龙血而铺开的技能循环会变得愈加流畅。

龙骑曾经是一个对身位要求比较高的职业，现在仅有3个技能要求身位，但这3个身位技能却对龙骑的输出影响深远，不可掉以轻心。

### 对单体输出

龙骑的基本技能连击是<Action name="精准刺" /> → <Action name="贯通刺" /> → <Action name="直刺" />（86级升级为<Action name="苍穹刺" />） 和 <Action name="精准刺" /> → <Action name="开膛枪" /> → <Action name="樱花怒放" />（背，86级升级为<Action name="樱花缭乱" />），在56级和58级之后，这两套连击会分别再依序加上两个技能：**直刺连** → <Action name="龙牙龙爪" />（侧）和 **樱花连**（背） → <Action name="龙尾大回旋" />（背），构成2套4连循环；64级之后则可以在4连之后再追加另一个龙尾大回旋/龙牙龙爪。一共7个技能，构成2套5连循环，听起来可能比较复杂，但合理安排技能键位，找个木桩摸两下就会发现还是挺简单的。

练级期间的龙骑首先应该保证这2套5连技能（一开始是3连，然后变成4连，一般以第三连，即++樱花++和++直刺++来称呼这两套连击）的顺序和身位不犯错。开怪后先打樱花连（开膛会为玩家附加<Status :id="2720" name="龙枪" />10%伤害提升，樱花则是对目标上DOT），然后保证龙枪和樱花不断的前提下，尽可能多地打直刺连。在5连循环成型之后，应该正好是一套樱花连，一套直刺连重复。

70级开始可以使用<Action name="跳跃" />（74升级为<Action name="高跳" />） → <Action name="幻象冲" /> 来获得巨龙怒目，巨龙怒目2档时，量谱显示“开眼”状态，此时使用<Action name="武神枪" />（俗称龙炮、或蓝龙炮）就能够进入红莲龙血状态，龙炮也会变为<Action name="死者之岸" />（俗称红龙炮）。

在获得红龙血之前，能力技好了就放即可，获得红龙血之后，需要按照<Action name="武神枪" />/<Action name="高跳" />（顺序可交换） → <Action name="幻象冲" />的穿插顺序施放（这三个技能都是能力技，需要采用1个战技+1~2个能力技的穿插方式进行输出，否则会[浪费GCD](/basic/battle-mech.md)；这个顺序是为了方便满级后对齐团队辅助而决定的，在4人本中也可以先打高跳→幻象冲，再打武神枪，需要具体情况具体分析）。巨龙怒目攒满后使用龙炮进入红龙血，并保证在红龙血期间使用3次<Action name="死者之岸" />（78级之前是2次）和1次<Action name="坠星冲" />。

龙骑的<Action name="贯穿尖" />（俗称扔标枪）是在无法靠近Boss时的补充输出技能，保证不浪费GCD。

最后，<Action name="破碎冲" />和<Action name="龙炎冲" />两个技能都是带有位移效果的能力技，可以从远距离快速靠近BOSS，由于是能力技不会占用GCD，因此在没有特殊情况的时候可以好了就放。但是这两个技能以及跳跃的动画硬直都比较长，容易发生跳完了卡硬直死于AOE的情况（跳跃升级为高跳之后有些许改善），另外就是在某些多动症BOSS喜欢高速移动，或大量小怪过于分散时，这些跳跃类技能都会成为优秀的追击技能。因此龙骑玩家一方面要勇于尝试，积极吸取教训，另一方面也要记得对你们的治疗好一点，毕竟你犯的问题都是治疗在救你。

### 群体AOE

龙骑的AOE循环是<Action name="死天枪" /> → <Action name="音速刺" /> → <Action name="山境酷刑" />，另外龙炮、红龙炮、坠星冲、龙炎冲都是AOE技能，需要注意的是，AOE三连以及龙炮、红龙炮是直线AOE，而坠星冲和龙炎冲是目标周围5m范围AOE，因此使用过龙炎冲和坠星冲再使用其他AOE技能时，注意调整自己的位置和面向，以防打空。

### 辅助与应急

龙骑有比较多的buff类技能，如何安排buff也是满级龙骑需要思考的主要问题之一。简略说明如下：

* <Action name="龙剑" />，下次战技必暴击，这个技能固定绑定直刺，即<Action name="精准刺" /> → <Action name="贯通刺" /> → <Action name="龙剑" /> → <Action name="直刺" />。在AOE的场合也可以绑定山境酷刑或音速刺（看当前等级，绑定给威力大的），这样你可以收货一串暴击。满级后龙剑可以积蓄2层，用法请参照满级攻略。
* <Action name="猛枪" />，俗称舍身（是以前的名字，部分攻略仍旧会叫它舍身，要注意）。作为主要爆发类技能，需要覆盖自己的主要伤害技能（包括樱花、各种跳）。
* <Action name="巨龙视线" />，俗称龙视或龙肠，需要指定一名队友作为目标，自身伤害提高10%，队友伤害提高5%。通常会给近战队友，或队伍里输出最高的（或者你最喜欢的ta）。虽然现在龙眼没有队友目标也能使用，但这样是挺亏的，除非自己野外solo战斗，否则不推荐这么做。
* <Action name="战斗连祷" />，提升10%暴击发动率，这个技能的收益不是特别高，通常配合团辅在团队爆发期里使用。

掉血的时候可以有<Action name="内丹" />、<Action name="浴血" />回血，治疗通常对龙骑都会有[莫名的宽容](https://nga.178.com/read.php?tid=18627908)，但总让治疗关照总是不太好的，一个优秀的龙骑不会在同一个地方死两遍。

## 满级手法

> 因精力有限，本站无法提供满级手法参考，可前往NGA论坛查找[龙骑的满级攻略](https://nga.178.com/thread.php?key=%E9%BE%99%E9%AA%91&fid=698)