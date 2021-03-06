---
title: "Model Transferability"
categories:
 
---

Summary
-------

Model parameters are generally estimated using data from sources such as travel surveys. Such surveys can be difficult and expensive to conduct in a manner that leads to sufficient sample sizes for parameter estimation, especially in smaller planning regions where resources may be quite limited. This means that in many areas, there are insufficient recent survey data for model parameter estimation. This has led to the practice of model transfer in many areas. Model parameters that have been estimated in one context (the "estimation context") are used to create parameters for use in the "application context."

Regardless of a region's size, attempting to transfer a model from another urban region should be carefully considered. Unlike other engineering models, transportation models are highly sensitive to urban context. Region's with a distinctive economic base (e.g. university town, resort area), demographic profile (e.g. seniors, young professionals) or terrain (e.g. mountain valleys, coastal zones, deserts) will display equally distinctive travel demand patterns that may contradict parameters that works perfectly well in an otherwise similar-sized region. Note also that the task of transferring *parameters* from another region is entirely separate from that of transferring the *modeling code* as applied in that region. The two tasks can easily confound each other.

The process of model transfer has become commonplace in transportation planning as resources for planning continue to be constrained. Since the late 1970’s, the National Cooperative Highway Research Program (NCHRP) has published guidebooks that provide transferable parameters, the latest of which, [Report 716: Travel Demand Forecasting: Parameters and Techniques](http://www.trb.org/Publications/Blurbs/167055.aspx%7CNCHRP), was released in 2012. The parameters provided in these reports reflect national averages, based in part on data from the National Household Travel Survey (NHTS). However, while these publications have provided some guidance to planners transferring parameters, the discussion of the transfer process is limited, and alternatives to using the national parameters are not discussed in great detail.

In 2014 the Federal Highway Administration, through the Travel Model Improvement Program (TMIP), published a [Guide for Model Transfer](https://www.fhwa.dot.gov/planning/tmip/publications/other_reports/travel_model_transfer/). The
report provides guidance to transportation planners on alternative approaches to model transfer based on the amount of available resources. The guidance, which is based on research that has been conducted on model transferability, is supplemented with simple examples of the various model transfer methods. The report presents the following concepts and findings regarding the process of model transfer and model transferability.

-   The correct way to transfer model parameters is to transfer the entire model, while examining whether the set of parameters needs to be scaled to the application context.

<!-- -->

-   When transferring models, choosing the best estimation context can greatly enhance model transferability.

<!-- -->

-   Some model components (e.g., trip production models) are more amenable to model transfer than others (e.g., trip distribution).

<!-- -->

-   Rigorously demonstrating that transferability of a model is correct involves using a model from the estimation context to predict travel behavior in the application context and comparing the results to those from a model estimated directly from data in the application context. However, the literature provides a relatively small number of model transferability studies, and many of these are limited in scope.

<!-- -->

-   The transferability studies that have been done have shown mixed results, and they do not provide any conclusive guidelines for model transfer. This is true for both trip based and activity based models though there has been subsequent research into activity based modeling that provides more information.

<!-- -->

-   Model transfer may be enhanced when some data are available in the application context. Updating procedures that make use of the application context data can greatly improve model transferability.

<!-- -->

-   Updating procedures include Simple (Naïve) Transfer, Transfer Scaling, Bayesian Updating, Combined Transfer, and Joint Context Estimation. The methods that make the most use of information from the application context generally improve transferability, but besides requiring more information, they require more resources and expertise to implement.

References
----------

Rossi, T.F. and C.R. Bhat (2014). Guide for Travel Model Transfer. Cambridge Systematics, Inc., prepared for Federal Highway Administration. <http://www.fhwa.dot.gov/planning/tmip/publications/other_reports/travel_model_transfer/>

------------------------------------------------------------------------

