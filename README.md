# Dissertation Project

## CleanRL results
The results mentioned in the github repository (cleanrl)[https://github.com/vwxyzjn/cleanrl] and the (documentation)[https://docs.cleanrl.dev/rl-algorithms/ppo/].

The tasks selected were continuous actions tasks in Mujoco environment (executing ppo_continuous_actions.py file).
Environments executed and results replicated: HalfCheetah-v4, Hopper-v4, Humanoid-v4, Pusher-v4, Walker2d-v4

## Results 

Results mentioned on CleanRL documentation

|Environment|Mean Episodic Return + Std. deviation|
|---|---|
|HalfCheetah-v4|	1442.64 ± 46.03|
|Walker2d-v4|	2287.95 ± 571.78|
|Hopper-v4|	2382.86 ± 271.74|
|InvertedPendulum-v4|	963.09 ± 22.20|
|Humanoid-v4|	716.11 ± 49.08|
|Pusher-v4|	-40.38 ± 7.15|

Results generated after executing ppo_continuous_actions.py file in CleanRL Github (10 different seeds for each environment)

|Environment|Mean Episodic Return + Std. deviation|Comparison with documentation values|
|---|---|---|
|HalfCheetah-v4| 1868.4 ± 622.7|Better|
|Walker2d-v4| 3650.7 ± 1085.4|Better|
|Hopper-v4| 2301.3 ± 892.4|Close|
|Humanoid-v4| 783.4 ± 169.6|Better|
|Pusher-v4| -49.4 ± 15.6|Close|


Different individual seed runs plot plus plot with mean + std. deviation generated.
