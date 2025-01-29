# R1-CDL
Continuous Distillation Learning持续蒸馏学习，在类DeepSeek-R1知识蒸馏强化的基础上，意图小模型能够以极低成本且简易的方式复制繁殖目标模型的强壮思维，在获取高价值蒸馏数据的同时，让小模型继承目标模型的强推理能力。以此期待，成为AGI与硅基生命演化的一种新实现范式。

无蒸馏

![无蒸馏](NoMethod.png)

R1-CDL持续蒸馏学习

![持续蒸馏学习](Method.png)

要点说明：

#1. 无任务时，抽取的数据集，经常是一道题或几道题，这种数据集可以是慢思考、长CoT、知识蒸馏强化等Resoning推理数据集，如 https://huggingface.co/datasets/bespokelabs/Bespoke-Stratos-17k
#2. 判断
