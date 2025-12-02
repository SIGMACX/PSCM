
# PSCM: Pseudo-Label Self-Correction with Mask Learning for Semi-Supervised Medical Image Segmentation
## The code will be released later.

<!-- PROJECT SHIELDS -->

<!-- PROJECT LOGO -->
<br />

<p align="center">
  <a href="https://github.com/SIGMACX/PSCM">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">PSCM</h3>
  <p align="center">
    Pseudo-Label Self-Correction with Mask Learning for Semi-Supervised Medical Image Segmentation
    <br />
<!--     <a href=""><strong>EXPLORE THE DOCUMENTATION FOR THIS PROJECT »</strong></a> -->
    <br />
    <br />
<!--     <a href="https://github.com/shaojintian/Best_README_template">查看Demo</a> -->
    ·
<!--     <a href="https://github.com/shaojintian/Best_README_template/issues">报告Bug</a>
    ·
    <a href="https://github.com/shaojintian/Best_README_template/issues">提出新特性</a> -->
  </p>

</p>

【Abstract】
Semi-supervised medical image segmentation has emerged as a promising approach for reducing the reliance on extensive manual annotations. However, existing methods still face two key challenges. First, pseudo-label learning is easily corrupted by structural errors, which can lead to inaccurate predictions being reinforced during consistency training. Second, mask learning often amplifies errors due to heuristic and structure-agnostic masking strategies. To address the above issues, we propose a unified framework for Pseudo-Label Self-Correction with Mask Learning (PSCM). PSCM integrates three complementary components to enhance pseudo-label reliability and strengthen representation learning under mask learning. First, the pseudo-label self-correction (PSC) module rectifies pseudo-labels by enforcing structural consistency between labeled and unlabeled samples. Furthermore, the bi-level optimal mask learning (BOM) strategy adaptively selects uncertain and boundary-sensitive regions for mask learning, thereby improving representation quality and enabling targeted error suppression. Additionally, the auxiliary decoder (AUD) enhances feature robustness by aligning model representations across factual and counterfactual environments, thereby effectively mitigating the impact of distributional shifts and improving generalization performance. Comprehensive experiments were conducted on five widely used 3D and 2D benchmark datasets, including MSD-Lung Tumor, NIH-Pancreas, Left Atrium, AMOS, and M&M. The results show that PSCM consistently delivers improved segmentation performance across different annotation ratios. 

![image](https://github.com/SIGMACX/PSCM/main/Main.pdf)

<!-- links -->
[your-project-path]:shaojintian/Best_README_template
[contributors-shield]: https://img.shields.io/github/contributors/shaojintian/Best_README_template.svg?style=flat-square
[contributors-url]: https://github.com/shaojintian/Best_README_template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/shaojintian/Best_README_template.svg?style=flat-square
[forks-url]: https://github.com/shaojintian/Best_README_template/network/members
[stars-shield]: https://img.shields.io/github/stars/shaojintian/Best_README_template.svg?style=flat-square
[stars-url]: https://github.com/shaojintian/Best_README_template/stargazers
[issues-shield]: https://img.shields.io/github/issues/shaojintian/Best_README_template.svg?style=flat-square
[issues-url]: https://img.shields.io/github/issues/shaojintian/Best_README_template.svg
[license-shield]: https://img.shields.io/github/license/shaojintian/Best_README_template.svg?style=flat-square
[license-url]: https://github.com/shaojintian/Best_README_template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/shaojintian




