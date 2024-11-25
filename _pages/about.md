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

I am broadly interested in **reasoning**. In the realm of reasoning, I've worked on complicated problems like:
- **Theorem proving and Logical reasoning** that uses theorem prover [Lean](https://lean-lang.org/) to help with the reasoning process <a href="/publications/#lean">[1]</a> 
- **Decompositional entailment** that formulates a consistent and theoretically grounded approach to annotating decompositional entailment dataset <a href="/publications/#decompos">[2]</a>

However, one puzzling limitation in LLM reasoning is that while these models can solve “superhuman” problems in specific domains, they often fail at simple tasks. This observation led me to question whether LLMs’ problem-solving abilities truly demonstrate superior reasoning capabilities or simply reflect domain-specific overspecialization. As a result, my focus has now turned to the more general, system-2-like reasoning. My work in this area includes:
- **Building general-purpose verifier** through rationale extraction from unlabelled data to provide process supervision during reasoning <a href="/publications/#supervision">[3]</a>
- **Investigating the effectiveness of CoT prompting** across 100+ papers and 20 datasets and discovering CoT benefits mainly math/symbolic reasoning tasks <a href="/publications/#cot">[4]</a>

I'm also interested in the **self-improvement** capability of LLMs. If we begin with the “end” (superintelligence/AGI) in mind, relying on human input won't get us there. We need to teach models to interact with the environment and self-improve. Specifically, I've worked on:
- **Understanding the reason** that prevents LLM from effective self-improvement <a href="/publications/#self-[in]correct">[5]</a>
- **Probing the limits** of self-improvement

I believe these two research directions are deeply interconnected and can synergistically enhance each other. Strong reasoning capabilities are essential for effective self-improvement, as models need to logically analyze and discriminate between good and bad generations to provide meaningful feedback. Conversely, self-improvement mechanisms are crucial for advancing reasoning capabilities, as complex logical problems often require multiple attempts and refinements to reach the correct solution. This bidirectional relationship suggests that advancing either area could create positive feedback loops that benefit both capabilities.

In addition, my research has frequently drawn inspiration from cognitive science concepts, including [cognitive load](https://en.wikipedia.org/wiki/Cognitive_load), [system 2 reasoning](https://en.wikipedia.org/wiki/Dual_process_theory), and [zone of proximal development](https://en.wikipedia.org/wiki/Zone_of_proximal_development). This connection seems natural, given that LLMs are fundamentally trained to emulate human cognitive patterns. I would love to explore this intersection more deeply in future research.
