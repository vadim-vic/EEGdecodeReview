# EEGdecodeReview
EEG and ECoG signal decoding review

The brain signal decoding models give a decent quality of limb movement classification in 2023. The base model is described in the [HTNet](https://github.com/BruntonUWBio/HTNet_generalized_decoding) by Brunton 2021, and its precedent [EEGNet](https://github.com/vadim-vic/arl-eegmodels). The plan of the works for this overvier is the fillowing:
# Search for the newest updates of HTNet and EEGNet
# Develop these models towards the heterogenous data like [Deliberate's](https://www.deliberate.ai/)
# Move problem statement from classification to decoding, assuming the phase space both in the source and the target spaces
# Develop the (State-Space Models D4](https://arxiv.org/pdf/2205.10947.pdf) by  Yousefi and Rezaei 2022 to 
## use Bayesian approach and, preferrable, diffusion probabilistic models with normalizing flows
## use Neural ODE networks with continous layers to boost the approximation quality in the framefork of SSM [Hippo](https://arxiv.org/abs/2206.12037) 2022
## since the usage of Riemanian spaces and [PyRiemann](https://github.com/pyRiemann/pyRiemann) models by Barachant 2022 have a great success in the EEG signal processing, consider works on the brain fuctional groups 

