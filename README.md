# pairs-trading-with-ML

Jonathan Larkin, August 2017

One popular strategy classification is Pairs Trading. Though this category of strategies can exhibit attractive performance characteristics, I often see individual strategies which have a very small set of eligible pairs. As in any quant strategy, the [breadth of bets](https://blog.quantopian.com/the-foundation-of-algo-success/) is proportional to the quality returns. As such, as the creator of a pairs trading strategy, you always prefer more (valid) pairs rather than fewer. This notebook shows a concrete example of using Machine Learning techniques, readily available in `scikit-learn`, to find pairs.
