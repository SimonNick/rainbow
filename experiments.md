# CartPole #1

1-step full Rainbow

```
python main.py \
--max-frames 10000 \
--evaluation_interval 500 \
--eps_decay 3000 \
--learning-start 1000 \
--update-target 100 \
--env CartPole-v0 \
--seed 0 \
--double \
--dueling \
--prioritized-replay \
--c51 \
--noisy \
--multi-step 1 \
--save-model "cartpole"
```

# CartPole #2

3-step full Rainbow

```
python main.py \
--max-frames 10000 \
--evaluation_interval 500 \
--eps_decay 3000 \
--learning-start 1000 \
--update-target 100 \
--env CartPole-v0 \
--seed 0 \
--double \
--dueling \
--prioritized-replay \
--c51 \
--noisy \
--multi-step 3 \
--save-model "cartpole"
```

# LunarLander #3

3-step dueling network

```
python main.py \
--max-frames 60000 \
--batch-size 1024 \
--evaluation_interval 5000 \
--eps_decay 20000 \
--learning-start 10000 \
--update-target 1000 \
--env LunarLander-v2 \
--seed 0 \
--dueling \
--multi-step 3 \
--save-model "lunarlander" 
```

# LunarLander #4

1-step dueling network

```
python main.py \
--max-frames 100000 \
--batch-size 1024 \
--evaluation_interval 5000 \
--eps_decay 20000 \
--learning-start 10000 \
--update-target 1000 \
--env LunarLander-v2 \
--seed 0 \
--dueling \
--save-model "lunarlander"
```
