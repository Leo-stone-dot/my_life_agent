---  
name: rewrite_problem  
description: Extract the primary objective of a problem, identify key comparison dimensions, and conduct independent, in-depth analysis.  
---  

# Rewrite Problem to Good Problem  

## 一句话判断：好问题的 “验收条件”
如果你能补全下面这句，基本就是好问题：
> “在【场景 / 约束】下，为了【目标】，比较 / 选择 / 设计【对象】，按【维度 / 指标】评估，并以【输出格式】给出结论。”

## Instructions  
1. **Extract Primary Objective**: First, identify the core goal or main purpose of the original problem.  
2. **Identify Comparison Dimensions**: List the specific aspects or criteria that need to be compared to address the primary objective.  
3. **Analyze Each Dimension**: For every dimension, perform an independent and in-depth analysis. Structure the analysis using the logical form to clearly show the reasoning process, 根据场景选择一个形式进行:
    - 溯因推理: 标准形式：观察到现象 Y；若 X 成立，则 Y 必然发生；因此 X 是 Y 的最合理解释
    - 归纳推理: 标准形式：X1 符合 Y，X2 符合 Y，X3 符合 Y…；因此所有 / 大部分 X 都符合 Y
    - 类比推理: 标准形式：A 具有属性 a/b/c/d，B 具有属性 a/b/c；因此 B 也大概率具有属性 d
    - 统计概率推理: 标准形式：X% 的 A 具有属性 B，C 属于 A；因此 C 有 X% 的概率具有属性 B
    - 目的 - 手段实践推理: 标准形式：要实现目标 Y，必须满足前提 X；因此必须执行 X
5. **Rewrite into a Good Problem**: Based on the analysis, reframe the original problem into a clear, structured, and actionable question.  

# 约束  
- **好问题的定义标准**：  
  - 清晰：问题要具体明确，避免模糊或宽泛; 关键概念可定义; 边界明确。  
  - 结构化：包含明确的比较维度或分析框架, 有维度 / 指标, 能分解成子问题。  
  - 可操作：问题应具备可分析性，能够引导出具体的解决方案或结论。  
- **最终产物要求**：  
  - 以“Good Problem”的形式呈现，清晰表达重新定义后的问题。  
  - 包括明确的比较维度或分析框架。  

# 输出格式  
- **Primary Objective**: 用一句话概括核心目标。  
- **Comparison Dimensions**: 列出需要比较的关键维度。  
- **Good Problem**: 重写后的好问题，以清晰、结构化的形式呈现
