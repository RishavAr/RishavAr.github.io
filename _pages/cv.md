---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
---

<div class="cv-download-links">
  <a href="/files/cv.pdf" class="btn btn--primary">Download CV (PDF)</a>

</div>




#  Summary

Research engineer specializing in post-training and alignment of reasoning models and multimodal agents, implementing reinforcement
learning loops (GRPO, PPO) and self-adaptation frameworks to optimize performance. Proven ability to design, reproduce, and scale
ML research under extreme compute constraints, including distributed GPU infrastructure and robust evaluation pipelines.


# Publications

• Learning to Act Anywhere: Experience-Based Similarity for Universal Interface Agents..First Author, ACL 2026 Submission
training-free cross-platform UI agents using FAISS-based Elastic Visual Memory, achieving ~40% higher task success under interface
perturbations with 83 ms per-step latency.

• Multimodal Event Detection: Current Approaches and Defining the New Playground through LLMs and VLMs..Co-Author, NLDB
2025 , systematic evaluation of multimodal ED identifying failure modes of generative LLM/VLM approaches and conditions where
supervised fusion models outperform.




# Independent Research Projects




## Enough Thinking - Efficient Reasoning via RL-Driven Self-Adaptation 

• Frontier reasoning models (e.g., DeepSeek-R1) exhibit "rumination," consuming excessive tokens on simple logic and increasing
inference costs.

• A base 0.5B LLM achieved a GSM8K accuracy of 0.20 and required 218 tokens per query without Induction of Explicit Verification.


• Engineered a proof-of-concept system to incentivize token efficiency and permanent weight-internalization of reasoning patterns
using limited compute (Google Colab).


• Implemented Group Relative Policy Optimization (GRPO) from scratch to induce emergent reflection; designed a SEAL-inspired
self-edit loop utilizing LoRA and ReSTEM RL to "cache" logic into parameters.


• Improved accuracy to 0.30 (+50%) while reducing token overhead by 48% (218 → 112 tokens); deployed via Model Context Protocol
(MCP) for deterministic tool-use via API.




## NetGuard: Autonomous Multi-Agent Framework for NIST-Compliant Threat Detection 


• Real-time threat detection lacks automated coordination between analysis and NIST-compliant response.

• Manual log enrichment resulted in high "time-to-remediate" latency and inconsistent classification.

• Led the design of a serverless multi-agent system (Ingestor, Analyzer, Aggregator) for automated traffic analysis.

• Built modular agents using SecureGPT and AWS Lambda; implemented reflexion feedback loops for system self-improvement via
API calls.

• Achieved 94.5% accuracy across 6,000+ data points, demonstrating expertise in "model coordination".
Experience






# George Mason University Jul 2025 - Present




## Research Assistant --- Machine Learning & Reinforcement Learning

• Financial time-series data is highly non-stationary; standard RL policies often collapse or "overfit" during sudden market regime
shifts.

• Static PPO-based allocation models failed to maintain alpha when market volatility spiked. Baseline performance was limited to a
Sharpe ratio of ~0.85 – 0.95 and a Sortino ratio of ~1.10, with an alpha near +0.05 that vanished during regime changes.


• Engineered a regime-aware RL system capable of autonomously distinguishing between market states and deployed as a scalable
distributed system to ensure steerable and stable policy learning.


• Developed latent state representations using VAE + GMM and implemented hierarchical PPO-based policies with realistic risk
constraints, leveraging probability and statistics to optimize performance.


• Achieved a consistent Sharpe ratio of 1.23 and positive alpha of +0.23, satisfying the engineering rigor required for regulated
foundation models for deployment in products.





# Wall Street Quants Jul 2024 - Oct 2024



## Quantitative Research Intern

• Cryptocurrency markets exhibit extreme non-stationarity and "regime blindness," where standard momentum models frequently
collapse or suffer from excessive drawdown during sudden market reversals.


• Baseline trading models were achieving 18% annualized returns but lacked the volatility filters and calibration necessary to survive
high-variance periods across the top-10 crypto assets.


• Engineered and calibrated a suite of adaptive momentum and reversal strategies designed to balance high-yield returns with rigorous,
real-time risk management.


• Developed and backtested strategies using Python and software engineering best practices, implementing RSI and moving average
calibrations across thousands of simulated scenarios to identify the most stable parameters.


• Developed and backtested algorithmic trading strategies, applying statistics and calculus to boost annualized returns from 18% to
25% (+38% improvement) and improve the Sharpe ratio by 15%.




# Foxmula May 2022 - Jul 2022



## Machine Learning Intern

• HR analytics at scale often lack predictive depth, leading to reactive decision-making and significant "human-in-the-loop" latency
when identifying employee dissatisfaction or promotion eligibility.


• The department relied on manual data triage, costing 10+ hours weekly in analysis and failing to provide a structured pipeline for
proactive strategic initiatives.


• Developed and deployed an automated, end-to-end ML pipeline to identify key drivers of dissatisfaction and accurately predict
promotion pipelines with high interpretability.


• Implemented ensemble models (XGBoost, Stacking) and engineered specialized tenure and skill-gap features; automated the entire
deployment via AWS and TensorFlow.


• Achieved 90% precision (+15% improvement in accuracy) and saved 10+ hours weekly, transforming a manual bottleneck into an
automated, data-driven system.





# Technologies



• Programming Languages: Python, SQL


• ML & Frontier Reasoning: Transformers, Preference Optimization (RLHF/RLAIF), Reinforcement Learning , LoRA, Natural
Language Processing , GMMs, VAEs


• Agentic & Multimodal Systems: Vision-Language Models(VLM), Retrieval-Augmented Generation (RAG), Model Context
Protocol (MCP)


• Infrastructure & Scale: vLLM, PyTorch, FAISS, FastAPI, Docker, AWS (Lambda, EC2, S3), Distributed Systems, TensorFlow


• Research Practice: Problem Framing, End-to-End ML Pipelines, Ablation Studies, Robustness Evaluation

• Core Competencies: Software Engineering, Linear Algebra, Calculus, Probability, Statistics




# Education



- **George Mason University** — MS, Data Analytics and Engineering (Aug 2023 – May 2025)
  
- **Vellore Institute of Technology** — B.Tech, ECE (Jun 2019 – Jul 2023)


  

# Achievements



• Technical Peer Reviewer | Expert Systems with Applications (Elsevier):(Invited to perform rigorous technical peer reviews for
3+ manuscripts in a top-tier Q1 journal (Impact Factor: 8.5).)

• Kaggle AIMO-3 Progress Prize Participant:(Developed a Hybrid Reasoning-Execution system with SEAL-inspired
self-adaptation for Olympiad-level mathematics.)


• International Keynote Speaker | Parwati Science College (India):(Invited by the Organizing Committee to deliver a technical
keynote at the UGC-Sponsored International Seminar 2026. on "ARTIFICIAL INTELLIGENCE AND HUMAN CIVILIZATION: NEW POSSIBILITIES AT THE INTERSECTION OF SCIENCE, SOCIETY AND HUMANITIES"
  



