
Training and Inference

https://learn.unity.com/tutorial/training-and-inference

学習開始:

```
$ mlagents-learn config/trainer_config.yaml --curriculum config/curricula/penguin/ --run-id penguin_01 --train
```

グラフで見る:

```
$ tensorboard --logdir=summaries --port=6006
```
