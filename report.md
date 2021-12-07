---
layout: report_layout
---

At the start of June, we [announced the NetHack Challenge 2021](https://ai.facebook.com/blog/launching-the-nethack-challenge-at-neurips-2021/), hosted at NeurIPS 2021, as a partnership between Facebook (now Meta) AI Research, AI Crowd, Oxford, UCL, and NYU. We furthermore were supported by our sponsors, Facebook AI (now Meta AI), and DeepMind. [In this challenge](https://www.aicrowd.com/challenges/neurips-2021-the-nethack-challenge), we set out the goal to beat NetHack using any method you want (within the bounds of compute/time restrictions at test time) or—failing that—get as high an in-game score as possible. The competition has ended, and in this post, we will present and discuss the results, having first briefly recapped why this challenge matters for AI research, and what the rules and stakes were.


## Why we organized NetHack Challenge
Write about NLE and why it’s important for RL (and AI) research
Discuss motivations for competition, perhaps hint at people’s expectations (Deep RL wins the day)

NetHack (originally released in 1987 but still actively developed) is one of the oldest and most popular rogue-like games as well as one of the hardest video games in existence. At NeurIPS 2020, researchers Facebook AI Research, UCL, NYU, and Oxford presented the NetHack Learning Environment (NLE) as a fast but complex RL environment based on NetHack, together with a baseline RL agent based on TorchBeast. However, our baseline agent is still many orders of magnitude away from expert human performance on NetHack. As a new frontier for RL research, there’s so much room for improvement on NLE that we felt we need the whole community to come together to make progress. So we organized the NeurIPS 2021 NetHack Competition Challenge. One of our goals was to see just how creative people can get without restrictions in training and agent design--and in doing so, move the classic symbolic AI vs deep learning debate forward. Deep learning techniques have won many battles recently, but will they win at the quest for NetHack’s coveted Amulet of Yendor?


Check out the [NetHack Wiki](https://nethackwiki.com/wiki/Main_Page){:target="_blank"} and [nethack.org](http://nethack.org/){:target="_blank"} to learn more about NetHack, or head over to the [Challenge Page](https://www.aicrowd.com/challenges/neurips-2021-nethack-challenge){:target="_blank"} for an intro.


## What is the NetHack Learning Environment?

The NetHack Learning Environment (NLE) is a Reinforcement Learning environment presented at NeurIPS 2020. NLE is based on [NetHack 3.6.6](https://github.com/NetHack/NetHack/tree/NetHack-3.6.6_PostRelease){:target="_blank"} and designed to provide a standard RL interface to the game, and comes with tasks that function as a first step to evaluate agents on this new environment. You can read more about NLE in the [NeurIPS 2020 paper](https://arxiv.org/abs/2006.13760){:target="_blank"}.


## About the NetHack Challenge At NeurIPS 2021

The NetHack Challenge invites entrants, using any method they choose, to develop agents that can reliably either beat the full game of NetHack or achieve as high a score as possible. No restrictions are placed on how the agent is trained and contestants will use their own hardware. Evaluation will be performed in a controlled setting, thanks to our partner and co-organizer, [AIcrowd](https://www.aicrowd.com/){:target="_blank"} who will run the competition [through their platform](https://www.aicrowd.com/challenges/neurips-2021-the-nethack-challenge){:target="_blank"}.

We are excited that this competition offers machine learning students, researchers and NetHack-bot builders the opportunity to participate in a grand challenge in AI - without prohibitive computational costs — and we are eagerly looking forward to the wide variety of submissions.


## Participation Information:
There will be four competition tracks:
<div style="color: #199696; font-size: 22px; font-weight: 400;">1. Best overall agent</div>
Winner: $3000, Runner up: $2000 — Awarded to the best-performing agent in the competition. All submitted agents qualify for this track.

<div style="color: #199696; font-size: 22px; font-weight: 400;">2. Best agent substantially using a neural network</div>
Winner: $3000, Runner up: $2000 — Awarded to the best-performing agent making substantial use of a neural network or significantly similar modeling technique.

<div style="color: #199696; font-size: 22px; font-weight: 400;">3. Best agent not using a neural network</div>
Winner: $3000, Runner up: $2000 — Awarded to the best-performing agent not using a neural network or significantly similar modeling technique.

<div style="color: #199696; font-size: 22px; font-weight: 400;">4. Best agent from an academic/independent team</div>
Winner: $3000, Runner up: $2000 — Awarded to the best-performing agent produced by a team predominantly led by non-industry-affiliated researchers.

Competitors can be eligible for multiple tracks and the prizes associated with them.


The competition runs from early June through October 15, and the winners will be announced at NeurIPS in December. For more information, check out the [Challenge Page](https://www.aicrowd.com/challenges/neurips-2021-nethack-challenge){:target="_blank"}, read our blog [here](https://ai.facebook.com/blog/launching-the-nethack-challenge-at-neurips-2021){:target="_blank"}. You can also follow us on [Twitter](https://twitter.com/NetHack_LE){:target="_blank"}, join our [Discord server](https://discord.gg/zkFWQmSWBA){:target="_blank"}, or get acquainted with the [NetHack Learning Environment](https://github.com/facebookresearch/nle){:target="_blank"}.


## Sponsors

We'd like to thank our sponsors for their contributions to the NetHack Challenge:

* <b>Facebook AI Research</b>
* <b>DeepMind</b>
