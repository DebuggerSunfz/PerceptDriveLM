#### Towards Robust Autonomous Driving: Conditional Multimodal Large Language Models for Fine-Grained Perception

------

This repository contains the code for the paper titled "Towards Robust Autonomous Driving: Conditional Multimodal Large Language Models for Fine-Grained Perception" which is submitted to ICRA2025.

#### Main Structure

![image-20241018144926875](C:\Users\孙先森\AppData\Roaming\Typora\typora-user-images\image-20241018144926875.png)

#### Main Results

![image-20241018144956841](C:\Users\孙先森\AppData\Roaming\Typora\typora-user-images\image-20241018144956841.png)

#### Quick Start

------

##### Install Packages

```
conda create -n percepdrivelm python=3.10
conda activate percepdrivelm
pip install -r requirements.txt
```

##### Data Preparation

Please refer to [dataset_prepare.md](https://github.com/PhoenixZ810/MG-LLaVA/blob/master/dataset_prepare.md).

##### Train model

- **Step 1**, Pretraining.

  ```
  bash script/train_pretrain.sh 
  ```

- **Step 2**, Fine-tuning.

  ```
  bash script/train_sft.sh
  ```

------



#### Acknowledgement

The project is built on top of the amazing multimodal large language model [LLaVA](https://github.com/haotian-liu/LLaVA). Thanks for these great work! 

