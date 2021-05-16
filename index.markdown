---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title:  Introduction
---

##  Welcome to the **hypnn** documentation page !

A neural network that generates weights for other neural networks is called a hypernet. The **hypnn** library allows training hypernets for different purposes such as: 
multimodal optimization, uncertrainty estimation in regression or classification tasks, transfer or one-shot learning, learning economical ensembles or a set models purposed for different datasets.


* Strong generalization of ensemble models


|               | MNIST         | Fashion-MNIST | CIFAR10  |  CIFAR100  |  KMNIST    |
| ------------- |:-------------:|:-------------:|:--------:|:----------:|:----------:|
| single        | 26            |       ?       |    ?     |     ?      |      ?     |
| hypnn         | 16            |       ?       |    ?     |     ?      |      ?     |




* Multimodal optimization. *The hypernets trained by our library are capable of finding multiple local minima.*

<p align="center">
 <table style="width:100%">
  <tr>
    <td><img alt="Data preprocessing" title="Data preprocessing" src="/assets/1.gif" width="650"></td>
    <td><img alt="Data preprocessing" title="Data preprocessing" src="/assets/3.gif" width="650"></td>
  </tr>
</table>
</p>




* Uncertainty estimation in regression tasks. *The ensembles created by the hypernet allows uncertainty estimation in regression tasks, 
that is how sure the network in its predictions especially when the new data is not similar to the training data.*


<p align="center">
 <table style="width:100%">
  <tr>
    <td><img alt="Data preprocessing" title="Data preprocessing" src="/assets/regression.png" width="width:100%"></td>
    <td><img alt="Data preprocessing" title="Data preprocessing" src="/assets/regression.png" width="width:100%"></td>
  </tr>
</table>
</p>


* Uncertainty estimation in classification tasks. *Similar to the regression tasks, the uncertainty tells how sure the network is when classyfying data.*


<p align="center">
 <table style="width:100%">
  <tr>
    <td><img alt="Data preprocessing" title="Data preprocessing" src="/assets/Figure_1.png" width="width:100%"></td>
    <td><img alt="Data preprocessing" title="Data preprocessing" src="/assets/Figure_2.png" width="width:100%"></td>
  </tr>
</table>
</p>


* Transfer learning.

<p align="center">
 <table style="width:100%">
  <tr>
    <td><img alt="Data preprocessing" title="Data preprocessing" src="/assets/blank.png" width="width:100%"></td>
    <td><img alt="Data preprocessing" title="Data preprocessing" src="/assets/blank.png" width="width:100%"></td>
  </tr>
</table>
</p>


* One-shot learning.


<p align="center">
 <table style="width:100%">
  <tr>
    <td><img alt="Data preprocessing" title="Data preprocessing" src="/assets/blank.png" width="width:100%"></td>
    <td><img alt="Data preprocessing" title="Data preprocessing" src="/assets/blank.png" width="width:100%"></td>
  </tr>
</table>
</p>


The input to the hypernet are the random vectors sampled from posterior distribution. 
In the hypnn, those are multimodal Gaussian distributions. 






