---
title: "PK-APF: Path-Keeping Algorithm for USVs Based on Artificial Potential Field"
collection: publications
permalink: /publication/applsci22
excerpt: ''
date: 2022-08-17
venue: 'Applied Sciences'
paperurl: ''
citation: 'Y. Chu, Z. Wu, Y. Yue, X. Zhu, E. G. Lim, and P. Paoletti, “PK-APF: Path-Keeping Algorithm for USVs Based on Artificial Potential Field,” Applied Sciences, vol. 12, no. 16, p. 8201, Aug. 2022, doi: 10.3390/app12168201.'
---

Abstract: Path-keeping requires unmanned surface vehicles (USVs) to follow a planned path in autonomous navigation. It is essential for USVs to carry out autonomous tasks such as collecting various data of water quality and surrounding terrain for exploration and protection of water environments. However, due to obstacle avoidance and other factors such as wind, water waves, and dynamics of USVs, USVs usually deviate from the original planned path during autonomous navigation. This paper proposes a novel path-keeping algorithm based on the artificial potential field method (PK-APF) for USVs. To minimize the deviation between the actual path and the original planned path, the vertical distance and the virtual foot points of the current position of USVs to the original path (a line connecting the previous navigation point and the next navigation point) are calculated. When the vertical distance is larger than a threshold, we regard the vertical foot point as a virtual goal point to guide the USVs to navigate the original path in real-time to achieve high-precision path-keeping. Obstacle avoidance is simulated in the MATLAB and Virtual RobotX (VRX) simulators, and the influence of wind and water waves is considered in VRX. Experiments are conducted in typical scenarios and results show that PK-APF outperforms the traditional APF by at least 22%. The work provides an important basis for real-life environments. Substantial further work is planned for applying the method on a physical USV.

Keywords: path-keeping; artificial potential field; virtual foot points; USVs; VRX; MATLAB

[[Download paper here]](https://www.mdpi.com/2076-3417/12/16/8201)

Bibtex:

```
@Article{app12168201,
AUTHOR = {Chu, Yijie and Wu, Ziniu and Yue, Yong and Zhu, Xiaohui and Lim, Eng Gee and Paoletti, Paolo},
TITLE = {PK-APF: Path-Keeping Algorithm for USVs Based on Artificial Potential Field},
JOURNAL = {Applied Sciences},
VOLUME = {12},
YEAR = {2022},
NUMBER = {16},
ARTICLE-NUMBER = {8201},
URL = {https://www.mdpi.com/2076-3417/12/16/8201},
ISSN = {2076-3417},
ABSTRACT = {Path-keeping requires unmanned surface vehicles (USVs) to follow a planned path in autonomous navigation. It is essential for USVs to carry out autonomous tasks such as collecting various data of water quality and surrounding terrain for exploration and protection of water environments. However, due to obstacle avoidance and other factors such as wind, water waves, and dynamics of USVs, USVs usually deviate from the original planned path during autonomous navigation. This paper proposes a novel path-keeping algorithm based on the artificial potential field method (PK-APF) for USVs. To minimize the deviation between the actual path and the original planned path, the vertical distance and the virtual foot points of the current position of USVs to the original path (a line connecting the previous navigation point and the next navigation point) are calculated. When the vertical distance is larger than a threshold, we regard the vertical foot point as a virtual goal point to guide the USVs to navigate the original path in real-time to achieve high-precision path-keeping. Obstacle avoidance is simulated in the MATLAB and Virtual RobotX (VRX) simulators, and the influence of wind and water waves is considered in VRX. Experiments are conducted in typical scenarios and results show that PK-APF outperforms the traditional APF by at least 22%. The work provides an important basis for real-life environments. Substantial further work is planned for applying the method on a physical USV.},
DOI = {10.3390/app12168201}
}
```
