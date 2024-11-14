---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

## Working Papers

### <strong>Non-Gaussian Structural Vector Autoregression with Unknown Break Points</strong> 
(Job market paper)

<a href="javascript:void(0)" onclick="toggleAbstract('abstract1')" style="font-size: 12px; text-decoration: underline; color: #007bff; cursor: pointer;"> Abstract</a> <a href="https://keyanliu1.github.io/files/jmp14112024.pdf" style="font-size: 12px;"><strong>Current Version (PDF)</strong></a>

<div id="abstract1" style="display:none; font-size: 0.85em;">
  <p>In this paper, I consider testing and estimating non-Gaussian Structural Vector Autoregressive models with unknown break points (SVAR-BP). This model extends traditional SVAR analysis by allowing for unknown breakpoints, capturing potential changes in both autoregressive coefficients and structural parameters. I employ the Partial Sample Generalized Method of Moments (PSGMM) to estimate the model and utilize the sup-Wald test to assess parameter stability. Additionally, I establish the asymptotic properties of the break point estimators and propose a sequential procedure for detecting and estimating multiple break points. My method is applied to a U.S. macroeconomic dataset from 1954 to 2023, where I identify significant structural breaks corresponding to key economic events. The results demonstrate the ability of my approach to detect and estimate multiple break points, modeling shifts in the dynamics of economic variables.</p>
</div>



### <strong>Identifying Structural Vector Autoregressions via Non-Gaussianity of Potentially Dependent Structural Shocks</strong> 
(with Markku Lanne and Jani Luoto). Revise &amp; Resubmit at *Journal of Business &amp; Economic Statistics*

<a href="javascript:void(0)" onclick="toggleAbstract('abstract2')" style="font-size: 12px; text-decoration: underline; color: #007bff; cursor: pointer;">Abstract</a> <a href="https://keyanliu1.github.io/files/Paper2.pdf" style="font-size: 12px;"><strong>Current Version (PDF)</strong></a>

<div id="abstract2" style="display:none; font-size: 0.85em;">
  <p>We show that all shocks in an $n$-dimensional structural vector autoregression (SVAR) are globally identified up to their order and signs if they are orthogonal and either (i) have zero co-skewness and at most one of them is not skewed or (ii) exhibit no excess co-kurtosis and at least $n-1$ of them are leptokurtic. The former case covers SVAR models with errors following dependent volatility processes. Moreover, if the numbers of both skewed and leptokurtic shocks are smaller than $n-1$, the skewed and leptokurtic shocks are globally identified, while the remaining shocks are set identified. To capture the non-Gaussian features of the data, versatile error distributions are needed. We discuss the Bayesian implementation of an SVAR-GARCH model with skewed <i>t</i>-distributed errors, including the assessment of the strength of identification and checking the validity of exogenous instruments potentially used for identification. The methods are illustrated in an empirical application to the oil market.</p>
</div>


## Publications

### <strong>Identifying Structural Vector Autoregression via Leptokurtic Economic Shocks</strong> 
(with Markku Lanne and Jani Luoto). *Journal of Business &amp; Economic Statistics*, 2023

<a href="javascript:void(0)" onclick="toggleAbstract('abstract3')" style="font-size: 12px; text-decoration: underline; color: #007bff; cursor: pointer;">Abstract</a> <a href="https://keyanliu1.github.io/files/Paper11.pdf" style="font-size: 12px;"><strong>Published Version (PDF)</strong></a> <a href="https://keyanliu1.github.io/files/paper1appendix.pdf" style="font-size: 12px;"><strong>Appendix</strong></a>

<div id="abstract3" style="display:none; font-size: 0.85em;">
  <p>We revisit the generalized method of moments (GMM) estimation of the non-Gaussian structural vector autoregressive (SVAR) model. It is shown that in the $n$-dimensional SVAR model, global and local identification of the contemporaneous impact matrix is achieved with as few as $n^2+n(n-1)/2$ suitably selected moment conditions, when at least $n-1$ of the structural errors are all  leptokurtic (or platykurtic). We also relax the potentially problematic assumption of mutually independent structural errors in part of the previous literature to the requirement that the errors be mutually uncorrelated. Moreover, we assume the error term to be only serially uncorrelated, not independent in time, which allows for univariate conditional heteroskedasticity in its components. A small simulation experiment highlights the good properties of the estimator and the proposed moment selection procedure. The use of the methods is illustrated by means of an empirical application to the effect of a tax increase on U.S. gasoline consumption and carbon dioxide emissions.</p>
</div>


## Working in Progress

### <strong>Inference for Weakly identified Non-Gaussian Structural Vector Autoregression</strong> 
(with Jani Luoto)

<script>
function toggleAbstract(id) {
  var element = document.getElementById(id);
  if (element.style.display === "none") {
    element.style.display = "block";
  } else {
    element.style.display = "none";
  }
}
</script>
