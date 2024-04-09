---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

This is a temporary page to present additional experiment results and analysis for anonymous rebuttal.

Currently this page contains extra rebuttal contents of <b>submission 1763 *Team up GBDTs and DNNs: Advancing Efficient and Effective Tabular Prediction with Tree-hybrid MLPs*</b> in KDD 24'. <b>All used reference No. follow the original one in the paper</b> if without specification.


# 💬 To R twnd 

- xxx

# 💬 To R pAZD

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 💬 To R F2J2
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 To R jHCg
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 To R LYyH 
|              | GE     | CH     | EY     | CA    | HO    | AD    | OT     | HE      | JA     | HI     | FB     | YE     | avg    |
| :----------- | -----: | -----: | -----: | ----: | ----: | ----: | -----: | ------: | -----: | -----: | -----: | -----: | -----: |
| XGBoost(T)   | x14\.72 | x8\.32  | x14\.05 | x3\.87 | x2\.75 | x6\.13 | x29\.89 | x273\.80 | x71\.17 | x24\.13 | x32\.85 | x25\.42 | x42\.26 |
| xXGBoost(T\*) | x12\.93 | x11\.04 | x11\.21 | x2\.57 | x2\.99 | x7\.39 | x8\.65  | x425\.65 | x24\.35 | x4\.46  | x22\.67 | x17\.69 | x45\.97 |


# 💬 To R hswh

<table style="border-collapse: collapse; border: none; border-spacing: 0px;">
	<caption>
	  ​​<b>Default hyperparameters (HPs) of T-MLP in this paper</b>
	</caption>
	<tr>
		<td colspan="2" style="border-bottom: 1px solid rgb(0, 0, 0); border-top: 1px solid rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt;">
			T-MLP’s GBDT architecture: XGBoost
		</td>
	</tr>
	<tr>
		<td style="border-top: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Model HPs
		</td>
		<td rowspan="2" style="border-left: 1px solid windowtext; border-top: 1px solid rgb(0, 0, 0); border-bottom: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Same as the default XGBoost configs used in the Table 4 of FT-T paper [23], you can find and download the HP config file from its <a href="https://github.com/yandex-research/rtdl-revisiting-models/blob/main/output/adult/xgboost/default/0/stats.json"><u>repo</u></a>, other unmentioned HPs are kept default as <a href="https://xgboost.readthedocs.io/en/stable/python/python_api.html#module-xgboost.sklearn"><u>XGBoost official APIs</u></a>.
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Training HPs
		</td>
	</tr>
	<tr>
		<td colspan="2" style="border-top: 1px solid rgb(0, 0, 0); border-bottom: 1px solid rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt;">
			T-MLP’s DNN architecture: MLP
		</td>
	</tr>
	<tr>
		<td colspan="2" style="border-top: 1px solid rgb(0, 0, 0); border-bottom: 1px solid rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt;">
			Model HPs
		</td>
	</tr>
	<tr>
		<td style="border-top: 1px solid rgb(0, 0, 0); border-right: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Hidden size
		</td>
		<td style="border-top: 1px solid rgb(0, 0, 0); border-left: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			1024; decided by keeping equivalent storage space as the MLP baselines in [23]
		</td>
	</tr>
	<tr>
		<td style="border-right: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Intermediate factor
		</td>
		<td style="border-left: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			2/3, i.e., with an intermediate size of 1024 x 2/3 = 676; refer to the one in FT-T [23]
		</td>
	</tr>
	<tr>
		<td style="border-right: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Residual dropout
		</td>
		<td style="border-left: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			0.1; refer to the one in FT-T [23]
		</td>
	</tr>
	<tr>
		<td style="border-right: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Layer count
		</td>
		<td style="border-left: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			1
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 1px solid rgb(0, 0, 0); border-right: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Sparsity rate
		</td>
		<td style="border-bottom: 1px solid rgb(0, 0, 0); border-left: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			0.33, the only HP for controlled pruning algorithm referring to CoFi [62]
		</td>
	</tr>
	<tr>
		<td colspan="2" style="border-top: 1px solid rgb(0, 0, 0); border-bottom: 1px solid rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt;">
			Training HPs
		</td>
	</tr>
	<tr>
		<td style="border-top: 1px solid rgb(0, 0, 0); border-right: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Learning rate
		</td>
		<td style="border-top: 1px solid rgb(0, 0, 0); border-left: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			(A)&nbsp;&nbsp; For single T-MLP, 1e-4; (B) For ensemble version, i.e., T-MLP(3), using 1e-4, 5e-4, 1e-3 for three branches respectively; refer to [23]
		</td>
	</tr>
	<tr>
		<td style="border-right: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Weight decay
		</td>
		<td style="border-left: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			0
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 1px solid rgb(0, 0, 0); border-right: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Optimizer
		</td>
		<td style="border-bottom: 1px solid rgb(0, 0, 0); border-left: 1px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			AdamW, with all other training HPs kept default
		</td>
	</tr>
</table>