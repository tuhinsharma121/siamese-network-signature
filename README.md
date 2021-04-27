# siamese-network-signature

Writer independent offline signature verification in banks using few shot learning

## Abstract:
Offline signature verification is one of the most critical tasks in traditional banking and financial industries. The unique challenge is to detect subtle but crucial differences between genuine and forged signatures. This verification task is even more challenging in writer independent scenarios, which is undeniably fiscal to most of the use cases. 

## Description:
Signature is arguably the most popular and widely accepted biometric hallmarks used in the Banking sector for verifying documents, bank checks, forms etc. That is why signature verification is such a critical task and a simple bug in the system can cause severe repercussions. There are two popular ways to do it – Online and Offline. In online process, signature needs to be captured on electronic writing pad and several other types of information like writing speed, pressure etc. are captured. In offline process signature is captured by scanner. While online process performs better than offline process, it comes with a cost due to special hardware requirements. Additionally there are many cases where offline process is the only option such as check transaction and document verification. Offline signature verification can be of two types -  writer dependent and writer independent. a writer dependent system needs to be updated with every new signer and for a bank, where every day new consumers can open their account this incurs huge cost. That is why the writer independent scenario is preferable over writer dependent approaches where a generic model is built to classify the signatures as genuine or forged based on the learnt discrepancies between a genuine and a forged signature. 
In case of standard image classification task, the input image is fed into a series of layers, and finally at the output we generate a probability distribution over all the classes. But it requires a large number of images. In offline signature verification scenario, we neither have enough signature for each signer and the total number signers is huge as well as dynamically changing. Thus, the cost of data collection and periodical retraining is too high. On the other hand, in a few shot image classification, we require only a few signatures for each signer, hence the name Few Shot. 

## Conferences:-

[1] [GIDS 2021](https://wurreka.com/ict/virtual-conference/gids-2021/session/signature-verification-in-banks-using-few-shot-learning)
