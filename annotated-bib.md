# Annotated Bibliography

Beale, C. M., & Lennon, J. J. (2012). Incorporating uncertainty in predictive species distribution modelling. Philosophical Transactions of the Royal Society of London. Series B, Biological Sciences, 367(1586), 247–258. https://doi.org/10.1098/rstb.2011.0178


Chen, X., Dimitrov, N. B., & Meyers, L. A. (2019). Uncertainty analysis of species distribution models. PLOS ONE, 14(5), e0214190. https://doi.org/10.1371/journal.pone.0214190

* Compares three methods for producing standard errors of SDM estimates - a new analytical approach developed by the authors, a bootstrap approach, and a Poisson PPM approach. This applies to MaxEnt SDMs
* I understand the analytic approach conceptually, but would have to spend much more time on the derivation to feel confident in understanding the maths
* Their take home messages are that their analytic approach is faster than bootstrapping and doesn't include the independence assumption of PPPMs. For their bootstrapping example of the *Aedes aegypti* mosquito, the run took over eight hours, which wouldn't be practical to implement in something like Wallace (I don't think)
* Ultimately, this was thought provoking, and stimulated some interesting ideas, but I'm not sure if this methodology will be implement or used in my final approach.

Myers, B. J. E., Weiskopf, S. R., Shiklomanov, A. N., Ferrier, S., Weng, E., Casey, K. A., Harfoot, M., Jackson, S. T., Leidner, A. K., Lenton, T. M., Luikart, G., Matsuda, H., Pettorelli, N., Rosa, I. M. D., Ruane, A. C., Senay, G. B., Serbin, S. P., Tittensor, D. P., & Beard, T. D. (2021). A New Approach to Evaluate and Reduce Uncertainty of Model-Based Biodiversity Projections for Conservation Policy Formulation. BioScience, 71(12), 1261–1273. https://doi.org/10.1093/biosci/biab094


Zurell, D., Franklin, J., König, C., Bouchet, P. J., Dormann, C. F., Elith, J., Fandos, G., Feng, X., Guillera‐Arroita, G., Guisan, A., Lahoz‐Monfort, J. J., Leitão, P. J., Park, D. S., Peterson, A. T., Rapacciuolo, G., Schmatz, D. R., Schröder, B., Serra‐Diaz, J. M., Thuiller, W., … Merow, C. (2020). A standard protocol for reporting species distribution models. Ecography, ecog.04960. https://doi.org/10.1111/ecog.04960