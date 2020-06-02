# Option
Option主要有两种， call和put。你可以把option看成是一个有价值的合同，可以花钱买，也可以卖它赚钱。对于买房，call option gives you the right to buy stock at a locked price, while put option gives you the right to sell stock at a predetermined price。对于卖方，call option means the obligation to sell at a predetermined price, while put option means the obligation to buy at a predetermined price.这里所说的predetermined price右脚strike price 或是exercise price。

write一个option实际上就是卖一个option的另外一种说法，short一个Option则是另外一种叫法。同样，long一个option等同于buy一个option.

买一个optoin, 付出的是买option的钱，又叫premium。得到的是option升值的潜力。比方说，一个TD公司strike price是70块的call option。现在卖3块，现在td的市值是68块。如果花了3块买了这个call,等td涨到73块你就回本了。如果涨到75块，你就赚了2块。如果涨到100块，你就赚了27块。如果td的价值一直下跌，你大不了就当是白买这个option，顶多亏了3块。

通常来说，write一个call就是指卖一个naked call, 或者short call。简单讲就是坐不需要本钱的买卖。每个option对应着100shares股票。再拿TD举例子，你如果没有TD的股票， 而卖了一个TD的Call，那就是卖了一个naked call。naked call的好处是可以空手套白狼，坏处是粉线很大。一旦TD涨到100，call buyer要exercise这个70块的call,作为seller,你就必须按100块的价格买下td股票，再以70的价格卖给call buyer。这时出去你先前卖call挣的三块，你亏损27。

Covered Call Strategy说的是在拥有TD股票的前提下卖TD的call，实际上就是long stock + short call这样就把TD股票升值的风险hedge住了。但同时也失去了自己拥有的TD升值的潜力。原理就是，你在卖call得同时，买了股票来cover自己，你卖的call亏钱的同时，你的股票会赚钱。

# 经验
一个优秀的华尔街交易员都是下午才开始交易的，上午的盘面涨跌根本都是假的，上午的时间用来看新闻，千万别上午交易。

降息 ——》 货币跌，股票涨
加息 ——》 货币张，债券跌
美元涨 ——》 黄金跌
糖期货降价——》食品公司利润高——》股票涨
美国不加息——》加拿大股票涨
油价跌——》加币跌——》加拿大股票涨
加拿大股票市场和油价成正相关
美元指数变强——》全球投资环境不好——》FED加息——》美国股市走强
厄尔尼诺——》粮食价格涨

苹果140，加拿大鹅30，costco155,google930,baba 140, dol一元店 120， NVDA 195, 
cibc全球科技基金，td科学与技术，
visa
udow 三倍道琼斯
spy
qqq

GILD
TWTR 观察
BA
COST


用dividend growth的策略投加拿大的股票，美国的股票放在RRSP里面免掉dividend的foreign withholding tax。当然像科技股这样很少dividend的放在non-registered 里面。

