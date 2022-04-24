# Sharpness-Aware Private Aggregation of Teacher Ensembles (Sharp-PATE)
##### Course Project: [ECSE-6962 Trustworthy Machine Learning (Spring-2022)](https://piazza.com/class/ky4olbgarmr2du)
##### Instructors: [Prof. Ali Tajer](https://www.isg-rpi.com/) and [Prof. Alex Gittens](https://www.cs.rpi.edu/~gittea/)
###### By: [Momin Abbas](https://mominabbas.github.io/)



Language: Python

API: Pytorch

# Instructions
The `pytorch/data` folder contains the datasets used for training (`MNIST`,`CIFAR-10`,`CIFAR-100`). Results of our experiments are located in the `pytorch/results` folder. 
To reproduce all of the experiments, simply download all the files in the pytorch folder and run `pytorch/main.py` as ``` python main.py ```.

For `MNIST`, run:  

```bash
python sharp_pate_mnist.py
```

# Reference
```
@article{papernot2016semi,
  title={Semi-supervised knowledge transfer for deep learning from private training data},
  author={Papernot, Nicolas and Abadi, Mart{\'\i}n and Erlingsson, Ulfar and Goodfellow, Ian and Talwar, Kunal},
  journal={arXiv preprint arXiv:1610.05755},
  year={2016}
}

@article{foret2020sharpness,
  title={Sharpness-aware minimization for efficiently improving generalization},
  author={Foret, Pierre and Kleiner, Ariel and Mobahi, Hossein and Neyshabur, Behnam},
  journal={arXiv preprint arXiv:2010.01412},
  year={2020}
}

```

