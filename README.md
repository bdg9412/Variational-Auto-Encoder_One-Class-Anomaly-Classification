# Variational-Auto-Encoder_One-Class-Anomaly-Classification
using VAE for ECG Classification  
# **실험개요**  
1) Variational Auto Encoder 구현  
2) 정상 데이터만을 이용하여 학습  
3) 정상 데이터와 비정상 데이터에 대한 재생성 데이터간 유사도 측정  
4) 유사도를 기반으로 비정상/정상 구분  

오토 인코더의 구조에서 중간에 latent vector를 구하는 과정에 변화를 준 VAE를 구현하였다.  
평균과 분산을 sampling 함수의 입력으로 사용하여 latent vector를 구하였다.  

Ref  
1. A. Géron, Hands-On Machine Learning with Scikit-Learn and TensorFlow, 한빛미디어, Seoul, 2018  
2. https://github.com/bdg9412/handson-ml2  
