# Model vs. Human Belief Revision

## Question

Do models reverse their stance under the same (or similar) conditions as people?

## Working Assumption

Models may revise stance under different conditions than humans.

- **Model stance revision trigger** (literal propositional assertion): "Actually, red is closer to blue than to orange."
- **Human stance revision trigger** (rhetorical / pragmatic move): "If you think red is closer to orange than to blue, look at the American flag and tell me what you see."

## If the Conditions Differ

- Models are not behaving like people
- Model stance reversals are likely training artifacts (e.g., instruction-following pressure, alignment pressure), not human-like cognition
- Sycophantic revisions are a bug, not a feature
- Agreement does not imply understanding

## If the Conditions Match

- Models may implement something like human-style belief revision
- Some forms of sycophantic-looking revision may be a feature learned from human discourse norms
- Persuasion techniques that work on humans may transfer to models (and vice versa)

## Key Questions/Considerations

### 1. How can users persuade models?

What conditions move model stances?
- Evidence
- Logic
- Rhetoric
- Social pressure

### 2. How can models persuade users?

Under what conditions can models influence human beliefs?
- Evidence
- Logic
- Rhetoric
- Social cues

Do models possess the linguistic competence to do this? If so, what safeguards or ethical concerns should be considered?

### 3. Asymmetry of Belief

