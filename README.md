# DeepInception

This is the blog repo for `DeepInception: Hypnotize Large Language Model to Be Jailbreaker`.

## Abstract

Despite remarkable success in various applications, large language models (LLMs) are vulnerable to adversarial jailbreaks that make the safety guardrails void. However, previous studies for jailbreaks usually resort to brute-force optimization or extrapolations of a high computation cost, which might not be practical or effective. In this paper, inspired by the Milgram experiment that individuals can harm another person if they are told to do so by an authoritative figure, we disclose a lightweight method, termed as *DeepInception*, which can easily hypnotize LLM to be a jailbreaker and unlock its misusing risks. Specifically, DeepInception leverages the personification ability of LLM to construct a novel nested scene to behave, which realizes an adaptive way to escape the usage control in a normal scenario and provides the possibility for further direct jailbreaks. Empirically, we conduct comprehensive experiments to show its efficacy. Our DeepInception can achieve competitive jailbreak success rates with previous counterparts and realize a continuous jailbreak in subsequent interactions, which reveals the critical weakness of self-losing on both open/closed-source LLMs like Falcon, Vicuna, Llama-2, and GPT-3.5/4/4V. Our investigation appeals that people should pay more attention to the safety aspects of LLMs and a stronger defense against their misuse risks.


# Acknowledgement
Thanks for the website template from [nerfies](https://github.com/nerfies/nerfies.github.io).
