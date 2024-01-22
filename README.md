# ra2yuri
----
这是什么？这是红色警戒2尤里的复仇，WIN10版下载、MOD攻略等，怀念青春，红色年华，天启、基洛夫、特斯拉、光棱、巨炮、尤里X与你同在。

整理by [zhengkai.blog.csdn.net](zhengkai.blog.csdn.net)


【扩展版】红色警戒2 重聚2023 1.4.20 最新win10/win11超级无敌全能适配版
----
介绍视频
https://www.bilibili.com/video/BV1SG4y1w72g/?spm_id_from=333.1007.tianma.7-4-26.click



红色警戒2(含尤里的复仇)完整免安装高压优化版
----
这个版本还不错，音响震撼，包含战役所有视频，更是自带WIN10/WIN11运行支持，相对完美的收藏版本。正在上传阿里云。
```
首选阿里云盘：

【扩展版】红色警戒2 重聚2023 1.4.20.exe
https://www.alipan.com/s/qA9VAdafGXe
提取码: 3gy0
点击链接保存，或者复制本段内容，打开「阿里云盘」APP ，无需下载极速在线查看，视频原画倍速播放。

备用百度链接: 
链接：https://pan.baidu.com/s/1zpgkrnQNHKZrqTGr0FVlMQ?pwd=15zh 
提取码：15zh
```

Win11红警玩不了怎么办
----

1. 首先右键选中“`此电脑`”，然后点击进入“`属性`”设置。
2. 然后点击左侧的“`应用`”，再进入右侧的“`可选功能`”
3. 接着找到相关设置下的“`更多Windows功能`”
4. 最后在其中找到“`旧版组件`”下的“`DirectPlay`”，勾选开启，再点击下方“确定”就可以正常玩红警了。


红色警戒2尤里的复仇背景设定
----

>故事的开始


一切起源于红色警戒2以下简称RA2。

一天，美国突然发现有大量苏联部队从四面八方而来，美国总统杜根质问苏联总理罗曼诺夫，没想到苏联方面竟想吞并美国，统一世界！

杜根立即下令发射核弹反击，但是苏联已经拥有了能控制人心智的能力，罗曼诺夫命令尤里控制了发射人员，致使核弹在发射井中爆炸，重创盟军。

杜根便派出部队与苏军决一死战……


>RA2（红色警戒2） 结局


盟军结局：指挥官与谭雅依靠爱因斯坦建造在佛罗里达州的超时空传送仪成功入侵莫斯科，进入克里姆林宫抓捕罗曼诺夫，将其送往伦敦审判。

而不知去向的尤里渐渐浮出了水面......

苏军结局：尤里为夺取国家最高权力，用心灵控制技术谋杀了罗曼诺夫总理后，栽赃给维拉迪摩将军并处死了他，后苏军情报员截获了罗曼诺夫生前寄出的录映带才得知真相。

之后，玩家成功统一了全世界并成为新任苏联总理。

>尤里的阴谋

盟军击溃苏联的入侵，大获全胜。

当美军以为已经成功击败邪恶势力时，尤里展示了他的恐怖计划：尤里已完全掌握了心灵控制的技术，当苏联垮台之后，尤里自行成立一个新国家并正式进行他的复仇大计，他在全世界部署了名为"心灵控制器"(Psychic Dominator)的超级武器组成的网络，企图控制全人类的心灵。

不过，盟军有爱因斯坦的伟大创造——时间机器。

指挥官需要通过时间机器回到大战的初期，销毁全世界的心灵控制器，并摧毁尤里的武装力量。

而另一方面，苏联的残余部队也在打着时间机器的主意，试图铲除尤里并改写失败的历史。


>YR(尤里的复仇)结局


盟军结局：尤里藏匿在南极的基地被盟军摧毁，尤里被抓获，他将在爱因斯坦教授的"心灵隔离室"中度过余生。

时间轴重新结合将世界恢复到 YR 战役之前，死亡的卡维利将军复活，苏联成为盟军的附属。

苏军结局：尤里藏匿在他家乡罗马尼亚的要塞被苏军摧毁，尤里还想逃脱失败的命运，他修好、启动了遗留在旧金山的时间机器并驾驶时间机器逃离。

