`Gradient Boosting Machines` : An ensemble of **sequentially** built **weighted** **weak** predictors, a boosting algorithm.

**Why sequential?** - to focus more on mistakes made by predecessor

**Why weighted?** - algorithm assigns higher weights to the training samples that got wrong by previous predictor

**Why weak?** - strong predictors generally learn most of the information and the error(remaining information) consists of noise, whereas weak predictors partially learn the information and hence, the successor predictor has scope of learning more information.
