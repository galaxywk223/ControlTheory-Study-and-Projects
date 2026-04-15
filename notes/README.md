# 学习笔记

`notes/` 是仓库的主阅读层。各章节统一组织问题背景、核心结论、数值结果和实验入口。根目录 [README](../README.md) 提供总览，后续章节按下列顺序组织。

## 章节顺序

| 章节 | 主题 | 内容定位 | 实验入口 |
| --- | --- | --- | --- |
| [01_线性时不变系统稳定性](./01_线性时不变系统稳定性.md) | LTI 稳定性 | 连续时间 LTI 稳定性入门 | [01 稳定性实验](../experiments/foundations/01_lti_stability/README.md) |
| [02_线性时不变系统控制](./02_线性时不变系统控制.md) | 状态反馈与输出反馈 | 控制器设计条件与 LMI 综合 | [02 控制实验](../experiments/foundations/02_lti_control/README.md) |
| [03_线性时不变系统周期采样控制与稳定性分析](./03_线性时不变系统周期采样控制与稳定性分析.md) | 周期采样控制 | 采样保持与时滞结构分析 | [03 采样控制实验](../experiments/foundations/03_periodic_sampling_control/README.md) |
| [04_鲁棒控制](./04_鲁棒控制.md) | 区间不确定系统与鲁棒性能 | 不确定模型与鲁棒性能 | [04 鲁棒控制实验](../experiments/robust_control/04_robust_control/README.md) |
| [05_非线性时滞神经网络稳定性](./05_非线性时滞神经网络稳定性.md) | 非线性与时滞稳定性 | 非线性时滞稳定性分析 | [05 时滞神经网络实验](../experiments/nonlinear_and_delay/05_delay_neural_network_stability/README.md) |
| [06_混沌时滞神经网络同步与图像加密](./06_混沌时滞神经网络同步与图像加密.md) | 混沌同步与图像加密 | 混沌同步与图像加密应用 | [06 同步与加密实验](../experiments/nonlinear_and_delay/06_chaotic_sync_and_image_encryption/README.md) |

## 与实验对应

| 实验目录 | 对应章节 | 说明 |
| --- | --- | --- |
| [experiments/foundations/01_lti_stability](../experiments/foundations/01_lti_stability/README.md) | `01` | 特征值判据、Lyapunov 方程和二维相图 |
| [experiments/foundations/02_lti_control](../experiments/foundations/02_lti_control/README.md) | `02` | 开环、状态反馈和输出反馈响应对比 |
| [experiments/foundations/03_periodic_sampling_control](../experiments/foundations/03_periodic_sampling_control/README.md) | `03` | 采样状态、连续状态和零阶保持输入 |
| [experiments/robust_control/04_robust_control](../experiments/robust_control/04_robust_control/README.md) | `04` | 区间不确定系统的鲁棒稳定与性能估计 |
| [experiments/nonlinear_and_delay/05_delay_neural_network_stability](../experiments/nonlinear_and_delay/05_delay_neural_network_stability/README.md) | `05` | LMI 裕度、相图和收敛时间扫描 |
| [experiments/nonlinear_and_delay/06_chaotic_sync_and_image_encryption](../experiments/nonlinear_and_delay/06_chaotic_sync_and_image_encryption/README.md) | `06` | 混沌同步误差、图像加密和统计分析 |
