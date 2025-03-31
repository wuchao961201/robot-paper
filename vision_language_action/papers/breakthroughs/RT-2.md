# RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control

## 基本信息
- **标题**: RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control
- **作者**: Anthony Brohan, Noah Brown, Justice Carbajal等
- **发表时间**: 2023
- **会议/期刊**: Conference on Robot Learning (CoRL) 2023
- **DOI/链接**: https://openreview.net/forum?id=XMQgwiJ7KSX
- **代码**: https://robotics-transformer2.github.io/

## 核心贡献
RT-2提出了vision-language-action模型的概念，将大型视觉-语言模型直接用于端到端机器人控制，通过将动作表示为文本令牌，将自然语言响应和机器人动作统一到相同格式。

## 关键技术点
1. 将机器人动作表示为文本字符串，无缝集成到视觉-语言模型中
2. 在机器人轨迹数据和互联网规模视觉-语言任务上共同微调现有VLM
3. 实现了基于链式思维的推理，能够执行多阶段语义推理

## 实验结果
RT-2在6000多个评估试验中显示出显著的性能提升：
- 对新对象的泛化能力显著提高(约3倍)
- 能够解释机器人训练数据中不存在的命令
- 能够执行基本推理以响应用户命令（如拾取最小/最大物体）

## 影响与应用
作为第一个真正的视觉-语言-动作模型，RT-2开创了将互联网规模预训练视觉-语言模型用于机器人控制的新范式，极大推动了具身AI的发展。

## 被引情况
- Google Scholar被引量：300+ (2024年6月)
- 近6个月增长曲线：呈指数增长趋势
- 相关专利数：5+ 