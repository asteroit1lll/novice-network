# 绝枪战士
<FloatTOC />

## 综合介绍

在第三星历时代，硌狮族作为少数民族拥有一种奇特的武器==枪刃==，他们认为枪代表女王的崇高地位，而其他的后来之“枪”都是虚假的，当时的女王亲卫队为了灭绝一切虚伪之枪，而拥有了绝枪战士的名号。

绝枪战士作为5.0追加的T职业，有着优异的输出和令DPS都羡慕的爆发伤害，虽然操作在目前的4个T之中算复杂的，但是这是值得的。不光有基础的队友护盾，还有单独的队友治疗，非常适合作为MT。

## 枪刃入门

枪刃不能作为进入游戏时的初始职业，需要有任意一个战斗职业到达60级之后，在森都接任务<quest name="成为绝枪战士" />，并获得枪刃，就能成为绝枪战士了。

枪刃属于坦克职业，想要玩枪刃的玩家，推荐以==斧术师==进入游戏，或者在[新人直升活动](/before/pay.md#萌新招待领多重福利)中选择骑士/暗黑骑士/战士直升包，然后接任务<quest name="成为绝枪战士" />转职。

## 练级手法

枪刃的盾姿是<Action name="王室亲卫" />(10)，使用王室亲卫之后，所有技能都会附加10倍基础仇恨。只要开着盾姿正常输出，理论上说几乎是很难OT的。

只要枪刃在MT的位置，就必须保持盾姿<Status :id="392" name="王室亲卫" />常驻，反之自己如果不是MT，就需要把它关掉。

绝枪战士作为一个T职业，除了需要掌握自身的输出、减伤等技能运用的同时，还需要有控场意识。可以阅读[T职基础攻略](https://nga.178.com/read.php?tid=19311442)和[四人副本-坦克必备意识和技巧集锦](https://nga.178.com/read.php?tid=15417017)这两篇文章，更详细了解T职业的减伤、空防，以及部分副本的应对实例。

### 对单体拉怪/输出

枪刃的基础输出连是<Action name="利刃斩" />→<Action name="残暴弹" />→<Action name="迅连斩" />，52级之后的<Action name="残暴弹" />还会为自己附加一个护盾，可谓是输出、治疗、防护三位一体的连击技能。同时，30级之后的枪刃使用<Action name="迅连斩" />连击之后还可以获得一颗==晶壤==。消耗==晶壤==就可以使用一套新的连击<Action name="烈牙" />（→<Action name="猛兽爪" />→<Action name="凶禽爪" />）（这套连击也被称为“子弹连”，后两个技能为烈牙自动变化，不用拖到技能栏里）。

刚拿到的枪刃单拉就是在盾姿下，以<Action name="闪雷弹" />开怪，然后重复<Action name="迅连斩" />连击（在<Action name="利刃斩" />或<Action name="残暴弹" />之后开启<Action name="无情" />），<Action name="音速破" />对齐每一次<Status :id="1831" name="无情" />。获得晶壤可以优先用来打<Action name="烈牙" />及其连击，如果在等级同步或者<Action name="烈牙" />CD的时候，则可以使用<Action name="爆发击" />消耗==晶壤==，注意不要让晶壤溢出。满级后习得的<Action name="倍攻" />则优先级更高，具体使用方法可参见满级攻略。<Action name="危险领域" />（80级会升级为<Action name="爆破领域" />）好了就用，尽可能在<Status :id="1831" name="无情" />生效中使用。

至此枪刃的输出循环其实已经基本成型了，70级学会<Action name="续剑" />之后，<Action name="烈牙" />连的每一个技能，都会获得一个buff，让<Action name="续剑" />依次变成<Action name="撕喉" />、<Action name="裂膛" />、<Action name="穿目" />，为了不浪费威力，需要在<Action name="烈牙" />连的三个连击之间穿插<Action name="续剑" />的3个能力技（即列牙→续剑2个键来回按3次）。

虽然<Action name="弓形冲波" />是一个范围AOE，但由于它也是不占GCD的能力技，因此同样可以在<Status :id="1831" name="无情" />中对单体使用。

### 对多怪拉怪/输出

枪刃的基础AOE是<Action name="恶魔切" />→<Action name="恶魔杀" />，完成连击后同样可以获得==晶壤==，消耗晶壤则可以使用<Action name="命运之环" />（满级后习得的<Action name="倍攻" />则优先级更高），当然在习得命运之环之前，可以继续使用<Action name="爆发击" />来消耗晶壤（超过2只小怪用<Action name="爆发击" />就不划算了，干脆溢出不用）。最后当然不要忘了<Action name="弓形冲波" />，好了就放（对齐<Status :id="1831" name="无情" />）。

### 减伤及辅助

职能技能<Action name="铁壁" />是20%小减伤，<Action name="星云" />是30%的大减伤，<Action name="伪装" />有10%的减伤，同时提升50%的招架（触发成功则有15%的减伤）。在常规的四人本拉怪的路上，基本上就以这3个技能为主要减伤。另外<Action name="极光" />的HOT，<Action name="石之心" />（82级升级为<Action name="刚玉之心" />）和<Action name="光之心" />的减伤也同样可以对自己生效，算是减伤非常丰富的T了。

枪刃的无敌是<Action name="超火流星" />，<Status :id="1836" name="超火流星" />自身的buff和骑士的<Status :id="1302" name="神圣领域" />效果本身是一样的，但枪刃在使用<Action name="超火流星" />时，会瞬间扣到1血，给很多治疗巨大的精神冲击。通常不建议枪刃过晚开超火流星，也不建议在面对白魔以外的治疗开超火流星，开太晚先<Action name="天赐祝福">天赐</Action>后超火流星，10s后倒T的惨剧，古今中外数不胜数。

职能技能<Action name="雪仇" />是一个降低自身周围敌人攻击的技能，在4人副本面对一群小怪时，经常与<Action name="亲疏自行" />一起组成减伤链的最后一环。而在8人副本等难度较高的副本里，雪仇通常会作为重要减伤的一环安排到团队减伤中。

而<Action name="光之心" />对标黑骑的<Action name="暗黑布道" />，同样是一个魔法团减，效果几乎等于一个魔法版的雪仇。在大多数情况下，我们都认为BOSS的大型AOE（特别华丽或者转场动画）是魔法伤害，但仍有例外，还是需要根据攻略或者ACT记录具体分析。

### 副本实战及应急

在四人本中，确认自己的<Status :id="392" name="王室亲卫" />已打开，通常来说，8人本优先枪刃做MT，当然如果你对副本不熟悉，或者对方已经开盾了，就沟通一下，让他去MT也没关系。

OT或需要换T时，需要先使用<Action name="挑衅" />，让自己的仇恨变为当前最高仇恨。当对方挑衅换T后，自己应该主动关掉盾姿，并对搭档使用<Action name="退避" />。

枪刃只有职能技能的<Action name="插言" />、<Action name="下踢" />可以进行打断，当怪物读条栏有发光边缘时，表示这个技能可以被打断，但是实际上有必要打断的技能并不多。<Action name="下踢" />是使敌方<Status :id="2" name="眩晕" />而打断，由于FF14中有抗性机制的存在，过多使用打断反而有可能导致需要打断的时候出现抗性，高等级的怪物大都具有眩晕抗性，无法通过眩晕打断。可以查看[副本攻略](/duty/)确认需要/能够打断的技能。

如果你在ST时发现场上倒T或倒奶了，请务必第一时间打开盾姿<Status :id="392" name="王室亲卫" />。

枪刃的<Action name="极光" />是一个HOT，可以给掉血的队友（或者自己使用）；<Action name="石之心" />（<Action name="刚玉之心" />）则是综合减伤，而且可以复制一份自身的<Status :id="1898" name="残暴弹" />buff给目标，这两个技能救急可能算不上，但一般的辅助来说也足够用了，枪刃整体来说还是一个偏忙碌的输出端的T。

## 满级手法

> 因精力有限，本站无法提供满级手法参考，可前往NGA论坛查找[绝枪战士的满级攻略](https://nga.178.com/thread.php?key=%E6%9E%AA%E5%88%83&fid=698)