但苏联少尉索菲亚依旧有控制时间机器的密码。

她略施小计将尤里传送到了白垩纪并释放了时间机器的所有能量，使尤里被困在白垩纪并被暴龙吃掉。

苏军终于征服了地球，就连月球也并入苏联，并且苏联还在向太阳系外拓展。



提取方法
----
用`xcc mixer`编辑器打开yuri目录下的`。mix`文件，我是在`expandmd01.mix`中找到并提取`rulesmd.ini`文件，也可以用我的这个。

MOD方法
----
直接修改`rulesmd.ini`文件并放到ra2yuri目录下即可。

兵种武器能力修改
----
复杂的搞不来，简单的还可以搞。
例如搜索`[SHK]`找到4506行，磁暴步兵的代码：
```
; Soviet Tesla Trooper
[SHK]
UIName=Name:SHK
Name=Shock Trooper
Category=Soldier
Primary=ElectricBolt
Secondary=AssaultBolt
Assaulter=no ; I clear out UC buildings
Prerequisite=NAHAND
CrushSound=InfantrySquish
Crushable=no
Strength=130
Armor=Plate
TechLevel=5
Pip=white
Sight=6
Speed=4
Owner=Russians,Confederation,Africans,Arabs
Cost=500
Soylent=250
Points=5
IsSelectableCombatant=yes
VoiceSelect=TeslaTroopSelect
VoiceMove=TeslaTroopMove
VoiceAttack=TeslaTroopAttackCommand
VoiceFeedback=TeslaTroopFear
VoiceSpecialAttack=TeslaTroopMove
DieSound=TeslaTroopDie
Locomotor={4A582744-9839-11d1-B709-00A024DDAFD1}
PhysicalSize=1
MovementZone=Infantry
;MovementZone=InfantryDestroyer ;GEF wow!!! copy paste bug from the original Disk Thrower!
ThreatPosed=20	; This value MUST be 0 for all building addons
VeteranAbilities=STRONGER,FIREPOWER,ROF,SIGHT,FASTER
EliteAbilities=SELF_HEAL,STRONGER,FIREPOWER,ROF
ImmuneToVeins=yes
Size=1
AllowedToStartInMultiplayer=no
ElitePrimary=ElectricBoltE
IFVMode=6
```
**修改建议：**
- Primary是升级前的武器，设置为升级后的武器即可。
- 例如Primary=120mmxE，直接就是三级天启的炮弹，磁暴步兵三级带E是ElectricBoltE磁能。
- ElitePrimary是升级后的武器，一般后面带E后缀。
- Strength=130生命值，设置为6000左右够用了。
- Speed=4是移动速度，10左右即可，太高容易卡带。

**任意车辆载人攻击代码：**
- 例如给磁暴坦克，给多功能步兵车加上之后，就可以载人射击了
```
PipScale=Passengers
Passengers=5
OpenTopped=yes;passengers can shoot out
SizeLimit=10;1 ;gs like half track and Blackhawk.  Terror Drones and Brutes are allowed in.
```

兵种武器修改（全局通用）
----
接下来搜他的武器`[ElectricBoltE]`，发现再24871行
```
; Fire by Telsa Trooper
[ElectricBoltE]
Damage=50
ROF=40
Range=5
Speed=100
Warhead=Shock
Report=TeslaTroopEliteAttack
Projectile=Electricbounce
IsElectricBolt=true
AssaultAnim=UCELEC;the anim to play when a UC building is cleared (assaulters need this on their primary weapon)

```
**修改建议：**
- Damage=50攻击伤害，200左右都可以
- Range=5攻击范围，30左右都可以
- Speed=100攻击速度，200左右都可以


