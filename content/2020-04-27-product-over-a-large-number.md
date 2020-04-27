Title: product-over-a-large-number
Date: 2020-04-26 12:58
Category: Review



<!-- write your content here. -->

当我们计算多个大数的乘积时，可能造成数值上溢或者下溢。
此时，我们需要将数值的log值相加，而不是计算数值的乘积。
这是因为：

$$ log(a) + log(b) = log(ab)$$