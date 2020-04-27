# 定投策略

## 策略说明

在众多交易策略之中，有一个很有名同时也是号称**“永远不会输钱”**的交易策略——马丁格尔策略。

### 马丁格尔策略

马丁格尔，是一种基于18世纪流行于法国赌场的交易策略，本身也是在赌场游戏系统中盛行至今的著名策略，号称“永远不输钱”的马丁格尔，目前在大多数赌场依然被限制加仓次数。

**马丁格尔策略的操作准则是：你以一单位赌注开始，在每次赔钱后，将赌注加倍，而在任何一次赢钱后，下一次又回归到一单位赌注**。因此，无论在赢钱之前输了多少次，只要概率让下注者赢一次，**不仅会收回先前到损失，还会获得第一次赌注总额的收益**。

马丁格尔策略从赌场被移植到金融交易市场中，创造了许多盈利奇迹和滑铁卢式的交易亏损。

**该策略认为行情永远会回调——即每一次交易盈利或亏损都是随机独立事件**。

从较长的周期来看这也许是对的，但真实情况往往比这更加复杂，**价格行情既不是随机的，交易者也不可能有无限多的筹码。**

**因此马丁格尔策略适用于震荡行情，一旦走出震荡开始单边行情，就会迎来非常大的风险。**

### 反马丁格尔策略

反马丁格尔策略就是将马丁格尔策略反向操作：**你以一单位赌注开始，在每次赚钱后，将赌注加倍，一直到你所「期待赢的次数」达到，就再从一单位赌注开始押注。如果在未达到「期待赢的次数」就输掉了，同样就从头开始，以一单位赌注重新开始押注**。

这是马丁格尔策略在交易市场上的变种，通常是通过一些指标判断行情进入单边趋势后，在趋势前期通过逐步加仓获取高额利润，并且通过限制次数的方式来控制风险。

马丁格尔策略虽然是一种非常好用的仓位策略，但是该策略同样”盈亏同源“——它的根本缺陷在于默认市场是一种单一态的随机概率事件，**因此在使用它的时候，一定要慎重，最好配合上趋势指标一起使用。**

### 策略规则

根据上面的介绍，在这里我们为控制风险对操作范围加以限制，拟定了如下策略规则：

1. 每分钟定投1手空单，20倍杠杆。
2. 未平的仓位，如果亏损超过3%，继续定投。如果盈利超过3%，每分钟平仓2手

其中，在测试脚本中，**定投周期、定投数量、杠杆倍数、盈亏率、仓位方向为可配置项**。

**请注意，任何策略在使用时需要做好风险管理，如果你想在实际环境中利用策略获得稳定的盈利，我们希望你能够在sandbox环境配合其他参数或是策略进行测试调整，以使你能够达到目的，我们也非常期待你能分享你的测试数据以及独到的见解。**

**当然，如果这个过程中，你遇到任何问题需要帮助亦或是有赚钱的策略想要分享，请在ISSUE中反映，我们会努力及时响应。**
