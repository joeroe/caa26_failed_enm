---
bibliography: "./references.bib"
csl: "./chicago-author-date.csl"
---
Paper submission to the Computer Applications & Quantitative Methods in Archaeology (CAA) Conference, Vienna, 31st March–4th April 2026

# Can ecological models predict the occurrence of species in the archaeological record? Can I?

**Joe Roe** <<https://joeroe.io>>  
Department of Cross Cultural and Regional Studies & School of Archaeology  
University of Copenhagen, Denmark

## Abstract

Ecological niche models, also known as species distribution models, are widely used by ecologists to quantify the relationship between the environment and the geographic extent of an organism [@SilleroEtAl2021].
Conceptually similar to 'predictive modelling' in archaeology, they involve training a model from known occurrences of the organism and a set of relevant environmental variables at those locations.
The trained model can be studied in itself or, more commonly, used to *predict* the occurrence of the organism in another environmental space.
This could be to anticipate the organism's response to future climate change, to model a hypothetical introduction of the organism to a new region or---most interestingly in the present context---reconstruct the palaeodistribution of the organism in a past environment.
@FranklinEtAl2015 observed a decade ago that the latter application could hold great interest for archaeological research – and also that data from environmental archaeology on known past occurrences could provide a key means of verifying 'hindcasted' ecological niche models.
Archaeologists have (with notable exceptions) been relatively slow to take up this call, perhaps due to the difficulty of obtaining the necessary palaeoclimatic data.
To my knowledge, there have been no reported uses of archaeological occurrences to verify a hindcast ecological niche model.

In a recent study [@RoeArranzOtaegui2025], I used ecological niche modelling to reconstruct the terminal Pleistocene and Early Holocene biogeography of 65 plant species found regularly in association with early agricultural archaeological sites in West Asia, including the progenitors of the first crops.
The scope of the study expanded significantly over the six years I worked on it, presenting technical challenges that were exacerbated by the need to incorporate a large number of 'best practices' drawn from the extensive literatures on ecological niche modelling on the one hand, and prediction using machine learning on the other.
The sense of relief in finally overcoming these challenges and producing models that performed well on all the standard metrics was short-lived, however, because they all spectacularly failed to predict the real past palaeodistributions revealed by the archaeological record.
When double- and triple-checking that I did the modelling correctly didn't change the situation, I was forced to invoke Box's law ["all models are wrong, but some are useful", @Box1976] and focus on other insights the results could provide.

Yet reflecting on *why* these models failed verification has proved, if anything, more interesting than the original study.
Is it a failure of this particular model (i.e., is it just my fault)?
Or is there a fundamental problem of transferability of ecological niche models applied to the past?
In either case, is it possible to rectify the situation?
Here I argue that, while methodological improvements could certainly be made, especially to mitigate overfitting, the mismatch between hindcast model and the archaeological record cannot simply be put down to the model being 'wrong'.
Instead it prompts us to think more explicitly about what past process—or processes—these two different signals represent and, crucially, how they have been transformed.
In particular, both palaeodistribution models (via the palaeoclimate surfaces used to produce them) and environmental archaeology represent temporally "mixed assemblages" [@Perreault2019, pp. 40-79], but mixed in different ways.
With this in mind, the expectation that the archaeological record could straightforwardly 'verify' ecological niche models is probably too naive.
But it suggests ways in which the two signals could be brought closer together, for example by formally incorporating palaeoclimatic variability and modelling of depositional processes, in a way that would benefit not just environmental archaeology but wider debates on the transferability of ecological niche models [@Franklin2023].

## Keywords

ecological niche modelling, species distribution modelling, machine learning, environmental archaeology, archaeobotany

## References