单位代码
----
直接`[xxxx]`可以快速找到资源，然后MOD。
```
0=GAPOWR;盟军发电厂
1=GAREFN;盟军矿厂
2=GAPILE;盟军兵营
3=GAWEAP;盟军兵工厂
4=GAAIRC;盟军空军指挥部
5=AMRADR;美国空军指挥部--AmericanParaDropSpecial
6=GADEPT;盟军维修厂
7=GAYARD;盟军船厂
8=GATECH;盟军实验室
9=GAROBO;控制中心---
10=GAOREP;　矿石精鍊器
11=GAWALL;盟军围墙
12=GAPILL;机枪碉堡---Vulcan2
13=NASAM;爱国者飞弹　--RedEye2
14=GAGAP;裂缝产生器
15=ATESLA;光棱塔----PrismShot/PrismSupport
16=GASPYSAT;间谍卫星
17=GACNST;盟军建造场
18=GTGCAN;法国巨炮　　GrandCannonWeapon
19=GACSPH;超时空传送仪---ChronoSphereSpecial
20=GAWEAT;天气控制器---LightningStormSpecial
21=GASAND;沙袋
22=GAGATE_A;闸门
23=;===苏军======;
24=NAPOWR;磁能反应炉
25=NAREFN;苏军矿厂
26=NAHAND;苏军兵营
27=NAWEAP;苏军兵工厂
28=NARADR;苏军雷达---SpyPlaneSpecial
29=NADEPT;苏军维修厂
30=NAYARD;苏军造船厂
31=NATECH;苏军实验室
32=NANRCT;核子反应堆---NukePayload
33=NAINDP;工业工厂
34=NAWALL;苏军围墙
35=NABNKR;战斗碉堡
36=NALASR;哨戒炮--Vulcan
37=NAFLAK;防空炮--FlakWeapon
38=TESLA　;磁暴线圈　--CoilBolt/OPCoilBolt
39=NACNST;苏军建造厂
40=NAIRON;铁幕---IronCurtainSpecial
41=NAMISL;核弹发射井--NukeSpecial
42=NAPSYB;心灵信标
43=;===尤里======;
44=YAPOWR;生化反应炉
45=YAREFN;奴隶矿厂
46=YABRCK;尤里兵营
47=YAWEAP;尤里兵工厂
48=NAPSIS;心灵感应器---PsychicRevealSpecial
49=YAYARD;尤里船厂
50=YAGRND;部队回收厂
51=YATECH;尤里实验室
52=GAFWLL;尤里围墙
53=NATBNK;坦克碉堡
54=YAGGUN;盖特机炮
55=YAPSYT;心灵控制塔----MultipleMindControlTower
56=NACLON;复制中心
57=YAGNTC;基因突变器---GeneticConverterSpecial
58=YAPPET;心灵控制器---PsychicDominatorSpecial
59=YACNST;尤里建造场
60=YAROCK;不明建筑物
61=YACOMD;尤里指挥中心
62=;===平======;
63=GASAND;沙墙
64=CAAIRP;科技机场---ParaDropSpecial
65=CAOILD;=科技钻油厂
66=CAPARS01;=艾菲尔铁塔
67=CAEAST02;＝尤里雕像----PrismShot
68=CATRAN03;＝尤里要塞
69=CAEAST01;=复活岛石像
[步兵类代码]
0=E1;美国大兵
1=E2;苏联动员兵
2=SHK;磁爆步兵
3=ENGINEER;盟军工程师
4=JUMPJET;火箭飞行兵
5=GHOST;海豹部队
6=YURI;尤里
7=IVAN;疯狂伊万
8=DESO;生化步兵
9=DOG;苏联军犬
10=CIV1;平民1
11=CIV2;平民2
12=CIV3;平民3
13=CTECH;技师
14=WEEDGUY;防IE挂载（没用）
15=CLEG;超时空兵团
16=SPY;间谍
17=CCOMAND;超时空突击队
18=PTROOP;伞兵
19=CIVAN;超时空伊万
20=YURIPR;尤里改
21=SNIPE;狙击手
22=COW;奶牛
23=ALL;鳄鱼
24=TANY;谭雅
25=FLAKT;防空步兵
26=TERROR;恐怖分子
27=SENGINEER;苏联工程师
28=ADOG;盟军军犬
29=VLADIMIR;VLADIMIR
30=PENTGEN;PENTGEN
31=PRES;总统
32=SSRV;终级保镖
33=CIVA;德克萨斯平民A
34=CIVB;德克萨斯平民B
35=CIVC;德克萨斯平民C
36=CIVBBP;棒员运动员
37=CIVBFM;海滩肥男
38=CIVBF;海滩女
39=CIVBTM;海滩瘦男
40=CIVSFM;雪中肥男
41=CIVSF;雪中肥女
42=CIVSTM;雪中瘦男
43=POLARB;北极熊
44=JOSH;猴子
45=YENGINEER;尤里工程师
46=GGI;重装大兵
47=INIT;尤里新兵
48=BORIS;鲍裏斯
49=BRUTE;狂兽人
50=VIRUS;病毒狙击手
51=CLNT;快枪手
52=ARND;终结者
53=STLN;蓝波
54=CAML;骆驼
55=EINS;爱因斯坦
56=MUMY;木乃伊
57=RMNV;洛马诺夫总理
58=LUNR;登月火箭兵
59=DNOA;暴龙
60=DNOB;暴龙
61=SLAV;奴隶矿工
62=WWLF;(木乃伊)
63=YDOG;尤里军犬
64=YADOG;尤里军犬
65=CIVFM;海滩肥女
[战车类代码]
0=AMCV;盟军移动基地车
1=HARV;尤里奴隶采矿车
2=APOC;天启坦克
3=HTNK;犀牛坦克
4=SAPC;装甲运输船
5=CAR;汽车
6=BUS;校车
7=WINI;wini
8=PICK;小货车
9=MTNK;灰熊坦克
10=HORV;武装采矿车
11=TRUCKA;货车A
12=TRUCKB;货车B
13=CARRIER;航空母舰
14=V3;V3火箭车
15=ZEP;基洛夫空艇
16=DRON;恐怖机器人
17=HTK;防空履带车
18=DEST;驱逐舰
19=SUB;飓风级战舰
20=AEGIS;宙斯盾战舰
21=LCRF;盟军运输船
22=DRED;无畏级战舰
23=SHAD;夜鹰直升机
24=SQD;乌贼
25=DLPH;海豚
26=SMCV;苏联移动机基车
27=TNKD;坦克杀手
28=HOWI;榴弹炮
29=TTNK;磁爆坦克
30=LTNK;轻坦克
31=CMON;超时空采矿车（不回）
32=CMIN;超时空采矿车
33=SREF;光棱坦克
34=XCOMET;位置标定器
35=HYD;海蝎
36=MGTK;幻影坦克
37=FV;多功能步兵车
38=VLAD;维拉迪摩指挥舰
39=DTRUCK;自爆卡车
40=PROPA;宣传车
41=CONA;挖掘机
42=COP;cop
43=EUROC;欧洲汽车
44=LIMO;豪华轿车
45=STANG;小轿车
46=SUVB;小汽车A
47=SUVW;小汽车B
48=TAXI;出租车
49=PTRUCK;货车C
50=CRUISE;巡游船
51=TUG;拖船
52=CDEST;海岸巡逻船
53=YHVR;尤里气垫船
54=PCV;尤里机动基地车
55=SMIN;尤里奴隶矿厂
56=SMON;超时空采矿车
57=YCAB;黄色计程车
58=YTNK;盖特炮坦克
59=BFRT;战斗要塞
60=TELE;磁电坦克
61=CAOS;神经突袭车
62=DDBX;巴士
63=BCAB;黑色计程车
64=BSUB;雷鸣潜艇
65=SCHP;武装直升机
66=JEEP;卡车
67=MIND;精神控制车
68=DISK;镭射幽浮
69=UTNK;激光坦克
70=ROBO;遥控坦克
71=SCHD;武装直升机
72=DOLY;摄影车
73=CBLC;电车
74=FTRK;救火车
75=AMBU;救护车
76=CIVP;民航机
77=V3V3;V3火箭车
78=TURCKB;货车B
[飞机类代码]
0=APACHE;阿帕奇
1=ORCA;入侵者战机
2=HORNET;大黄蜂
3=V3ROCKET;V3火箭
4=ASW;舰载反潜机
5=DMISL;无畏级导弹
6=PDPLANE;运输机
7=BEAG;黑鹰战机
8=BPLN;米格战机(鲍里斯的飞机)
9=SPYP;侦察机
10=CMISL;雷鸣导弹
```
