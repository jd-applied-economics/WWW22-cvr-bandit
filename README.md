# Adaptive Experimentation with Delayed Binary Feedback
Accepted at the Web Conference 2022.
[arXiv preprint](https://arxiv.org/pdf/2202.00846.pdf)

## Citation
Zenan Wang, Carlos Carrion, Xiliang Lin, Fuhua Ji, Yongjun Bao, and Weipeng
Yan. 2022. Adaptive Experimentation with Delayed Binary Feedback. In
_Proceedings of the ACM Web Conference 2022 (WWW ’22), April 25–29, 2022,
Virtual Event, Lyon, France_. ACM, New York, NY, USA, 9 pages. https:
//doi.org/10.1145/3485447.3512097


## Abstract 
Conducting experiments with objectives that take significant delays to materialize (e.g. conversions, add-to-cart events, etc.) is challenging. Although the classical "split sample testing" is still valid for the delayed feedback, the experiment will take longer to complete, which also means spending more resources on worse-performing strategies due to their fixed allocation schedules. 
Alternatively, adaptive approaches such as "multi-armed bandits" are able to effectively reduce the cost of experimentation. But these methods generally cannot handle delayed objectives directly out of the box. This paper presents an adaptive experimentation solution tailored for delayed binary feedback objectives by estimating the real underlying objectives before they materialize and dynamically allocating variants based on the estimates. Experiments show that the proposed method is more efficient for delayed feedback compared to various other approaches and is robust in different settings. In addition, we describe an experimentation product powered by this algorithm. This product is currently deployed in the online experimentation platform of JD.com, a large e-commerce company and a publisher of digital ads.

## Keywords
Multi-armed Bandit, Delayed Feedback, Conversion Rate (CVR), Display Ads, Experimentation Platform, Deployed System

## Simulation Code
[Paper Simulation Code](paper_appendix_simulation.Rmd)