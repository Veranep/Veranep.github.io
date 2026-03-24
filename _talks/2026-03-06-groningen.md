---
title: "How User Sociodemographics Inadvertently Affect LLM-User Conversations"
collection: talks
type: "Talk"
permalink: /talks/2026-03-06-groningen
venue: "CL Group Seminar"
date: 2026-03-06
location: "Groningen, The Netherlands"
---

Generative Large Language Models (LLMs) personalize responses based on perceived user characteristics, a phenomenon called implicit personalization. This can enhance user experience but also introduce or amplify bias when models infer sociodemographic attributes from subtle conversational cues. In this talk, I present a systematic investigation of how LLMs infer and act on such information when confronted with stereotypical cues. Using controlled synthetic conversations, we show that models extract demographic attributes from stereotypical cues and encode them in latent user representations; notably, for several groups, these inferences persist even when users explicitly identify with a different demographic group. I will also present work in which we examine the methodological foundations of persona-based bias research by comparing six commonly used sociodemographic cues across seven LLMs on a range of tasks. Although outputs generated from different cues are often correlated, we observe substantial variance in how personas are realized, underscoring LLM sensitivity to prompt formulation and cautioning against drawing conclusions from a single cue. Together, our findings highlight both the prevalence and malleability of demographic inference in LLMs and argue for greater transparency, methodological rigor, and user control in personalization research and deployment.
