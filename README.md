# Quazi Mostahid Labib

**Electrical Engineering & Automation undergraduate at Tsinghua University | Class of 2029**

I build software at the intersection of **ML systems, software infrastructure, and robotics**, with a focus on efficient inference, reproducible evaluation, and autonomous systems. I care about implementation, testing, and measurable results.

## Selected engineering projects

| Project | Engineering highlights |
| --- | --- |
| **[VORTEX](https://github.com/LabibBD/vortex-inference)** | C++17/CUDA neural-network inference runtime with GPU memory reuse, graph execution, transformer operators, ONNX conversion and profiling. Passed 30/30 C++/CUDA tests on RTX 5060 Ti; measured 5.1× lower median latency than PyTorch CUDA eager on a defined small FP32 transformer workload ([benchmark conditions and limitations](https://github.com/LabibBD/vortex-inference/blob/main/docs/rtx5060ti_lab_benchmark_2026-11-21.md)). |
| **[FORGE-CI](https://github.com/LabibBD/forge-ci)** | Python CLI and CI toolkit for reproducible robot-learning evaluation, regression gating, failure analysis, six-dimensional disturbance testing, and automated HTML reporting. Includes a reproducible one-command regression demo and GitHub Actions automation. |
| **[ARES](https://github.com/LabibBD/ARES)** | ROS 2 autonomous exploration system integrating Nav2, LiDAR-based SLAM, risk-aware frontier selection, and mission evaluation in simulation. A documented single mission achieved 74.37% map coverage and 7/7 successful navigation goals. |

## Open-source contributions

**[Hugging Face LeRobot](https://github.com/huggingface/lerobot)**

- [PR #4224](https://github.com/huggingface/lerobot/pull/4224): proposed deterministic LIBERO initial-state allocation using episode indices, with regression tests for reset and termination behavior.
- [PR #5501](https://github.com/huggingface/lerobot/pull/5501): proposed per-episode initial-state metrics for reproducible, paired evaluation comparisons; 80 relevant local tests passed after rebasing.
- [Review of PR #5447](https://github.com/huggingface/lerobot/pull/5447#pullrequestreview-6046693884): independently ran evaluator and vector-environment tests (30 passed, 2 skipped) and reproduced an edge case where a missing simulator metric was indistinguishable from a genuine zero.

Both authored PRs are open upstream as of November 25, 2026.

## Research and technical interests

- Multi-agent reinforcement learning and evaluation of intelligent systems.
- LiDAR-based terrain traversability and autonomous path planning for off-road robotics.
- GPU computing, ML systems, backend and infrastructure engineering.

## Technical toolkit

- **Languages:** C++, Python, CUDA
- **ML and systems:** PyTorch, ONNX, GPU inference, profiling, numerical validation and benchmarking
- **Robotics:** ROS 2, Gazebo, MuJoCo, Nav2, SLAM
- **Software engineering:** Linux, Git, GitHub Actions, automated testing, CI and reproducible experiments

## Opportunities and contact

Open to internships, undergraduate research, and engineering collaborations in ML systems, software infrastructure, and robotics/autonomy.

- **Email:** [qmostahid@gmail.com](mailto:qmostahid@gmail.com)
- **LinkedIn:** [Quazi Mostahid Labib](https://www.linkedin.com/in/quazi-mostahid-labib-14ba7b272/)
