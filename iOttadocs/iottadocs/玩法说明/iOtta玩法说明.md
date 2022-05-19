
## 主要玩法概述
整体判定形状为七边形，玩法为伪7k，实则为七分判定线无轨加七判定点
![[mmexport1652762608668.jpg]]

## 键型设计
![[mmexport1652762614597.jpg]]



## 判定区域
![[mmexport1652762620585.jpg]]

准度判定
perfect +-55ms（pure perfect +-25ms 与分数与acc无关）fine +-125msbad +-250msmiss 最低判定范围以下
有全部四种判定的键型：tap有p，f，m三种判定的键型：hold，tap flick，point hold只有p，m两种判定的键型：drag，flick，point drag，point flick

## 物量计算
所有键型物量为1

## 计分规则
基础计分perfect分数=1000000/物量fine分数=perfect分数*70%bad和miss分数均为0
连击分计算combo断前为基础计分combo断后：单键分数=单键基础分数*5%*（剩余物量/总物量）+单键基础分数*95%，并刷新单键基础分数

## 难度分级
分为四个难度α（alpha）、β（beta）、γ（gama）、ι（iotta）iotta难度为隐藏难度定级为1～13

## 评级
700000以下 false700000～780000 D780000～820000 C820000～880000 B880000～920000 A920000～940000 A+940000～980000 S980000～1000000 S+1000000 Impeccable（IP）

## acc计算
perfect数/物量*100%+fine数/物量*70%

## 观赏性玩法
背景可选择播放bga判定块可自由移动（不破坏玩法为前提）边类型键可以于所在边自由移动

