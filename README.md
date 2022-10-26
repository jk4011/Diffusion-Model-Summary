# Diffusion-Model-Summary


[**Understanding Diffusion Models: A Unified Perspective**](https://arxiv.org/abs/2208.11970)\
Aug 2022, Calvin Luo\
* ELBO, VAE, HVAE를 차근차근 설명하고 이것이 어떻게 diffusion model의 이론적인 배경이 되는지 설명함. 뒤에는 SDE based model과 guidance sampling을 간단히 소개함. 논문마다 수식이 다른데, 수식을 통합해서 깔끔하게 정리해둠. 증명 보고 싶을 때 이 논문 보면 좋음. 

[**DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps**]()\
Jun 2022\
[summary at notion](https://jh11.notion.site/DPM-Solver-A-Fast-ODE-Solver-for-Diffusion-Probabilistic-Model-Sampling-in-Around-10-Steps-228fc29f3119448c98fb7fc78448de97)\
* 이전 Diffusion model의 generation에는 1,000 step의 model inference가 필요했는데, diffusion model에 특화된 high order ode sampling방법을 제시해서 20 step에도 좋은 퀄리티의 이미지를 생성해냄. 

