# LLM Eval 

# 按领域/专项能力

## Math 
​​[GSM8K​​](https://github.com/hkust-nlp/ceval)   
OpenAI发布的数学应用题数据集，包含8,500道小学至中学水平题目，侧重数学推理能力。   
发布 2021年 OpenAI

[MATH500](https://github.com/openai/prm800k/tree/main?tab=readme-ov-file#math-splits)   
发布 OpenAI  

[AIME 2024]()   American Invitational Mathematics Examination  
美国数学邀请赛，针对中学生，3h15道题目。  

## Code 

[Codeforces](https://codeforces.com/)  
算法竞赛平台  

[SWE-bench](https://www.swebench.com/)    
一句话介绍： 测试模型解决github上流行的python项目的真实问题的能力。  
SWE-Bench是由普林斯顿大学和芝加哥大学研究者提出（ICLR 2024发表）的真实世界软件工程评测基准，通过2,294个来自12个流行Python开源项目的GitHub真实问题与PR任务，评估大语言模型在复杂代码库中完成跨文件bug修复和功能改进的能力，要求生成代码通过原库测试验证，并具备处理数十万行代码的长上下文及持续扩展特性。   
发布 2024/03  Princeton  [HuggleFace](https://huggingface.co/princeton-nlp)  

[multi-swe-bench](https://github.com/multi-swe-bench/multi-swe-bench)  
一句话介绍：测试模型解决github上多语言项目的真实问题的能力。  
发布 2025/04  字节


## 事实评估  
[SimpleQA](https://github.com/openai/simple-evals/)   
事实性基准测试，用于衡量语言模型回答简短的事实搜索类问题的能力。   
发布 2024/10 OpenAI 英文 

[C-SimpleQA](https://huggingface.co/datasets/OpenStellarTeam/Chinese-SimpleQA)       
中文版事实性基准测试，用于衡量语言模型回答简短的事实搜索类问题的能力。  
发布 2024/11  中文    OpenStellarTeam  
3000个高质量问题组成，涵盖6个主要主题和99个细分主题  

## 阅读理解  
[DROP](https://arxiv.org/abs/1903.00161)  A Reading Comprehension Benchmark Requiring Discrete Reasoning Over Paragraphs  
基于给定的段落文字，提取信息进行推理，计算和排序。
发布 2019/03   英文

## 推理能力  
[BIG-Bench](https://github.com/google/BIG-bench/tree/main)  
测评大模型一般推理能力（不局限数学和编码），涉及200多个推理任务。  
发布 2021  Google   

[BIG-Bench Extra Hard](https://github.com/google-deepmind/bbeh)    
BIG-Bench的增强版，每个任务的难度显著增强。   
发布 2025 Google



# 通用能力/多学科跨领域      


[c-eval](https://github.com/hkust-nlp/ceval)       
中文综合能力测试，覆盖52个学科、13,948道多选择题，评测模型对中文知识体系的理解。
发布 2023年  HKUST

[​​MMLU](https://arxiv.org/pdf/2009.03300) 
​​Massive Multitask Language Understanding   
英文多任务测试，涵盖57个学科（如数学、法律、伦理），评估跨领域知识掌握能力。
发布 2021   UCBerkeley

[MMLU-Pro](https://huggingface.co/datasets/TIGER-Lab/MMLU-Pro) 
MMLU进阶版，提高了问题的质量，增加了问题的难度。   
选择题从4个选项变成10个选项，提高了题目中推理能力的要求，增加了大学考试级别的问题。

发布 2024/07   

[CMMLU](https://github.com/haonan-li/CMMLU)  
Chinese Massive Multitask Language Understanding      
中文版多任务测试，继承MMLU框架。涵盖多个学科和领域，评估跨领域知识掌握能力。
常识类、人文、社科、理工等共67个主题 
11,528道多选题，其中67个主题每个主题至少105道题


[GPQA](https://github.com/idavidrein/gpqa/)    AGraduate-Level Google-Proof Q&ABenchmark    
研究生级别且无法通过google搜索得到答案的问答测试。由领域内（生物化学和物理）专家编写的448道多选题。  
发布日期  2023/11月  

GPQA Diamond   
GPQA挑选出来的的高质量子集，包含其中198道题目。 
挑选标准：由领域专家选择，且，非专家答对概率低于 1/3。

[FRAMES](https://arxiv.org/abs/2409.12941)   
测评大模型基于维基百科的RAG回答的效果。  
发布 2024/09 Google  [HuggineFace](https://huggingface.co/datasets/google/frames-benchmark)

# 多模态 
[MMMU](https://mmmu-benchmark.github.io)
多模态（文字+图像），多科学和领域


# 测试平台   
[FlagEval](https://flageval.baai.ac.cn/#/home)   
北京智源  
评测领域：自然语言处理（NLP）、计算机视觉（CV）、音频（Audio）、多模态（Multimodal）


