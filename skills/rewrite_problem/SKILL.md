---  
name: rewrite-problem  
description: Transforms vague or ill-defined questions into clear, structured, and actionable "good problems" by extracting the core objective, identifying comparison dimensions, and applying structured reasoning. Use when a user wants to compare multiple options, evaluate trade-offs, make a decision between alternatives, or asks questions like "which is better", "pros and cons", "help me decide", "how should I choose", or "what are the trade-offs". Produces a rewritten problem statement with explicit comparison dimensions, a structured evaluation framework, and a decision-ready output format.  
---  

# Rewrite Problem to Good Problem  

## 验收条件：好问题的模板
好问题能补全以下句子：
> "在【场景 / 约束】下，为了【目标】，比较 / 选择 / 设计【对象】，按【维度 / 指标】评估，并以【输出格式】给出结论。"

## Instructions  
1. **Extract Primary Objective**: Identify the core goal or main purpose of the original problem in one sentence.  
2. **Identify Comparison Dimensions**: List the specific aspects or criteria needed to address the primary objective.  
3. **Analyze Each Dimension**: For every dimension, perform an independent and in-depth analysis. Choose the most appropriate structured reasoning form for the scenario (e.g. 溯因推理、归纳推理、类比推理、统计概率推理、目的 - 手段实践推理), and label it explicitly.
4. **Rewrite into a Good Problem**: Reframe the original problem into a clear, structured, and actionable question using the template above.

## 好问题的定义标准
- **清晰**：问题具体明确，关键概念可定义，边界明确，避免模糊或宽泛。  
- **结构化**：包含明确的比较维度或分析框架，有维度 / 指标，能分解成子问题。  
- **可操作**：能够引导出具体的解决方案或结论，产出比较表、决策矩阵或评估报告。  

## 示例

**原始问题（模糊）**：我应该用 React 还是 Vue？

**Primary Objective**: 为团队的新 Web 项目选择最合适的前端框架，以平衡开发效率与长期维护成本。

**Comparison Dimensions**: 学习曲线、生态系统成熟度、团队现有技能、社区支持、性能表现。

**Dimension Analysis（目的 - 手段实践推理）**:  
- 要实现"降低长期维护成本"，必须满足"框架有稳定的长期支持和活跃社区"；因此必须评估两个框架的发布周期与社区活跃度。

**Good Problem**: 在团队以 JavaScript 为主、项目周期 18 个月的约束下，为了最大化开发效率并降低维护成本，比较 React 与 Vue，按学习曲线、生态成熟度、社区支持、团队适配性四个维度评估，并以优劣对比表和推荐结论的形式给出答案。

---

## 输出格式  
- **Primary Objective**: 用一句话概括核心目标。  
- **Comparison Dimensions**: 列出需要比较的关键维度。  
- **Dimension Analysis**: 每个维度的推理过程（标注所用推理形式）。  
- **Good Problem**: 重写后的好问题，套用验收条件模板，以清晰、结构化的形式呈现。
