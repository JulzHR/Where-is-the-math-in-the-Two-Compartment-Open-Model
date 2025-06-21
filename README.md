# Where is the math in the Two Compartment Open Model? by Julio Reyes

Welcome! This repository presents my mathematical modeling project exploring how pharmacokinetic models, specifically the **two compartment open model**, describe drug movement through the body.

**Note:** I will focus **exclusively on the theoretical background and mathematical derivation** of the equations that govern the model. It does not include experimental or clinical data, but instead highlights the math behind how we understand drug distribution in the body. :)

---

## Personal Information

Hi! I'm Julio Hernández Reyes, a Chemistry major student with a minor in Mathematics. I'm passionate  

## Introduction

After taking the course Introduction to Pharmacology, I got interested in how pharmacokinetics work. Nonetheless, due to time constraints and because it is an introductory course, the graphs of the model were only shown without a true understanding of the math behind them. Now that I have the opportunity, I would like to see the how math describe the biological or chemical processes that are happening in drug distribution, how the equation of the model is obtained and how are the pharmacokinetic parameters obtained.

Here is the link to the [Motivational Video](https://www.youtube.com/watch?v=WnimfMnryds)

Here is the link to the [Video Presenting Classmates]()

## Hands On

As stated in the [Video Presenting Classmates](), the basic idea of the model is to keep track of the amount of drug that goes inside and ouside the compartments as time passes. This behavior is shown in the following equation:

$$
\frac{dC_n}{dt}=Input\space rate\space of\space drug-Output\space rate\space of\space drug
$$

where $$C_n$$ refers to the compartment that is being described, either the central/plasma compartment or the peripheral/tissue compartment.

### Variety of Models

Depending on the route of administration of the drug (oral, injection, infusion, etc.) and the excretion of the drug (urine or sweat mainly), the representation of the model may vary. For instance, oral administration will have an extra constant when compared to IV. Some models mention that excretion only occurs in the central compartment, while others affirm that excretion happens in the tissue compartment or  even a combination of both compartments. So, as you can see, this model is versatile since it allows to take these factors (administration and excretion) into consideration.




### Two Compartment Open Model for IV Bolus Dose

For the IV bolus dose, the visualization of the model looks as follows:

![](IV_2CM.png)

Based on that, the equations that model the amount of drug present in each compartment are given by the following differential equations:

$$
\frac{dC_p}{dt}=k_{21}C_t-(k_{10}+k_{12})C_p
$$

$$
\frac{dC_t}{dt}=k_{12}C_p-k_{21}C_t
$$

where $$C_p$$ is the plasma compartment and $$C_t$$ is the tissue compartment.

### Mathematical derivation



## Summary and Conclusions

## References
