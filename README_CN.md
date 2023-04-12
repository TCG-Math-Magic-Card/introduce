# TCG数学魔法卡设计

[English](/README.md)

我发明了一种桌面游戏。我觉得很酷，而且我的精力和能力有限。我希望通过社区来发展和壮大他。如果你感兴趣请阅读并加入进来。[加入Discard](https://discord.gg/9xUGkcg3)

- Q: 什么是TCG?
  -  A: TCG 是 Trading Card Game 的缩写，翻译为“交换卡牌游戏”。这类游戏通常是指玩家使用自己的卡片组合来与其他玩家对抗。每个卡片代表着不同的角色、能力或装备等，可以通过购买卡片包或者与其他玩家交换来获取更多的卡片，从而丰富自己的卡片库并提高在游戏中的实力。知名的 TCG 游戏包括《魔法飞球》（Magic: The Gathering）、《炉石传说》（Hearthstone）、《游戏王》（Yu-Gi-Oh!）等。
- Q: 数学魔法卡是一个什么样的游戏？
  - A: 数学魔法卡，是一个致力于将纯粹的数学概念融入到桌游中的游戏。当然里面会有魔法的部分，但是我保证核心获胜的机制是数学概念。
- Q: 为什么要设计这样的游戏？
  - A:单纯出于好玩。

# 简易规则
请注意简易规则是方便你理解这个游戏中的核心概念。一旦你理解简易规则后，我建议你去阅读详细的规则，以获取更多的策略选择。

在此之前请允许我介绍游戏中的三种基本卡片。它们分别是值卡，算子卡,断言卡。
## 值卡
值卡表示最纯粹的值。比如数字1或者数字2。它们的意义和你平时理解的数学上的1和2是差不多的。只是以卡片的形式体现。
## 算子卡
算子这个概念可能在你的生活中并不常见，但是你一定知道`+`这个符号。它一般也被叫做加法符号，我们这里说的算子卡就是类型与`+`、`-`之类你常见的技术符号。你可能也感觉到了，算子卡表示的符号可以把两个‘值’（游戏里对应值卡）链接在一起，从而形成一个新的式子。比如：`1+1`,`4-3`之类的。
## 断言卡
断言卡上有一句断言，用来描述一个数学概念。比如“这是偶数”、“这是奇数”。通过值卡和算子卡构成的式子我们可以得出一个值。然后我们通过我们的数学知识就可以知道这个断言的真假了。比如 `1+1 | 是奇数`，`1+1 | 是偶数`。我们可以知道第一个组合是假，第二个组合是真。

断言卡上除了断言，还有两个很重要的东西：胜利点数，失败点数。这两个值有什么用呢？它是用以判断游戏最终哪方获胜或者失败的。每有一个为真的组合，你的最终胜利点数就会加上那种断言卡上的胜利点数。反之如果为假就减去。双方最终计算出胜利点数多的人获胜，或者平局。