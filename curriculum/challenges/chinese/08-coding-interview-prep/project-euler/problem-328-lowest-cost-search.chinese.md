---
id: 5900f4b41000cf542c50ffc7
challengeType: 5
title: 'Problem 328: Lowest-cost Search'
videoUrl: ''
localeTitle: 问题328：成本最低的搜索
---

## Description
<section id="description">我们试图通过提问来找到从整数集{1,2，...，n}中选择的隐藏数字。我们要求的每个数字（问题）的成本等于所要求的数字，我们得到三个可能的答案之一：“您的猜测低于隐藏的数字”，或“是的，就是它！”或“您的猜测是高于隐藏号码“。给定n的值，最优策略最小化了最坏情况下的总成本（即所有问题的总和）。例如<p>如果n = 3，我们能做的最好的就是问号码“2”。答案将立即引导我们找到隐藏号码（总费用= 2）。 </p><p>如果n = 8，我们可能决定使用“二分搜索”类型的策略：我们的第一个问题是“4”，如果隐藏数字高于4，我们将需要一个或两个额外的问题。让我们的第二个问题是“6”。如果隐藏数字仍高于6，我们将需要第三个问题以区分7和8.因此，我们的第三个问题将是“7”，这个最坏情况的总成本将是4 + 6 + 7 = 17。 </p><p>通过将“5”作为我们的第一个问题，我们可以大大改善n = 8的最坏情况成本。如果我们被告知隐藏的数字高于5，我们的第二个问题将是“7”，那么我们将确定隐藏的数字是什么（总成本为5 + 7 = 12）。如果我们被告知隐藏号码低于5，我们的第二个问题将是“3”，如果隐藏号码低于3，我们的第三个问题将是“1”，总成本为5 + 3 + 1 = 9。自12&gt; 9以来，该策略的最坏情况成本为12.这比我们之前使用“二元搜索”策略所取得的成本更好;它也优于或等于任何其他策略。所以，事实上，我们刚刚描述了n = 8的最优策略。 </p><p>假设C（n）是通过n的最优策略实现的最坏情况成本，如上所述。因此，C（1）= 0，C（2）= 1，C（3）= 2，C（8）= 12.类似地，C（100）= 400，C（n）= 17575。 </p><p>找到C（n）。 </p></section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>euler328()</code>应返回260511850222。
    testString: assert.strictEqual(euler328(), 260511850222);

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler328() {
  // Good luck!
  return true;
}

euler328();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
