# machine-learning-for-networking-paper-list

![](https://img.shields.io/github/last-commit/MoweiWang/machine-learning-for-networking-paper-list?color=green) ![](https://img.shields.io/badge/PaperNumber-7-brightgreen)

Must-read papers on data-driven networking research that primarily apply machine learning techniques to the computer networking domain. The papers are mostly selected from major venues such as Sigcomm, NSDI, Mobicom, IMC, CoNEXT,INFOCOM, Hotnets, OSDI, SOSP, etc. Preprint papers with interesting topics or insights are also included here. Watch this repository for the latest updates!

<!-- ## introduction -->

<!-- This is a paper list about data-driven networks. Different from traditional fine-tuning that uses an explicit classifier, prompt-based tuning directly uses the pre-trained models to conduct the pre-training tasks for classification or regression. -->

<!-- This is a paper list about data-driven networks. -->
<!-- Unlike conventional handcrafted networking system, . -->
<!-- We categorize the recent advances according to its main application solution. -->
We use the following badges to highlight features of the paper.


![](https://img.shields.io/badge/Pensieve-blue) The abbreviation of the work.

![](https://img.shields.io/badge/GNN-brown) The main data-driven technique used in the work.

![](https://img.shields.io/badge/Congestion_control-green) The main explored networking problem of the work.

<!-- ![](https://img.shields.io/badge/Analysis-green) The main explored property of prompt learning methods in the work. -->


- [machine-learning-for-networking-paper-list](#machine-learning-for-networking-paper-list)
  - [Overview](#overview)
  - [Control and scheduling](#control-and-scheduling)
    - [Video streaming](#video-streaming)
    - [Congestion control](#congestion-control)
    - [Scheduling](#scheduling)
    - [Routing, traffic engineering and traffic optimization](#routing-traffic-engineering-and-traffic-optimization)
    - [Job scheduling](#job-scheduling)
    - [Multi-path scheduling](#multi-path-scheduling)
  - [Configuration optimization](#configuration-optimization)
    - [Packet classification](#packet-classification)
    - [Topology adaptation in data center networks](#topology-adaptation-in-data-center-networks)
  - [Performance evaluation](#performance-evaluation)
    - [Network modeling](#network-modeling)
    - [Measurement](#measurement)
    - [configuration extrapolation](#configuration-extrapolation)
  - [Self-driving Networks](#self-driving-networks)
  - [Conceptual discussion and experimental study](#conceptual-discussion-and-experimental-study)
    - [Interpretability](#interpretability)
    - [Generalization](#generalization)
    - [Robustness](#robustness)
    - [Verification](#verification)
  - [Others](#others)
    - [Platform](#platform)
    - [Experience](#experience)


## Overview
This section contains the papers that overview the general trends in recent data-driven networking.

1. **Machine learning for networking: Workflow, advances and opportunities.** IEEE Network, 2018.

   *Mowei Wang, Yong Cui, Xin Wang, Shihan Xiao, Junchen Jiang.* [[pdf](https://ieeexplore.ieee.org/abstract/document/8121867)]

2. **Machine Learning for Computer Systems and Networking: A Survey.** ACM Computing Surveys (CSUR), 2022.

   *Marios Evangelos Kanakis, Ramin Khalili, Lin Wang.* [[pdf](https://linwang.info/docs/papers/csur22-ml4sysnet.pdf)]




## Control and scheduling
Efficient **resource management** and network adaption are the keys to improving network system performance. However, it is challenging to solve these problems with a rule-based heuristic algorithm due to the complexity of diverse system environments, noisy inputs and difficulty in optimizing the tail performance. Specifically, arbitrary parameter assignments based on experiences and action taken following predetermined rules often result in a scheduling algorithm that is understood by people but far from optimal.
### Video streaming

1. **Neural adaptive video streaming with pensieve.** ACM SIGCOMM, 2017. ![](https://img.shields.io/badge/Pensieve-blue) ![](https://img.shields.io/badge/DRL/A3C-brown) ![](https://img.shields.io/badge/Congestion_control-green)

   *Hongzi Mao, Ravi Netravali, Mohammad Alizadeh.* [[pdf](https://dl.acm.org/authorize.cfm?key=N33908)] [[slides](https://conferences.sigcomm.org/sigcomm/2017/files/program/ts-5-2-pensieve.pptx)] [[code](https://github.com/hongzimao/pensieve)]

2. CS2P
3. Via
4. pytheas
5. CFA

### Congestion control


1. [Tcp ex machina: Computer-generated congestion control.](https://conferences.sigcomm.org/sigcomm/2013/papers/sigcomm/p123.pdf "Remy") (SIGCOMM'13) [[slides]](https://conferences.sigcomm.org/sigcomm/2013/slides/sigcomm/12.pdf "Remy slides")[[code]](https://github.com/tcpexmachina/remy "Remy code")[[website]](http://web.mit.edu/remy/ "Remy website")
2. [PCC: Re-architecting Congestion Control for Consistent High Performance.](https://www.usenix.org/system/files/conference/nsdi15/nsdi15-paper-dong.pdf "PCC") (NSDI'15) [[slides]](https://www.usenix.org/sites/default/files/conference/protected-files/nsdi15_slides_dong.pdf "PCC slides")[[code]](https://github.com/PCCproject "PCC code")[[website]](https://modong.github.io/pcc-page/ "PCC website")

3. [PCC Vivace: Online-Learning Congestion Control.](https://www.usenix.org/system/files/conference/nsdi18/nsdi18-dong.pdf "PCC Vivace") (NSDI'18) [[slides]](https://www.usenix.org/sites/default/files/conference/protected-files/nsdi18_slides_dong.pdf "PCC Vivace slides")[[code]](https://github.com/PCCproject/PCC-Kernel "PCC Vivace code")
4. indigo
5. ICML
6. NIPS
7. Puffer

8. **Machine learning for internet congestion control: Techniques and challenges.** IEEE Internet Computing (IC), 2019. ![](https://img.shields.io/badge/Survey-blue) ![](https://img.shields.io/badge/Congestion_control-green)

   *Lei Zhang, Yong Cui, Mowei Wang, Zhenjie Yang, Yong Jiang.* [[pdf](https://ieeexplore.ieee.org/abstract/document/8935577)]


### Scheduling

### Routing, traffic engineering and traffic optimization
1. Learn to route, hotnets
2. experience driven, infocom
3. Auto, sigcomm

### Job scheduling
1. Decima
2. DeepRM

### Multi-path scheduling
1. infocom
2. JSAC
3. JSAC

## Configuration optimization

### Packet classification
1. NeuralCuts


### Topology adaptation in data center networks
1. xWeaver

## Performance evaluation

### Network modeling
1. unveiling
2. deepQ, sigcomm netai workshop

### Measurement
1. sketchlearn
2. conext, gan

### configuration extrapolation
1. NSDI
2. [2022][NSDI] Configanator- A Data-driven Approach to Improving CDN Performance

## Self-driving Networks

## Conceptual discussion and experimental study

### Interpretability
1. apnet
2. sigcomm neiai workshop

### Generalization

### Robustness

### Verification

## Others

### Platform
1. pantheons
2. Park

### Experience
1. ICML workshop pensieve in Facebook

<!-- # Conference and Journal -->