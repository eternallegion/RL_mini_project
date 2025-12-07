# RL_mini_project
RL수업의 미니 프로젝트입니다.

문제번호
0. oh_jama
1. Ancient_Kings

에이전트 타입 -> 선택가능
dqn , double_dqn , rainforce_base , a2c , all

train mode


python train_rl.py --puzzle 1 --algorithm all --episodes 10000
======================================================================


elvaluation mode

# Oh Jama 플레이 시각화 reinforce_baseline
(디폴트가 reinforce_baseline으로 되어 있습니다. 그래서 다른 알고리즘의 경우에는 뒤에 --algorithm 알고리즘 명을 써야합니다.)
python play_oh_jama.py --model results/best_model_Oh_Jama_20251206_162754.pth

# Ancient Kings 플레이 시각화 a2c
python play_ancient_kings.py --model results/best_model_Ancient_Kings_20251206_034924.pth --algorithm a2c


만일 실행이 잘 안 될경우, 백업파일에 있는 걸 쓰세요
