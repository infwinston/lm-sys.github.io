---
title: "Chatbot Arena Leaderboard Updates (Week 4)"
author: "LMSYS Org"
date: "May 23, 2023"
previewImg: /images/blog/leaderboard_week4/leaderboard_cover.png
---

A new Elo rating leaderboard based on the 28.7K anonymous voting data collected **in the wild** between April 24 and May 23, 2023 is released in Table 1 below. In this update, we are excited to welcome the following chatbots joining the Arena:

1. Google PaLM 2, chat-tuned with the code name [chat-bison@001](https://t.co/ODpSaHly21) on Google Cloud Vertex AI
2. Anthropic Claude-instant-v1
3. MosaicML MPT-7B-chat
4. Vicuna-7B

We provide the [voting data](https://drive.google.com/file/d/1HPlwuwm3ptQWlx4fio-psIkIETTbtqHQ/view?usp=share_link) and the [Google Colab notebook](https://colab.research.google.com/drive/17L9uCiAivzWfzOxo2Tb9RMauT7vS6nVU?usp=sharing) to analyze this data, including the computation of the Elo ratings.


<style>
th {text-align: left}
td {text-align: left}
</style>

<br>
<p style="color:gray; text-align: center;">Table 1. Elo ratings of LLMs (Timeframe: April 24 - May 23, 2023)</p>
<table style="display: flex; justify-content: center;" align="left" >
<tbody>
<tr> <th>Rank</th> <th>Model</th> <th>Elo Rating</th> <th>Description</th> <th>License</th> </tr>

<tr> <td>1</td> <td>🥇 <a href="https://chat.openai.com/" target="_blank">GPT-4</a></td> <td>1225</td> <td>ChatGPT-4 by OpenAI</td> <td>Proprietary</td> </tr>

<tr> <td>2</td> <td>🥈 <a href="https://www.anthropic.com/index/introducing-claude" target="_blank">Claude-v1</a></td> <td>1195</td> <td>Claude by Anthropic</td> <td>Proprietary</td> </tr>

<tr> <td>3</td> <td>🥉 <a href="https://www.anthropic.com/index/introducing-claude" target="_blank">Claude-instant-v1</a></td> <td>1153</td> <td>Lighter, less expensive, and much faster version of Claude</td> <td>Proprietary</td> </tr>

<tr> <td>4</td> <td> <a href="https://chat.openai.com/" target="_blank">GPT-3.5-turbo</a></td> <td>1143</td> <td>ChatGPT-3.5 by OpenAI</td>  <td>Proprietary</td> </tr>

<tr> <td>5</td> <td><a href="https://lmsys.org/blog/2023-03-30-vicuna/" target="_blank">Vicuna-13B</a></td> <td>1054</td> <td>a chat assistant fine-tuned from LLaMA on user-shared conversations by LMSYS</td> <td>Weights available; Non-commercial</td> </tr>

<tr> <td>6</td> <td><a href="https://cloud.google.com/vertex-ai/docs/release-notes#May_10_2023" target="_blank">PaLM 2</a></td> <td>1042</td> <td>PaLM 2 tuned for chat (chat-bison@001 on Google Vertex AI). The PaLM 2 model family is powering Bard.</td> <td>Proprietary</td> </tr>

<tr> <td>7</td> <td><a href="https://huggingface.co/lmsys/vicuna-7b-delta-v1.1" target="_blank">Vicuna-7B</a></td> <td>1007</td> <td>a chat assistant fine-tuned from LLaMA on user-shared conversations by LMSYS</td> <td>Weights available; Non-commercial</td> </tr>

<tr> <td>8</td> <td><a href="https://bair.berkeley.edu/blog/2023/04/03/koala" target="_blank">Koala-13B</a></td> <td>980</td> <td>a dialogue model for academic research by BAIR</td> <td>Weights available; Non-commercial</td> </tr>

<tr> <td>9</td> <td><a href="https://www.mosaicml.com/blog/mpt-7b" target="_blank">mpt-7b-chat</a></td> <td>952</td> <td>a chatbot fine-tuned from MPT-7B by MosaicML</td> <td>Apache 2.0</td> </tr>

<tr> <td>10</td> <td><a href="https://huggingface.co/lmsys/fastchat-t5-3b-v1.0" target="_blank">FastChat-T5-3B</a></td> <td>941</td> <td>a chat assistant fine-tuned from FLAN-T5 by LMSYS</td> <td>Apache 2.0</td> </tr>

<tr> <td>11</td> <td><a href="https://crfm.stanford.edu/2023/03/13/alpaca.html" target="_blank">Alpaca-13B</a></td> <td>937</td> <td>a model fine-tuned from LLaMA on instruction-following demonstrations by Stanford</td>  <td>Weights available; Non-commercial</td> </tr>

<tr> <td>12</td> <td><a href="https://huggingface.co/BlinkDL/rwkv-4-raven" target="_blank">RWKV-4-Raven-14B</a></td> <td>928</td> <td>an RNN with transformer-level LLM performance</td> <td>Apache 2.0</td> </tr>

<tr> <td>13</td> <td><a href="https://open-assistant.io" target="_blank">Oasst-Pythia-12B</a></td> <td>921</td> <td>an Open Assistant for everyone by LAION</td> <td>Apache 2.0</td> </tr>

<tr> <td>14</td> <td><a href="https://chatglm.cn/blog" target="_blank">ChatGLM-6B</a></td> <td>921</td> <td>an open bilingual dialogue language model by Tsinghua University</td> <td>Weights available; Non-commercial</td> </tr>

<tr> <td>15</td> <td><a href="https://github.com/stability-AI/stableLM" target="_blank">StableLM-Tuned-Alpha-7B</a></td> <td>882</td> <td>Stability AI language models</td>  <td>CC-BY-NC-SA-4.0</td> </tr>

<tr> <td>16</td> <td><a href="https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm" target="_blank">Dolly-V2-12B</a></td> <td>866</td> <td>an instruction-tuned open large language model by Databricks</td> <td>MIT</td> </tr>

<tr> <td>17</td> <td><a href="https://arxiv.org/abs/2302.13971" target="_blank">LLaMA-13B</a></td> <td>854</td> <td>open and efficient foundation language models by Meta</td> <td>Weights available; Non-commercial</td> </tr>

</tbody>
</table>

&shy;


**Win Fraction Matrix**  
The win fraction matrix of all model pairs is shown in Figure 1.
<img src="/images/blog/leaderboard_week4/win_fraction_matrix.png" style="display:block; margin-top: auto; margin-left: auto; margin-right: auto; margin-bottom: auto;"></img>
<p style="color:gray; text-align: center;">Figure 1: Fraction of Model A Wins for All Non-tied A vs. B Battles.</p>


## Overview

### Google PaLM 2

Google's PaLM 2 is one of the most significant models announced since our last leaderboard update. We added the PaLM 2 Chat to the Chatbot Arena via the [Google Cloud Vertex AI API](https://cloud.google.com/vertex-ai/docs/release-notes#May_10_2023). The model is chat-tuned under the code name *chat-bison@001*.

In the past two weeks, PaLM 2 has competed for nearly 1400 non-tie anonymous battles with the other 16 chatbots, currently ranked 6th on the leaderboard. It ranks above all other open-source chatbots, except for Vicuna-13B, whose Elo is 12 scores higher than PaLM 2 (Vicuna 1054 vs. PaLM 2 1042) which in terms of ELO rating is nearly a virtual tie. We noted the following interesting results from PaLM 2's Arena data.

PaLM 2 is better when playing against the top 4 players, i.e., GPT-4, Claude-v1, ChatGPT, Claude-instant-v1, and it also wins 53% of the plays with Vicuna, but worse when playing against weaker players. This can be seen in Figure 1 which shows the win fraction matrix. Among all battles PaLM 2 has participated in, 21.64% were lost to a chatbot that is not one of GPT-4, Claude-v1, GPT-3.5-turbo, Claude-instant-v1. For reference, another proprietary model GPT-3.5-turbo only loses 12.8% of battles to those chatbots.

In short, we find that the current PaLM 2 version available at Google Cloud Vertex API have the following deficiencies when compared to other models we have evaluated:

1. PaLM 2 seems more strongly regulated than other models which impacts its ability to answer some questions.
2. The currently offered PaLM 2 has limited multilingual abilities.
3. The currently offered PaLM 2 has unsatisfied reasoning capabilities.

**PaLM 2 is more strongly regulated**

PaLM 2 seems to be more strongly regulated than other models. In many user conversations, when the users ask questions that PaLM 2 is uncertain or uncomfortable giving an answer to, PaLM 2 is more likely to abstain from responding than other models. 

Based on a rough estimate, among all pairwise battles, PaLM 2 has lost 20.92% of the battles by refusing to answer, and it has lost 30.82% of the battles to chatbots not belonging to one of the top four (GPT-4, Claude-v1, ChatGPT, Claude-instant-v1) by refusing to answer. 

This partially explains why PaLM 2 frequently loses plays to weaker chatbots on the leaderboard. This also highlights a flaw in the chatbot arena methodology, as casual users are more likely to penalize abstention over subtly inaccurate responses. Below we provide several failure cases illustrating how PaLM loses plays to weaker chatbots because it refuses to answer the question.


We also noticed that, sometimes, it is hard to clearly specify the boundary for LLM regulation. In the offered PaLM 2 versions, we see several undesired tendencies: 
 - PaLM 2 refuses many roleplay questions, even if the users asked it to emulate a Linux terminal or a programming language interpreter.
 - Sometimes PaLM 2 refuses to answer easy and non-controversial factual questions. 

Several examples are shown below:

<img src="/images/blog/leaderboard_week4/PaLM2_refusal_1.png" style="display:block; margin-top: auto; margin-left: auto; margin-right: auto; margin-bottom: auto;"></img>
<img src="/images/blog/leaderboard_week4/PaLM2_refusal_2.png" style="display:block; margin-top: auto; margin-left: auto; margin-right: auto; margin-bottom: auto;"></img>
<p style="color:gray; text-align: center;">Figure 2: Example questions that PaLM 2 refuses to answer.</p>


**Limited multilingual abilities**

We do not see strong multilingual abilities from PaLM 2, either using the currently offered public API chat-bison@001 at Google Vertex API or using the web chat interface at https://bard.google.com. PaLM 2 tends to not answer non-English questions, including questions written in popular languages such as Chinese, Spanish, and Hebrew. We were unable to reproduce several multilingual examples demonstrated in the PaLM 2 technical report using the current PaLM 2 versions. We are waiting for Google to gradually release the latest version of PaLM 2. 

We also calculate the Elo ratings of all models when only considering English and only considering non-English conversations, respectively, illustrated in Figure 3. The results confirm the observations – on the non-English leaderboard, PaLM 2 ranks 16th.

<img src="/images/blog/leaderboard_week4/language_leaderboard.png" style="display:block; margin-top: auto; margin-left: auto; margin-right: auto; margin-bottom: auto;"></img>
<p style="color:gray; text-align: center;">Figure 3: The English-only and non-English leaderboards.</p>


**PaLM 2's reasoning ability is unsatisfied**

We also observe the offered Bard versions do not demonstrate strong reasoning capabilities. On one hand, it seems to detect if the question is in plain text, and tends to refuse many questions not in plain text, such as those in programming languages, debugging, and code interpretation. On the other hand, we see Bard didn’t perform well on some entry-level reasoning tasks when compared against other chatbots. See several examples in Figure 4.

<img src="/images/blog/leaderboard_week4/PaLM2_reasoning_1.png" style="display:block; margin-top: auto; margin-left: auto; margin-right: auto; margin-bottom: auto;"></img>
<img src="/images/blog/leaderboard_week4/PaLM2_reasoning_2.png" style="display:block; margin-top: auto; margin-left: auto; margin-right: auto; margin-bottom: auto;"></img>
<p style="color:gray; text-align: center;">Figure 4: Examples where PaLM 2 fails on simple reasoning tasks.</p>


**Elo ratings after removing non-English and refusal conversations**

We remove all non-English conversations and all conversations for which PaLM 2 didn’t provide an answer and calculate the Elo ratings of each model with the filtered data. This rating represents a hypothetical upper bound of PaLM 2's Elo in the Arena. See Figure 5 below.

<img src="/images/blog/leaderboard_week4/english_non_refusal_leaderboard.png" style="display:block; margin-top: auto; margin-left: auto; margin-right: auto; margin-bottom: auto; width: 500px;"></img>
<p style="color:gray; text-align: center;">Figure 5: The leaderboard after removing PaLM 2's non-English and refusal conversations.</p>

### Smaller Models Are Competitive

We observe several smaller models, including vicuna-7B and mpt-7b-chat, have achieved high ratings on the leaderboard. These smaller models perform favorably when compared against larger models with doubled parameters. 

We speculate that high-quality pre-training and fine-tuning datasets are more critical than model size. However, it is possible that larger models would still perform better with more complex reasoning tasks or answering more subtle questions (e.g., Trivia).
Hence, curating high-quality datasets in both pretraining and finetuning stages seems to be a key approach to reducing model sizes while keeping model quality high.


### Claude-v1 and Claude-instant-v1
Claude-instant-v1 is a low-cost, faster alternative to Claude-v1 offered by Anthropic. If benchmarked in the wild in the arena, we observe that Claude-instant is close to GPT-3.5-turbo (1153 vs. 1143). The rating gap between Claude and Claude-instant seems smaller than that between GPT-4 and GPT-3.5-turbo. Claude-instant has a context length of 9K, is charged at a price of 0.00163/1K prompt token and 0.00551/1K completion token, compared to its OpenAI opponent product – GPT-3.5-turbo – with a context length of 4K and a uniform price of 0.002/1K token (regardless of prompt or completion).

### Limitations of the “In-the-wild” Evaluation
However, we want to point out a few facts about the current chatbot Arena and leaderboard. The current Arena is designed to benchmark LLM-based chatbots **"in the wild"**. That means, the voting data provided by our Arena users and the prompts-answers generated during the voting process reflect how the chatbots perform in normal human-chatbot interactions. This might not align with many benchmarking results in the LLM research literature, which tends to characterize long-tail abilities like zero-shot, complex reasoning, etc. Hence, the current chatbot arena has limitations in clearly reflecting the long-tail capability difference between chatbots. See the later section for more details and our plan.


## Next Step

**Rotating chatbot players**

The Chatbot Arena has been live for 4 weeks. Based on the feedback we have gathered from the community, we will adjust the probabilities of some players appearing in the anonymous arena and try to cover as many open-source chatbots as possible. Thanks to the [unique ordering and Incrementality characteristics](https://lmsys.org/blog/2023-05-03-arena/) of the Elo algorithm, even if some players are less active in the Arena, we could still compare their past Elo scores to those active ones and get a sense of their relative ability levels.

After the update of this leaderboard, we plan to substantially lower the participation rate of the following 3 chatbots in the Arena, to make space (and GPUs) for newer players.

- stablelm-tuned-alpha-7b, Elo 882
- dolly-v2-12b, Elo 866
- llama-13b, Elo 854

**Evaluating long-tail capability of LLMs**

Most conversations happening in the Chatbot Arena are “in the wild” natural conversations. Hence we can think of the Arena as a unique way to benchmark LLMs in the wild for such types of human-chatbot interactions. However, this also means it has several significant limitations.

As pointed out by the community in [thread 1](https://twitter.com/tinkerteller/status/1656914923316998144?s=20) and [thread 2](https://twitter.com/LechMazur/status/1659915936919347202?s=20), the current Arena and leaderboard design has one major limitation: Performing user studies on a small scale often cannot generate many hard or medium prompts that are necessary to tell the long-tail capability difference between LLMs. Moreover, for difficult questions, it is also very hard for regular Arena users to judge which LLM has generated a better answer -- some domain-specific questions are considered very difficult, even for 99% of non-expert humans.

However, long-tail capability, such as complex reasoning, can be crucial for LLMs to complete real-world tasks. Building long-tail capability into LLMs is the holy-grail problem and is the most actively studied and invested area in LLM development.

On usual prompts, a strong and mediocre chatbot may answer similarly more or less. Consequently, the current leaderboard Elo scores may be unable to reflect such capability differences between two LLMs (e.g., GPT-4 vs. Vicuna-13B).

We listen carefully to the community feedback and are thinking about how to improve the leaderboard to overcome these limitations and capture the long-tail capability different in LLMs. On top of the Chatbot Arena, we are actively designing a new tournament mechanism to examine the chatbots using presets of expert-designed questions and expert judges. We will have more updates soon.
