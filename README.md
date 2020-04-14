# CIS520
Use logistic regression to do a binary classification problem. Write your own calculation equation. 


The important part of it should be logistic regression is to miminum logistic loss function log_2(1+e^(yf(x)). 

Also from another perspective, we could think about it as P(y|x) = g(w^T*x) where g(u) is 1/(1+e^u). Then with this assumption and maximum probablity estimation, we should get the largest value of function: ln L(probablity) = ln (1+e^(yf(x)) which is same as before.
