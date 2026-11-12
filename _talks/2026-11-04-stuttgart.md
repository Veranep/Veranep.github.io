---
title: "Beyond Demographics: How Conversational Context Shapes LLM Advice"
collection: talks
type: "Talk"
permalink: 2026-11-04-stuttgart
venue: "IMS Colloquium"
date: 2026-11-04
location: "Stuttgart"
---

Large language models (LLMs) increasingly provide high-stakes and personal advice, yet their recommendations can vary depending on what users reveal in conversation. This talk presents two studies examining how conversational context shapes advice outcomes and sycophancy. I will first present work that investigates what drives differences in LLM-generated advice across users. Although prior work has identified disparities between sociodemographic groups, we find that LLMs struggle to infer user sociodemographics from a single conversation history and that group-level disparities are small. Instead, conversation topics are the strongest predictors of advice outcomes among the (psycho)linguistic features we examined, sometimes acting as proxies for sociodemographic groups and influencing LLM-generated advice in unpredictable ways. Next, I will discuss a recent study in which we examine how disclosures of different aspects of users'  identities shape sycophancy. Across controlled synthetic and real-world conversations, disclosures involving feelings elicit more sycophantic responses than career-related disclosures, particularly for vulnerable users. Comparing mitigation strategies, we find that direct preference optimization (DPO) reduces overall sycophancy more effectively than prompting, but both methods are most effective for those receiving the least sycophantic answers to begin with. Together, our findings show that even seemingly unrelated disclosures can lead LLMs to respond differently to the same requests, and we call for the evaluation of LLMs and methods designed to improve their behavior in more realistic and dynamic conversational settings.
