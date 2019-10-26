# 诈金花
上周的level4太难了，这周我们玩点简单的--“诈金花”，放心，我拦住了ds，不会让你们自己写游戏，你们只负责玩。    
诈金花可是一项集智慧、运气、勇气、判断力与一身的游戏。       
## 规则：   
> * 其它 < 对子 < 顺子 < 金花 < 顺金 < 筒子    
> * 牌型点数完全相同，后发牌的赢，嗯，运气很重要    
> * 每个人都有自己的初始筹码200000，每局都会扣取底注100     
> * 一局会有多轮，每轮都要下注（最多5轮）     
> * 你下注的时候会告诉你最低下注筹码数，你可以选择跟注、加注、弃牌
> * 加注不得超过最低筹码的三倍（eg:最低下注筹码为200，你最多只能下注600）
> * 有玩家加注之后，该筹码数成为新的最低筹码数（eg: 目前底注300，有人加注，下注了600，那么后面的玩家最低下注为600）
> * 下注数量和要求视为弃牌（下注数小于最低筹码数，或者高于最低筹码的三倍，最简单的，弃牌你直接return 0）
> * 筹码不足100不能继续游戏，   
> * 游戏会进行很多轮，最终统计成绩，筹码数多的获胜


## 怎么玩
从这里fork一份到自己的github ，clone到本地      
在player包里添加自己的Player类,类名为“你的英文名＋Player”， 实现Player接口，完善信息，并实现你的算法    
其他的代码，一行都不要改动      
然后提交pull request。注意只提交自己添加的类。   


>tips: 一个优秀的算法，需要考虑到你的牌型、轮数、剩余玩家、桌上的筹码总量、最低下注数、你的余额等等信息
>代码里给了几个很不成熟的算法，请自己考虑一个更好的算法，干掉王尼玛

## 高端操作
* 机器学习算法,训练模型，提高胜率
* 反射作弊，贿赂荷官
