# Autonomous Driving System
## Road Following & Collision Avoidance
A technology that follow the road and avoid collision on the road 
using Jetson Nano based RC car.



## Contens
- Description
- Environment
- Reference

## Description
자율 주행 차량에서 사용하는 기능인 road following 및 collision avoidance 기능을 설계하는 프로젝트이다.
  
  
이 프로젝트는 edge device인 Jetson Nano 기반의 RC카를 사용하여 진행했다.
  
  
해당 프로젝트에서 구현한 주요 기능은 road following과 collision avoidance이다.
  
  
두 기능은 ResNet을 이용하여 정상 루트인지 아닌지 혹은 장애물인지 아닌지를 판단하고, 이를 기반으로 길을 따라가거나 장애물을 회피하는 기능을 수행한다.
  
### Hardward
- Jetson Nano Developer Kit
- Jetbot Standard

### Network
- ResNet


## Enviroment
> Python<br>PyTorch

