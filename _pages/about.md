---
layout: about

title: About
permalink: /
subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

profile:
  align: left
  image: professional_reflection.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>555 your office number</p>
    <p>123 your address street</p>
    <p>Your City, State 12345</p>


news: false # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
more: false

research_interest: Research Interest
more_title: More About Me
---

Nowadays, I'm increasingly interested in the **fundamental limitations** of language models. Is autoregressive prediction really the best architecture? Do we truly need massive datasets when humans learn from far fewer examples? How can we bridge the training-inference gap when models must generalize to out-of-domain environments far beyond what they've seen during training? If you're also thinking about these problems, I'd love to <a href="https://calendar.app.google/BewYXJYPcTGveKRX6">chat</a>!

I've worked extensively on **agents**, **reasoning**, and **self-improvement**:

**Agents**: I've worked on agentic RL and <a href="https://aws.amazon.com/security-agent/">security agents</a> that can autonomously identify and validate vulnerabilities.

**Reasoning**: In the realm of reasoning, I've worked on:

<ul><li><strong>Building general-purpose verifier</strong> through rationale extraction from unlabelled data to provide process supervision during reasoning <a href="/publications/#supervision">[1]</a> (mentioned in Lilian Weng's <a href="https://bit.ly/44ChA3B">blog</a>)</li></ul>
<ul><li><strong>Investigating the effectiveness of CoT prompting</strong> across 100+ papers and 20 datasets and discovering CoT benefits mainly math/symbolic reasoning tasks <a href="/publications/#cot">[2]</a> (<a href="https://bit.ly/4lLMnSy">discussion</a> with Jason Wei)</li></ul>
<ul><li><strong>Theorem proving and Logical reasoning</strong> that uses theorem prover <a href="https://lean-lang.org/">Lean</a> to help with the reasoning process <a href="/publications/#lean">[3]</a></li></ul>
<ul><li><strong>Decompositional entailment</strong> that formulates a consistent and theoretically grounded approach to annotating decompositional entailment dataset <a href="/publications/#decompos">[4]</a></li></ul>

**Self-improvement**: If we begin with the "end" (superintelligence/AGI) in mind, relying on human input won't get us there. We need to teach models to interact with the environment and self-improve. Within this area, I've worked on:

<ul><li><strong>Understanding the reason</strong> that prevents LLM from effective self-improvement <a href="/publications/#self-[in]correct">[5]</a></li></ul>
<ul><li><strong>Probing the limits</strong> of self-improvement even with high-quality feedback <a href="/publications/#friction">[6]</a></li></ul>
