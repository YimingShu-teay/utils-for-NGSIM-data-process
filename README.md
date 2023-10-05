### Brief Introduction

This code was written quite some time ago for the purpose of processing the NGSIM dataset. While it might not be the epitome of organization or high efficiency, it should serve as a valuable starting point for those venturing into data processing.

This data processing is aimed at **extracting lane-changing points of vehicles and capturing feature information of traffic flow scenarios during lane changes**.

Here is the link to get NGSIM dataset: https://data.transportation.gov/Automobiles/Next-Generation-Simulation-NGSIM-Vehicle-Trajector/8ect-6jqj

### Main Function

1.Extraction of the driving trajectories of each lane-changing vehicle in the vicinity of lane-change points within the NGSIM dataset.



<div align=center><img width="650" height="550" src="https://github.com/YimingShu-teay/utils-for-NGSIM-data-process/blob/main/fig/fig2.png"/></div>



2.Treating each lane-changing vehicle as an ego vehicle, we obtained the traffic scenarios at their lane-change points.

<div align=center><img width="650" height="550" src="https://github.com/YimingShu-teay/utils-for-NGSIM-data-process/blob/main/fig/fig3.png"/></div>



3.Extraction of traffic features within a minimal unit scenario.

<div align=center><img width="650" height="350" src="https://github.com/YimingShu-teay/utils-for-NGSIM-data-process/blob/main/fig/fig1.png"/></div>



### Further Reading

[1]. Zhang Y, Xu Q, Wang J, et al. A learning-based discretionary lane-change decision-making model with driving style awareness[J]. IEEE transactions on intelligent transportation systems, 2022, 24(1): 68-78.

[2]. Liu Y, Wang X, Li L, et al. A novel lane change decision-making model of autonomous vehicle based on support vector machine[J]. IEEE access, 2019, 7: 26543-26550.