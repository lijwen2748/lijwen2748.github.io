---
title: "simplecar"
collection: tools
type: "model checker"
permalink: /tools/2023-07-17-simplecar
venue: "Software Engineering, ECNU"
date: 2023-07-17
location: "Shanghai, China"
excerpt: "`simplecar` is a simple implementation of **CAR** (Complementary Approximate Reachability), which is a novel safety model checker algorithm and was presented since 2017."
---

`simplecar` is a simple implementation of **CAR** (Complementary Approximate Reachability), which is a novel safety model checker algorithm and was presented since 2017. 

> The tool can be downloaded [here](https://github.com/lijwen2748/simplecar).

## Related Publications:

- Searching for i-Good Lemmas to Accelerate Safety Model Checking. Yechuan Xia, Anna Becchi, Alessandro Cimatti, Alberto Griggio, **Jianwen Li**\*, and Geguang Pu\*. International Conference on Computer Aided Verification (CAV), 2023. [\[pdf\]](CAV2023.pdf)
> This paper is our first attempt to investigate **what** is the key factor to affect the performance of CAR and **how** to search (instead of compute) them effectively during runtime. The experimental results are suprisingly good, though the heuritics are straightforward. 

- Accelerate Safety Model Checking Based on Complementary Approximate Reachability. Xiaoyu Zhang, Shengping Xiao, Yechuan Xia, **Jianwen Li**\*, Mingsong Chen, and Geguang Pu. Transaction on Computer Aided Design (TCAD), 2022. [\[pdf\]](TCAD2022.pdf)
> This paper focus on safety checking (correctness proof), and present several heuristics to acceralate the performance of forward CAR. The results show the combination of forward+backward CAR have an overall better perfromance than forward+backward IC3/PDR.

- Combining BMC and Complementary Approximate Reachability to Accelerate Bug-Finding. Xiaoyu Zhang, Shengping Xiao, **Jianwen Li**\*, Geguang Pu, Ofer Strichman. International Conference on Computer Aided Design (ICCAD), 2022. [\[pdf\]](ICCAD2022.pdf)
> This paper presents three different ways to combine BMC and CAR, trying to pursue a better bug-finding (unsafety checking) algorithm than the state-of-the-art BMC. 

- Finding More Property Violations in Model Checking via the Restart Policy. Mengtao Geng, Xiaoyu Zhang and **Jianwen Li**. Electronics, 2021. [\[pdf\]](Electronics2021.pdf)
> This paper considered to import the restart strategy from the SAT community to accelerate the bug-finding performance of CAR. 

- Intersection and Rotation of Assumption Literals Boosts Bug-Finding. Rohit Dureja, **Jianwen Li**, Geguang Pu, Moshe Y. Vardi and Kristin Y. Rozier. 11th Working Conference on Verified Software: Theories, Tools, and Experiments (VSTTE), 2019. [\[pdf\]](VSTTE2019.pdf)
> This paper explores how using different assumption orderings to invoke the SAT solver can affect significantly the performance of CAR (particularly on bug detection). 

- SimpleCAR: An Efficient Bug-Finding Tool Based on Approximate Reachability. **Jianwen Li**, Rohit Dureja, Geguang Pu, Kristin Y. Rozier1 and Moshe Y. Vardi. International Conference on Computer Aided Verification (CAV), 2018. [\[pdf\]](CAV2018.pdf)
> This is the official paper to release our model checker.

- Safety Model Checking with Complementary Approximations. **Jianwen Li**, Shufang Zhu, Yueling Zhang, Geguang Pu and Moshe Y. Vardi. International Conference on Computer Aided Design (ICCAD), 2017. [\[pdf\]](ICCAD2017.pdf)
> This is the first paper to propose CAR. The fundamental theories and principles are established in this paper, though the results are not exciting enough (when compared to IC3/PDR).  




