# Annotated Bibliography

Araújo, M. B., Anderson, R. P., Márcia Barbosa, A., Beale, C. M., Dormann, C. F., Early, R., Garcia, R. A., Guisan, A., Maiorano, L., Naimi, B., O’Hara, R. B., Zimmermann, N. E., & Rahbek, C. (2019). Standards for distribution models in biodiversity assessments. Science Advances, 5(1), eaat4858. https://doi.org/10.1126/sciadv.aat4858

* NB: Make sure to review the Supp Info for this document!!
* Sources of uncertainty include uncertainty in predictor variables and modeling and parameter uncertainty
* Uncertainty also includes location uncertainty
* In terms of achieving the Gold Standard, the authors assert that error propagation of uncertainty is necessary

Beale, C. M., & Lennon, J. J. (2012). Incorporating uncertainty in predictive species distribution modelling. Philosophical Transactions of the Royal Society of London. Series B, Biological Sciences, 367(1586), 247–258. https://doi.org/10.1098/rstb.2011.0178

* Does a nice job breaking up uncertainty into three classes -- data, model, and predictions -- and breaks up models into three 'families' -- niche-based, demographic, and process-based. However it's worth noting that their use of demographic models as a class doesn't match my use (as of where I am in the paper right now).
* They point out some challenges with using the realized niche for prediction. At this point (12 years after this publication), I think these are all pretty well noted issues, but I'm not sure many folks take them into consideration when building forecasting SDMs. 
* Overall, I think these authors do a nice job documenting many of the sources of uncertainty inherent in distribution modeling, and they setup a bit of a framework of how uncertainty could be incorporated, but there are no methodological advances provided here.
* A quote that I think is noteworthy - "Indeed, once appropriate measures of predication uncertainty are available, we expect that for many species our best models are completely uninformative"

Chen, X., Dimitrov, N. B., & Meyers, L. A. (2019). Uncertainty analysis of species distribution models. PLOS ONE, 14(5), e0214190. https://doi.org/10.1371/journal.pone.0214190

* Compares three methods for producing standard errors of SDM estimates - a new analytical approach developed by the authors, a bootstrap approach, and a Poisson PPM approach. This applies to MaxEnt SDMs
* I understand the analytic approach conceptually, but would have to spend much more time on the derivation to feel confident in understanding the maths
* Their take home messages are that their analytic approach is faster than bootstrapping and doesn't include the independence assumption of PPPMs. For their bootstrapping example of the *Aedes aegypti* mosquito, the run took over eight hours, which wouldn't be practical to implement in something like Wallace (I don't think)
* Ultimately, this was thought provoking, and stimulated some interesting ideas, but I'm not sure if this methodology will be implement or used in my final approach.


Diniz‐Filho, J. A. F., Mauricio Bini, L., Fernando Rangel, T., Loyola, R. D., Hof, C., Nogués‐Bravo, D., & Araújo, M. B. (2009). Partitioning and mapping uncertainties in ensembles of forecasts of species turnover under climate change. Ecography, 32(6), 897–906. https://doi.org/10.1111/j.1600-0587.2009.06196.x



Meynard, C. N., Leroy, B., & Kaplan, D. M. (2019). Testing methods in species distribution modelling using virtual species: What have we learnt and what are we missing? Ecography, 42(12), 2021–2036. https://doi.org/10.1111/ecog.04385


Myers, B. J. E., Weiskopf, S. R., Shiklomanov, A. N., Ferrier, S., Weng, E., Casey, K. A., Harfoot, M., Jackson, S. T., Leidner, A. K., Lenton, T. M., Luikart, G., Matsuda, H., Pettorelli, N., Rosa, I. M. D., Ruane, A. C., Senay, G. B., Serbin, S. P., Tittensor, D. P., & Beard, T. D. (2021). A New Approach to Evaluate and Reduce Uncertainty of Model-Based Biodiversity Projections for Conservation Policy Formulation. BioScience, 71(12), 1261–1273. https://doi.org/10.1093/biosci/biab094

Naimi, B., Hamm, N., Groen, T., Skidmore, A., & Toxopeus, A. (2014). Where is positional uncertainty a problem for species distribution modeling? Ecography, 37, 191–203. https://doi.org/10.1111/j.1600-0587.2013.00205.x

Serra‐Diaz, J. M., Borderieux, J., Maitner, B., Boonman, C. C. F., Park, D., Guo, W., Callebaut, A., Enquist, B. J., Svenning, J., & Merow, C. (2024). occTest: An integrated approach for quality control of species occurrence data. Global Ecology and Biogeography, e13847. https://doi.org/10.1111/geb.13847

* occTest is a neat new package that evalutates occurence points
* how is this related to uncertainty? I think it is related in that the points you include in an analysis likely have an impact on the outcomes (this seems obvious, but I'm not actually aware of that many analyses that test to robustness of this). 
* seems to me that a test of uncertainty could include analyses with vs without various thresholds of filtering
* TO-DO - consider how I might incorporate this package into uncertainty analyses

Steen, B., Broennimann, O., Maiorano, L., & Guisan, A. (2024). How sensitive are species distribution models to different background point selection strategies? A test with species at various equilibrium levels. Ecological Modelling, 493, 110754. https://doi.org/10.1016/j.ecolmodel.2024.110754


Stoklosa, J., Daly, C., Foster, S. D., Ashcroft, M. B., & Warton, D. I. (2015). A climate of uncertainty: Accounting for error in climate variables for species distribution models. Methods in Ecology and Evolution, 6, 412–423. https://doi.org/10.1111/2041-210X.12217

* Need to read this paper in full, but last sentence of the abstract is important - "Our results indicate that the best approach is to use stratified random in environmental space BP sampling if accuracy is essential, and fully random in environmental space BP sampling if model stability is essential."

Zurell, D., Franklin, J., König, C., Bouchet, P. J., Dormann, C. F., Elith, J., Fandos, G., Feng, X., Guillera‐Arroita, G., Guisan, A., Lahoz‐Monfort, J. J., Leitão, P. J., Park, D. S., Peterson, A. T., Rapacciuolo, G., Schmatz, D. R., Schröder, B., Serra‐Diaz, J. M., Thuiller, W., … Merow, C. (2020). A standard protocol for reporting species distribution models. Ecography, ecog.04960. https://doi.org/10.1111/ecog.04960

* This is the ODMAP paper, or the paper the introduces the ODMAP procedure.
* The authors include "Uncertainty quantification" as one of the sections of ODMAP to be filled out, but they do not necessarily provide any suggested ways / best practices to consider or incorporate uncertainty into SDMs. 
* Interestingly, they cite Beale and Lennon 2012 as evidence that there are tools for dealing with uncertainty, but this was not me read on the Beale and Lennon paper. As I say above, I thought they did a great job at pointing out the different sources of uncertainty, but not necessarily in identifying how to quantify them.