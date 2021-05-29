# Estimation of the actual incidence of coronavirus disease (COVID-19) in emergent hotspots

Supporting Materials for Andrei R. Akhmetzhanov, Kenji Mizumoto, Sung-mok Jung, Natalie M. Linton, Ryosuke
Omori, Hiroshi Nishiura. Estimation of the actual incidence of coronavirus disease (COVID-19) in emergent hotspots: The example of Hokkaido, Japan during February–March 2020. Journal of Clinical Medicine. 2021, 10, 2392. ([doi:10.3390/jcm10112392](https://doi.org/10.3390/jcm10112392))

[See also pdf version on github](https://github.com/aakhmetz/Covid19IncidenceHokkaidoFeb2020/blob/master/manuscript/2021%20Akhmetzhanov%20et%20al%20Hokkaido%20paper%20JCM.pdf)

**Abstract**
Following the first report of coronavirus disease 2019 (COVID-19) in Sapporo City, Hokkaido Prefecture, Japan on 14 February 2020, a surge of cases was observed in Hokkaido during February and March. As of 6 March, 90 cases were diagnosed in Hokkaido. Unfortunately, many infected persons may not have been recognized as cases due to having mild or no symptoms. We therefore estimated the actual number of COVID-19 cases in (i) Hokkaido Prefecture and (ii) Sapporo City using data on cases diagnosed outside these areas. The estimated cumulative incidence in Hokkaido as of 27 February was 2297 cases (95% confidence interval [CI]: 382, 7091) based on data on travelers outbound from Hokkaido. The cumulative incidence in Sapporo City as of 28 February was estimated at 2233 cases (95% CI: 0, 4893) based on the count of confirmed cases within Hokkaido. Both approaches resulted in similar estimates, indicating higher incidence of infections in Hokkaido than were detected by the surveillance system. This quantification of the gap between detected and estimated cases can help inform public health response as it provides insight into the possible scope of undetected transmission.

[**The main notebook of this study**](https://nbviewer.jupyter.org/github/aakhmetz/Covid19IncidenceHokkaidoFeb2020/blob/master/scripts/%20Main%20analysis%20%28python%2C%20PyMC3%29.ipynb) 

<p align="center">
  <img src="manuscript/cover%20Hokkaido%20paper.png" title="Map">
</p>

---------
**Thank you for your interest to our work!** 

The notebook was written in Python using the geopandas package for mapping and the PyMC3 package (version 3.8) for Bayesian inference.

Few words of caution: We would like to note that our code is not supposed to work out of box, because the links used in the notebooks were user-specific, and our main intent was to show the relevance of the methods used in our paper.
