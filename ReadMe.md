# Causal Inference for Observational Studies
I decided to develop a series of tutorials on causal inference methods for observational studies after receiving reviewer feedback asking to address endogeneity issues in some of my submitted manuscripts. While working on those revisions, I thought to create a workshop focused on methods designed to tackle these challenges in observational studies. Below are some of the topics I plan to cover. Each session presents a method(s) to tackle specific inference problems inherent to observational data, where treatment assignment is not randomized and confounding is a major concern. Later, I hope to expand this effort by making YouTube videos and writing blog posts. 

## 1. Observational Studies and Causal Inference
- Understanding difference between correlation and causation
- Introduction to counterfactuals and potential outcomes framework
- Overview of causal diagrams (Directed Acyclic Graphs - DAGs)
- Fundamental assumptions: unconfoundedness, overlap, and SUTVA
- Causal inference in social science, epidemology, and economics

### Readings
- [Holland, Paul W. 1986. “Statistics and Causal Inference.” *Journal of the American Statistical Association* 81(396): 945–960.](https://www.jstor.org/stable/2289064)
- [Rubin, Donald B. 1974. “Estimating Causal Effects of Treatments in Randomized and Nonrandomized Studies.” *Journal of Educational Psychology* 66(5): 688–701.](https://doi.org/10.1037/h0037350)
- [Pearl, Judea. 2009. *Causality: Models, Reasoning, and Inference*. Cambridge University Press (Chapters 1-2).](https://doi.org/10.1017/CBO9780511803161)

---

## 2. Potential Outcomes and Counterfactual Reasoning
- Concept of counterfactuals: defining "what would have happened"
- Estimating causal effects: ATE, ATT, and CATE
- Potential outcomes framework for policy evaluation

### Readings
- [Rubin, Donald B. 1978. “Bayesian Inference for Causal Effects: The Role of Randomization.” *The Annals of Statistics* 6(1): 34–58.](https://www.jstor.org/stable/2958830)
- [Holland, Paul W. 1986. “Statistics and Causal Inference.” *Journal of the American Statistical Association* 81(396): 945–960.](https://www.jstor.org/stable/2289064)
- [Sekhon, Jasjeet S. 2004. “Quality Meets Quantity: Case Studies, Conditional Probability and Counterfactuals.” *Perspectives on Politics* 2(2): 281–293.](https://doi.org/10.1017/S1537592704040161)

---

## 3. Regression-Based Methods
- Using regression to adjust for confounders and estimate causal effects
- Regression Discontinuity (RD) designs
- Instrumental Variable (IV) estimation for endogeneity


### Readings
- [Angrist, Joshua D., and Alan B. Krueger. 1991. “Does Compulsory School Attendance Affect Schooling and Earnings?” *The Quarterly Journal of Economics* 106(4): 979–1014.](https://doi.org/10.2307/2937954)
- [Hahn, Jinyong, Petra Todd, and Wilbert Van der Klaauw. 2001. “Identification and Estimation of Treatment Effects with a Regression-Discontinuity Design.” *Econometrica* 69(1): 201–209.](https://doi.org/10.1111/1468-0262.00183)
- [Imbens, Guido W., and Joshua D. Angrist. 1994. “Identification and Estimation of Local Average Treatment Effects.” *Econometrica* 62(2): 467–475.](https://doi.org/10.2307/2951620)

---

## 4. Matching Methods
- Propensity score matching
- Exact matching, Mahalanobis distance matching, and full matching
- Evaluating balance before and after matching
- Limitations of matching methods

### Readings
- [Ho, Daniel E., Kosuke Imai, Gary King, and Elizabeth A. Stuart. 2007. “Matching as Nonparametric Preprocessing for Reducing Model Dependence in Parametric Causal Inference.” *Political Analysis* 15: 199–236.](https://doi.org/10.1093/pan/mpl013)
- [Stuart, Elizabeth A. 2010. “Matching Methods for Causal Inference: A Review and a Look Forward.” *Statistical Science* 25(1): 1–21.](https://doi.org/10.1214/09-STS313)
- [Rosenbaum, Paul R., and Donald B. Rubin. 1985. “Constructing a Control Group Using Multivariate Matched Sampling Methods that Incorporate the Propensity Score.” *The American Statistician* 39(1): 33–38.](https://doi.org/10.2307/2683903)

---

## 5. Weighting Methods
- Using Inverse Probability Weighting (IPW) for causal inference
- Stabilized weights
- Entropy balancing: a flexible reweighting method
- Comparison of weighting vs. matching approaches


### Readings
- [Rosenbaum, Paul R. 1987. “Model-Based Direct Adjustment.” *Journal of the American Statistical Association* 82(398): 387–394.](https://doi.org/10.2307/2289440)
- [Robins, James M., and Andrea Rotnitzky. 1995. “Semiparametric Efficiency in Multivariate Regression Models with Missing Data.” *Journal of the American Statistical Association* 90(429): 122–129.](https://doi.org/10.1080/01621459.1995.10476494)
- [Hainmueller, Jens. 2012. “Entropy Balancing for Causal Effects: A Multivariate Reweighting Method to Produce Balanced Samples in Observational Studies.” *Political Analysis* 20(1): 25–46.](https://doi.org/10.1093/pan/mpr025)

---
## 6. Causal Inference with Longitudinal Data: Fixed Effects and Difference-in-Differences
- Fixed effects models for controlling time-invariant unobservables
- Difference-in-Differences: identifying causal effects in panel data
- Parallel trends assumption and its validation
- Extensions of DiD: triple differences and event studies


### Readings
- [Card, David, and Alan B. Krueger. 1994. “Minimum Wages and Employment: A Case Study of the Fast Food Industry in New Jersey and Pennsylvania.” *American Economic Review* 84(4): 772–793.](https://www.aeaweb.org/articles?id=10.1257/aer.84.4.772)
- [Bertrand, Marianne, Esther Duflo, and Sendhil Mullainathan. 2004. “How Much Should We Trust Differences-in-Differences Estimates?” *Quarterly Journal of Economics* 119(1): 249–275.](https://doi.org/10.1162/003355304772839588)
- [Angrist, Joshua D., and Jörn-Steffen Pischke. 2009. *Mostly Harmless Econometrics: An Empiricist's Companion*. Princeton University Press (Chapter 5).](https://press.princeton.edu/books/paperback/9780691120355/mostly-harmless-econometrics)

---

## 7. Causal Inference with Longitudinal Data: Synthetic Control Methods
- Introduction to synthetic control as a method for comparative case studies
- Constructing a synthetic control using weighted averages of control units
- Comparison of synthetic control and DiD methods
- Limitations and robustness checks for synthetic controls


### Readings
- [Abadie, Alberto, and Javier Gardeazabal. 2003. “The Economic Costs of Conflict: A Case Study of the Basque Country.” *American Economic Review* 93(1): 113–132.](https://www.aeaweb.org/articles?id=10.1257/000282803321455188)
- [Abadie, A., A. Diamond, and J. Hainmueller. 2010. “Synthetic Control Methods for Comparative Case Studies: Estimating the Effect of California’s Tobacco Control Program.” *Journal of the American Statistical Association* 105: 493–505.](https://doi.org/10.1198/jasa.2009.ap08746)

---

## 8. Machine Learning for Causal Inference
- Role of machine learning in estimating propensity scores and treatment effects
- Metalearners: S-learner, T-learner, and X-learner frameworks
- Causal forests for heterogeneous treatment effects
- Double machine learning for high-dimensional causal inference

### Readings
- [Belloni, Alexandre, Victor Chernozhukov, and Christian Hansen. 2014. “High-Dimensional Methods and Inference on Structural and Treatment Effects.” *Journal of Economic Perspectives* 28(2): 29–50.](https://doi.org/10.1257/jep.28.2.29)
- [Künzel, Sören R., Jasjeet S. Sekhon, Peter J. Bickel, and Bin Yu. 2019. “Metalearners for Estimating Heterogeneous Treatment Effects Using Machine Learning.” *Proceedings of the National Academy of Sciences* 116(10): 4156–4165.](https://doi.org/10.1073/pnas.1804597116)
- [Athey, Susan, and Guido W. Imbens. 2016. “Recursive Partitioning for Heterogeneous Causal Effects.” *Proceedings of the National Academy of Sciences* 113(27): 7353–7360.](https://doi.org/10.1073/pnas.1510489113)

---

## 9. Sensitivity Analysis for Causal Inference
- Methods for assessing impact of unmeasured confounding
- Sensitivity analysis using Rosenbaum bounds
- Introduction to E-value for robustness checks
- Sensitivity to assumptions in DiD, IV, and RD designs
- Practical tools for conducting sensitivity analysis in R

### Readings
- [Rosenbaum, Paul R. 2002. *Observational Studies*. Springer (Chapters 4 and 9).](https://link.springer.com/book/10.1007/978-1-4757-3692-2)
- [Imbens, Guido W. 2003. “Sensitivity to Exogeneity Assumptions in Program Evaluation.” *American Economic Review* 93(2): 126–132.](https://doi.org/10.1257/000282803321947718)
- [VanderWeele, Tyler J., and Peng Ding. 2017. “Sensitivity Analysis in Observational Research: Introducing the E-Value.” *Annals of Internal Medicine* 167(4): 268–274.](https://doi.org/10.7326/M16-2607)

---

## 10. Causal Mediation Analysis
- Distinguishing between direct and indirect effects of treatments
- Identification and estimation of mediators
- Assumptions in mediation analysis: sequential ignorability
- Statistical methods for mediation: Baron-Kenny, structural equation modeling

### Readings
- [Baron, Reuben M., and David A. Kenny. 1986. “The Moderator–Mediator Variable Distinction in Social Psychological Research.” *Journal of Personality and Social Psychology* 51(6): 1173–1182.](https://doi.org/10.1037/0022-3514.51.6.1173)
- [VanderWeele, Tyler J. 2015. *Explanation in Causal Inference: Methods for Mediation and Interaction*. Oxford University Press (Chapters 1-3).](https://global.oup.com/academic/product/explanation-in-causal-inference-9780199325870)
- [Imai, Kosuke, Luke Keele, and Dustin Tingley. 2010. “A General Approach to Causal Mediation Analysis.” *Psychological Methods* 15(4): 309–334.](https://doi.org/10.1037/a0020761)

---

## 11.Causal Inference in Survival Analysis 
- Kaplan-Meier curves and their role in survival analysis
- Cox proportional hazards model: assumptions and interpretation
- Random Survival Forests (RSFs) for identifying important predictors
- Estimating treatment effects in time-to-event data


### Readings
- [Cox, D. R. 1972. “Regression Models and Life-Tables.” *Journal of the Royal Statistical Society: Series B* 34(2): 187–220.](https://doi.org/10.1111/j.2517-6161.1972.tb00899.x)
- [Hernán, Miguel A. 2010. “The Hazards of Hazard Ratios.” *Epidemiology* 21(1): 13–15.](https://doi.org/10.1097/EDE.0b013e3181c1ea43)
- [Ishwaran, Hemant, and Udaya B. Kogalur. 2007. “Random Survival Forests for R.” *R News* 7(2): 25–31.](https://www.r-project.org/doc/Rnews/Rnews_2007-2.pdf)

