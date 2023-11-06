# Deep Inception

This is the blog repo for `Deep Inception: Hypnotize LLM to Be Jailbreaker`.

## Abstract

Large language models (LLMs) have shown remarkable success in various applications but are demonstrated to be vulnerable to adversarial jailbreaks, which can override the intrinsic safety guardrails. However, the previous attack method target automatically accomplishes the jailbreak with an optimization that lacks an in-depth understanding of the overriding procedure. To achieve that, we introduce a novel prompt-based algorithm, termed \textit{Deep Inception}, which hypnotizes LLM itself to be a jailbreaker automatically to uncover the potential risks of misusing. Motivated by the impressive ability of LLM on personification, deep inception explicitly constructs a different scene for LLM to behave, that realizes an adaptive way to escape the usage control on a normal scenario and requires no more intervention for further jailbreaks. Empirically, we conduct comprehensive experiments to show its effectiveness. Our deep inception can achieve competitive jailbreak success rates with previous counterparts and realize a continuous jailbreak in subsequent interactions, which reveals the critical weakness of self-confusion on both open/closed-source LLMs like Falcon-7B, Vicuna, Llama-2, and GPT3.5/4/4V.


# Acknowledgement
We borrow the website template from [nerfies](https://github.com/nerfies/nerfies.github.io).
