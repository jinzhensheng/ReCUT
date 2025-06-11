# ReCUT:Balancing Reasoning Length and Accuracy in LLMs via Stepwise Trails and Preference Optimization

# Overview
![](figs/ReCUT.png)
 ReCUT employs a stepwise exploration mechanism and a long-short switched sampling strategy, enabling LLMs to incrementally generate diverse reasoning paths. These paths are evaluated and used to construct preference pairs to train two specialized models (Gemini LLMs)---one optimized for reasoning accuracy, the other for shorter reasoning. A final integrated model is obtained by interpolating the parameters of these two models.
