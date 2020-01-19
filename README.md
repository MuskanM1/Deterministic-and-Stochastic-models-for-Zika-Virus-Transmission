# Deterministic And Stochastic models for Zika Virus Transmission

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Results](#Results)
* [Conclusion](#Conclusion)
* [Reference](#Reference)

## General info
Transmission of Zika virus is the cause for one of the most widespread mosquito-borne diseases. Aedes-aegypti mosquito is the major contributor for the spread among the Aedes-type mosquitos.  We consider a sample space of a population of healthy humans. In this case, there is no disease and hence no outbreak of any infectious disease since everyone is healthy. Consider a situation where a small subset of the population is infected by a virus. Now, the rest of the population comes under the category of "susceptible" since they can catch the disease from the infected person/s. One after other susceptible humans become infected humans at a rate. We assume that once the disease has prevailed in a body, it cannot affect it again because the person has either become immune to it (chickenpox) or has died from it. In both cases, the person gets removed from the sample space of susceptible and infected humans. Everyone will either recover or die from the disease once they have caught it, and thus, it will end the pandemic in a definite time depending on the rate of spreading. There may be people who don't get sick at all. To study this we study the dynamical system to observe how state variables change with time. We have different rates of change and increments for different variables.

## Technologies
Project is created with:
* Software: MATLAB 

## Results

![Alt Text](https://github.com/MuskanM1/Deterministic-and-Stochastic-models-for-Zika-Virus-Transmission/blob/master/docs/screenshots/1.JPG)

![Alt Text](https://github.com/MuskanM1/Deterministic-and-Stochastic-models-for-Zika-Virus-Transmission/blob/master/docs/screenshots/2.JPG)

![Alt Text](https://github.com/MuskanM1/Deterministic-and-Stochastic-models-for-Zika-Virus-Transmission/blob/master/docs/screenshots/3.JPG)

![Alt Text](https://github.com/MuskanM1/Deterministic-and-Stochastic-models-for-Zika-Virus-Transmission/blob/master/docs/screenshots/4.JPG)

![Alt Text](https://github.com/MuskanM1/Deterministic-and-Stochastic-models-for-Zika-Virus-Transmission/blob/master/docs/screenshots/5.JPG)

![Alt Text](https://github.com/MuskanM1/Deterministic-and-Stochastic-models-for-Zika-Virus-Transmission/blob/master/docs/screenshots/6.JPG)

![Alt Text](https://github.com/MuskanM1/Deterministic-and-Stochastic-models-for-Zika-Virus-Transmission/blob/master/docs/screenshots/8.JPG)

## Conclusion

Three different approaches have been used namely, the deterministic model and 2 stochastic models, CTMC(Continuous Time Markov Chain) and  DTMC(Discrete Time Markov Chain). The threshold obtained from the deterministic model is synonymous, that is, ⍴(M) <1(=1,>1) when R​O ​<1(=1,>1). The probability of disease extinction can be derived using branching process approximation of the non-linear CTMC model near the disease-free equilibrium.  Our analytical and numerical results showed that both deterministic and stochastic models predict disease extinction when R​O​<1. However, the predictions by these models are different when R​O​>1. In this case, deterministic model predicts with certainty disease outbreak while the stochastic model has a probability of disease extinction at the beginning of an infection. Hence, with stochastic models, it is possible to attain a disease-free equilibrium even when R​O​>1. Also, we noticed that initial conditions do not affect the deterministic threshold while the stochastic thresholds are affected. Thus, the dynamics of the stochastic model are highly dependent on the initial conditions and should not be ignored.The points q1,q2,q3 are the parameters for determining the probability of extinction when R​O​>1, or when R​O​ for stochastic and deterministic does not match the conclusion.  

## Reference
[Deterministic and stochastic CTMC models from Zika disease transmission](https://www.researchgate.net/publication/323608978_Deterministic_and_stochastic_CTMC_models_from_Zika_disease_transmission)
 
