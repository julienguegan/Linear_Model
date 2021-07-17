# Linear_Model
Some practical work about the linear model to understand basics concepts of statistical estimation.

## Ordinary Least Square

We have **n** observations **(y,x)**. We make the hypothesis of the linear model and we define the estimator that **minimize the sum of the squares errors**. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/45081450/126046784-4378a94d-738d-4e95-b039-8a5368b35158.png" />
</p>

The first orders conditions for this minimization allow to find easily the values of the parameters of the OLS estimator (**slope** and **intercept**). 
We can then compute values like the **coefficient of determination R2**, give **confidence intervals**, do predictions or make hypothesis test.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45081450/126046701-c51f36d8-5363-4fef-a166-7d6864f87eed.png" />
</p>

## Regularization : Ridge - Lasso

Penalization terms allows to simplify a problem when it is ill-conditionned.

Ridge regression is useful when a lot of independent variabes are highly correlated. This idea is to add the norm L2 of the parameter on the OLS formulation.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45081450/126047161-9fac9c52-b730-4566-90f1-3d2b8eeafb05.png" />
</p>

Lasso method performs both variable selection and regularization. It allows to enhance the prediction accuracy and interpretability of the resulting statistical model. Instead of a norm L2 (Ridge), the norm L1 is used.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45081450/126047248-cd335dc2-a4e1-4e15-b8a1-afc21779c2bb.png" />
</p>
