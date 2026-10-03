# -atom01_train训练框架基于IsaacLab 2.3.1、IsaacSim 5.1.0以及rslrl 3.2.0构建，提供了类似于legged_gym的direct强化学习环境以及IsaacLab原生的manager_based强化学习环境。该框架支持在MuJoCo中进行sim2sim迁移，并支持IsaacLab地形导出功能。
上述任务均在atom01平台上完成了sim2sim与sim2real验证。
参考开源地址：https://github.com/Roboparty/roboparty_train



<img width="1314" height="654" alt="image" src="https://github.com/user-attachments/assets/a9350ce9-0b9c-4976-aa7f-c4540dab6df9" />



平地盲走


cd /workspace/IsaacLab
./isaaclab.sh -p /workspace/robotor/roboparty_train-main/robolab/scripts/rsl_rl/play.py \
  --task=RPO-Flat --num_envs=1 \
  --checkpoint /workspace/IsaacLab/logs/rsl_rl/rpo_flat/2026-09-16_13-36-32/model_9000.pt


