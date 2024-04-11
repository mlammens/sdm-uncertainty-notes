# Ideas and Thoughts

## Sources of uncertainty

* inputs
    * presences
    * absences
    * background points
    * environmental layers
        * different sources for the same variables - i.e., temperature from WorldClim vs PRISM, etc.
* models
    * just looking over Diniz-Filho et al. 2009, I see that they found the greatest source of uncertainty in predictions came from SDM choice. I wonder if this is still true? **Has there been any similar updates in partitioning uncertainty since this paper?**


## What parameters need to vary?

In my past GSA work on demographic models, I first identified all of the variables / parameters that could be uncertain going in to the model. 
It seems obvious, but that seems like a good approach here too.
This does seem like it will vary quite a bit based on the model choice though.
Given that Wallace only currently supports BIOCLIM and maxent, it would seem reasonable to start here.

### Using Valavi et al as a model?

An approach that comes to mind is to go through the Valavi et al 2022 paper and play with that code to examine the impacts of varying input parameter values.


## Use of simulate species

* Consider using simulated species to examine spatial thinning parameters (see also written notes)
* What role could simulations have? I suppose the would limit one source of uncertainty - or allow us to control for it - which is species locations