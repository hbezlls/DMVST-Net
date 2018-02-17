# Deep Multi-View Spatial-Temporal Network for Taxi Demand Prediction

This is a TensorFlow implementation of DMVST-Net in the following paper: \
Huaxiu Yao, Fei Wu, Jintao Ke, Xianfeng Tang, Yitian Jia, Siyu Lu, Pinghua Gong, Jieping Ye, Zhenhui Li [Deep Multi-View Spatial-Temporal Network for Taxi Demand Prediction](https://faculty.ist.psu.edu/jessieli/Publications/2018-AAAI-taxi-demand.pdf).

## Requirements
- keras>=2.0.8
- tensorflow>=1.3.0
- python 2.7 (Recommend Anaconda)

## Data
This work is an intern work in Didi Chuxing. Due to the privacy policy, we do not provide the raw data. Maybe you can apply a similar type of data in https://outreach.didichuxing.com/appEn-vue/Personal. 

## Input
As shown in the framework, there are three inputs:
- local demand image
- external features
- semantic network

More details will be add soon.

If you find the code is userful, please cite our paper
```
@inproceedings{yao2018deep,
  title={Deep Multi-View Spatial-Temporal Network for Taxi Demand Prediction},
  author={Yao, Huaxiu and Wu, Fei and Ke, Jintao and Tang, Xianfeng and Jia, Yitian and Lu, Siyu and Gong, Pinghua and Ye, Jieping and Li Zhenhui},
  booktitle={The Thirty-Second AAAI Conference on Artificial Intelligence},
  year={2018}
}
```
