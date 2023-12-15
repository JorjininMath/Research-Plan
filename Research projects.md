~~# 2023/10/21~~
~~# 2023/11/01~~
~~# 2023/11/15~~
# 2023/12/15
### NHGP
* When finish RW_KRR and MSE of SK, then do this, need to finish before next spring

### MSE convergence of SK
* Draft document
  * Misspecification theorem
  * High-dimensional result, find the high-probability bound
  * polish draft, change symbols
* Experiments
  * low-dimensional, validate the slope
  * high-dimensional, apply smolyak and separable kernel;
                      compare with low-dimension and other high-dimensional methods

### RW-KRR
* Draft
  * Put theoretical and numerical parts together
  * Write the handwritthen note first
  * ~~Implement exponential kernel's results~~ 
* Experiments
  * ~~See $\lambda$ influence~~
    * $\lambda$ is small, it performs better for Dejong, worse for Griewank. 
  * ~~Fix totoal budget $B$, see $n$ with error~~
    * ~~The RMSE still changes with changing of $n$, hence this experiment will not give proper conclusion~~
  * ~~Add a GP benchmark function~~
    * No need this
  * Try to use RandomSearchCV to train parameters for Simple and Strict cases, fix some errors in code.
  * Now need to compare three cases under larger $n$, and $m$ increasing as some power to $B$
