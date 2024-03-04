# 刘威

## 教育经历

- <div style="display: flex; justify-content: space-between;">
    <div> 硕士（推免生）    <strong>华中科技大学</strong></div>
    <div>2022.09 ~ 2025.06</div>
</div>

- 网络空间安全学院&emsp;&emsp;&emsp;网络与信息安全&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;加权成绩 88.35
- <div style="display: flex; justify-content: space-between;">
    <div>本科         <strong>华中科技大学</strong></div>
    <div>2018.09 ~ 2022.06</div>

</div>

- 化学与化工学院&emsp;&emsp;&emsp;&emsp;化学（拔尖）&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;加权成绩 87.98
- 2022年&emsp;&emsp;华中科技大学“学业奖学金”一等奖
- 2023年&emsp;&emsp;华中科技大学“学业奖学金”一等奖、华中科技大学“知行奖学金”、华中科技大学“三好研究生”


## 比赛经历
**竞赛&emsp;&emsp;ATEC 2023 大模型应用与安全**
**赛道二: 大模型的工具学习 第三名**
- 通过LoRA 微调大模型ChatGLM2-6b，让ChatGLM 从多轮对话中学会提取调用工具的必要信息。
- 使用Prompt Engineering 优化输入提示词模板，减少模型对Instruction 中的情景依赖，让模型更深入理解用户
Query，提升泛化性。
**赛道四: 网络安全大模型 第二名**
该赛题需要微调大模型ChatGLM2-6b，要求大模型能够具有在多种任务下的通用检测能力，同时要求保证大模
型不遗忘原有的知识。
- 借助ChatGPT，实现对数据流量包的特征提取函数，将十六进制文本转化为大模型能够理解的通用语言。
- 针对不同任务，在同一prompt 模板上设计优化，最后在所有任务数据采样后输入大模型进行LoRA 微调。

**竞赛&emsp;&emsp;通义千问AI挑战赛 Code Qwen能力算法赛道**
*比赛内容：通过微调LLM来提升大语言模型Qwen-1.8B的理解代码能力。*
- 收集代码生成数据集，并进行数据预处理，调整Prompt模板
- 使用accelerate部署单机多卡，进行SFT微调Qwen-1.8B；在本地docker镜像上，使用并行脚本在HumanEvalPack 和 MBPP任务上进行评测

**竞赛&emsp;&emsp;第六届“强网”拟态防御国际精英挑战  白盒安全测试赛（人工智能赛道）**
- 设计稀疏补丁优化算法生成对抗样本，攻击黑盒目标检测模型，使其错误分类
- 生成后门样本在受害模型植入后门，使其对正常交通标志牌能够正常检测，而对后门样本检测框正常识别，但是类别全部识别为目标标签

**竞赛&emsp;&emsp; Kaggle：LLM - Detect AI Generated Text**
*比赛内容：检测论文是否是由LLM生成的*
- 使用EDA分析学生写的论文和LLM生成的论文之间在词语的选择偏好、词频等方面上的差距。
- 通过LSA来评估文章在主题上的连贯性，用于评估学生写的论文与LLM生成的论文在主题一致性上个存在差异。
- 使用预训练大模型Mistral-7B序列分类

## 项目经历
LLM调用Stable Diffusion搭建一个多模态Agent
1. 构建prompt解析函数，实现自动对用户输入文本自动解析并进行api请求。
2. 使用Langchain构建意图识别Agent，判断用户输入是否进行文生图，调用sdweb api
3. 构建关键词检测，通过判断用户文本中是否存在关键词进行意图识别。


## 科研论文成果

<div style="display: flex; justify-content: space-between;">
    <div><strong>PointCRT: Detecting Backdoor in 3D Point Cloud via Corruption Robustness.</strong></div>
    <div>2023</div>
</div>
点云后门样本检测，学生一作，发表于CCF-A会议 ACM MM, 2023 (oral)

<div style="display: flex; flex-wrap: wrap;">
    <div style="flex-basis: 100%;"><strong>PointCA: Evaluating the Robustness of 3D Point Cloud Completion Models Against Adversarial Examples.</strong></div>
    <div style="width: 100%; text-align: right;">2023</div>
</div>
点云补全对抗攻击，学生二作，发表于CCF-A会议 AAAI, 2023 (oral)




## 其他

- 编程：Python、C++
- 工具框架：熟练掌握深度学习框架Pytorch的基础知识，熟悉Carla的基本使用，了解LangChain的基本用法与应用，了解Stable difusion WebUI常见插件使用方法
- 技能：机器学习安全，预训练模型微调
- 大语言模型：熟悉常见大语言模型基础知识，了解大语言模型微调方法
- 通过 CET4/6 英语等级考试，分别为625、557
