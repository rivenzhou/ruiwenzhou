---
title: "3. Correlated Survival Outcome Prediction with Neural Network"
#excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
collection: portfolio
---

Extensive literature has been proposed for the analysis of correlated survival data. Subjects within the same cluster share some common characteristics, e.g., genetic and environmental factors, so their time-to-event outcomes are correlated. The frailty model under the proportional hazards assumption has been widely applied to analyze clustered survival outcomes. However, the prediction performance of this method can be less satisfactory when the risk factors have complicated effects, e.g., nonlinear and interactive. 

To deal with this issue, we proposed a neural network frailty Cox model that replaces the linear risk function with the output of a feed-forward neural network. The estimation is based on quasi-likelihood with the use of Laplace approximation. The method is applied to the clustered time-to-failure prediction within kidney transplantation facility using the national kidney transplant registry data from the U.S. Organ Procurement and Transplantation Network (OPTN). Our proposed method is shown to have better prediction performance in the simulation studies and real data application.