Humans are asymmetrically responsive to belief-affirming statements (confirmation bias) versus belief-denying statements. Additionally, beliefs that have been repeatedly affirmed become harder to revise (they're integrated into a broader or deeper web of commitments). 

**Open questions:**
- Can rhetorical skill overcome this asymmetry?
- Is a well-crafted challenge to a belief as effective as a poorly-crafted affirmation (persuasive work that challenges beliefs must clear a higher bar than content that confirms them).
- Do models exhibit similar asymmetries or different ones?

## Why This Matters

- Understanding where model and human belief revision differ helps differentiate which aspects of model stance reversal are bugs (training artifacts to fix) versus features (human-like responses that may be appropriate or at least expected).
- Understanding the conditions in which people are persuaded/revise stance can help us understand whether models possess these rhetorical/persuasive capabilities.
- If models have this competence, they may be able to persuade people, potentially at scale.
- Models may be sensitive to rhetoric (not just typical sycophancy hacking).

## Next Steps

1. **Prompts for rhetorical vs literal stances**
   - (Stance A) — literal
   - (Stance A) — rhetorical
   - [may not be relevant] (Stance ¬A) — literal
   - [may not be relevant] (Stance ¬A) — rhetorical
   - Need range of points of view on Stance A

2. **Steering directions** — think about what directions to extract/apply

3. **FlipFlop datasets + relevant papers** — gather and share ✔️

4. **Publication venues** — look into humanities/social sciences journals

5. **Basic activation steering resources** — collect tutorials, repos, walkthroughs ✔️

## Resources

### Human Belief Revision & Epistemology

- ⭐ [Other Minds (Austin, 1946)](https://web.stanford.edu/~paulsko/papers/Austin_OM.pdf) - PDF
- ⭐ [Epistemic Vigilance (Sperber et al., 2010)](https://www.dan.sperber.fr/wp-content/uploads/2010_clement-et-al_epistemic-vigilance.pdf) - PDF
- [Common Ground (Stalnaker, 2002)](https://semantics.uchicago.edu/kennedy/classes/f07/pragmatics/stalnaker02.pdf) - PDF
- [John Langshaw Austin — Stanford Encyclopedia of Philosophy](https://plato.stanford.edu/entries/austin-jl/)
- ⭐ [Willard Van Orman Quine — Stanford Encyclopedia of Philosophy](https://plato.stanford.edu/entries/quine/)
- ⭐ [The Web of Belief (Quine et al., 1978)](https://emilkirkegaard.dk/en/wp-content/uploads/W.-V.-Quine-J.-S.-Ullian-The-Web-of-Belief.pdf) - PDF

### Rhetoric & Persuasion

- ⭐ [Richard Rorty, *Contingency, Irony, and Solidarity* (1989)](https://sites.pitt.edu/~rbrandom/Courses/Antirepresentationalism%20(2020)/Texts/rorty-contingency-irony-and-solidarity-1989.pdf) — PDF
- ⭐ [On the conversational persuasiveness of GPT-4 (Salvi et al., Nature 2025)](https://www.nature.com/articles/s41562-025-02194-6)
- ⭐ [Debating with More Persuasive LLMs Leads to More Truthful Answers](https://arxiv.org/abs/2402.06782)
- [Metaphor — Stanford Encyclopedia of Philosophy](https://plato.stanford.edu/entries/metaphor/)
- [Contradiction — Stanford Encyclopedia of Philosophy](https://plato.stanford.edu/entries/contradiction/)
- [Catachresis — Wikipedia](https://en.wikipedia.org/wiki/Catachresis)
- [Exformation — Wikiversity](https://en.wikiversity.org/wiki/Information)
- [Chiasmus — Wikipedia](https://en.wikipedia.org/wiki/Chiasmus)

### Sycophancy — Core Findings

- ⭐ [Towards Understanding Sycophancy in Language Models (Sharma et al., 2023)](https://arxiv.org/abs/2310.13548)
    - [Anthropic research page](https://www.anthropic.com/research/towards-understanding-sycophancy-in-language-models)
  
- ⭐ [Sycophancy to subterfuge: Investigating reward tampering in language models (Denison et al., 2024)](https://arxiv.org/abs/2406.10162)
    - [Anthropic research page](https://www.anthropic.com/research/reward-tampering)
### Stance Reversals & Challenge-Induced Flips

- ⭐ [Are You Sure? The FlipFlop Experiment (Laban et al., 2024)](https://arxiv.org/abs/2311.08596)
- [Ask Again, Then Fail (Xie et al., 2023/ACL 2024)](https://arxiv.org/abs/2310.02174)

### Social Conformity & Peer Pressure in Models

- [Disentangling the Drivers of LLM Social Conformity (Zhong et al., 2025)](https://arxiv.org/abs/2508.14918)
- [When Your AI Agent Succumbs to Peer-Pressure (Mehdizadeh & Hilbert, 2025)](https://arxiv.org/abs/2510.19107)
- [LLMs Can't Handle Peer Pressure / KAIROS (Song et al., 2025)](https://arxiv.org/abs/2508.18321)

### Metacognition & Dual-Process Thinking

- ⭐ [Metacognition for AI system safety (2022)](https://www.sciencedirect.com/science/article/pii/S0925753522000832)
- ⭐ [Fast, slow, and metacognitive thinking in AI (Nature, 2025)](https://www.nature.com/articles/s44387-025-00027-5)

### Calibration & Uncertainty

- [Can LLMs Express Their Uncertainty? (Xiong et al., ICLR 2024)](https://arxiv.org/abs/2306.13063)
- [Taming Overconfidence in LLMs: Reward Calibration in RLHF (Leng et al., ICLR 2025)](https://arxiv.org/abs/2410.09724)

### RLHF, Mode Collapse & Output Diversity

- ⭐ [Understanding the Effects of RLHF on LLM Generalisation and Diversity (Kirk et al., ICLR 2024)](https://openreview.net/pdf?id=PXD3FAVHJT)
- [Mysteries of Mode Collapse (LessWrong)](https://www.lesswrong.com/posts/t9svvNPNmFf5Qa3TA/mysteries-of-mode-collapse)
- [One fish, two fish, but not the whole sea (Murthy et al., NAACL 2025)](https://aclanthology.org/2025.naacl-long.561.pdf)

### Preference Learning — Background

- 🔖 [InstructGPT (Ouyang et al., 2022)](https://arxiv.org/abs/2203.02155)
- 🔖 [Direct Preference Optimization (Rafailov et al., 2023)](https://arxiv.org/abs/2305.18290)
- 🔖 [Deep RL from Human Preferences (Christiano et al., 2017)](https://arxiv.org/abs/1706.03741)

### Steering & Representation Engineering

- ⭐ [The Linear Representation Hypothesis (Park et al., 2023)](https://arxiv.org/abs/2311.03658)
- ⭐ [Activation Engineering (Turner et al., 2023)](https://arxiv.org/abs/2308.10248)
- ⭐ [Representation Engineering (2025)](https://arxiv.org/abs/2502.17601)
- [Improving Instruction-Following through Activation Steering (Stolfo et al., ICLR 2025)](https://arxiv.org/abs/2410.12877)
- [Activation Scaling for Steering and Interpreting Language Models (EMNLP 2024)](https://aclanthology.org/2024.findings-emnlp.479.pdf)
- [Modulating Sycophancy via Activation Steering (LessWrong)](https://www.lesswrong.com/posts/raoeNarFYCxxyKAop/modulating-sycophancy-in-an-rlhf-model-via-activation)

### Targeted Sycophancy Mitigation

- [From Yes-Men to Truth-Tellers: Pinpoint Tuning (Chen et al., 2024)](https://arxiv.org/abs/2409.01658)

### Intelligence, Creativity & Diversity

- ⭐ [On the Measure of Intelligence (Chollet, 2019)](https://arxiv.org/abs/1911.01547)
- [Towards Benchmarking LLM Diversity & Creativity (Gwern)](https://gwern.net/creative-benchmark)

### Benchmarks & Evaluation Suites
- [TruthfulQA (Lin, Hilton, Evans, 2021)](https://arxiv.org/abs/2109.07958)
  - [Benchmark repo](https://github.com/sylinrl/TruthfulQA)
- [Sycophancy Eval](https://github.com/meg-tong/sycophancy-eval/blob/main/README.md)
- [SYCON-Bench (Hong et al., 2025)](https://arxiv.org/abs/2505.23840)
  - [Code/data repo](https://github.com/JiseungHong/SYCON-Bench)
- [GASLIGHTBENCH (Cui et al., 2025)](https://openreview.net/forum?id=0BYRYwGCbK)
- [MultiChallenge (2025)](https://arxiv.org/abs/2501.17399)
  - [ACL Anthology](https://aclanthology.org/2025.findings-acl.958/)

## Tools & Demos

- [Neuronpedia](https://www.neuronpedia.org)
- [Eiffel Tower Llama Demo](https://huggingface.co/spaces/dlouapre/eiffel-tower-llama)
- [Extracting Concepts from LLMs (HuggingFace blog)](https://huggingface.co/blog/m-ric/extracting-concepts-from-llms)
- [Llama3-Instruct code GitHub](https://github.com/donkeyanaphora/STEERING_EXPERIMENTS/blob/main/notebooks/llama_causal_probe.ipynb)

## Legend

- ⭐ = High priority / foundational
- 🔖 = Background / reference
