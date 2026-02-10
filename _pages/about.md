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

I am currently working on **reinforcement learning** and **autonomous agents**, particularly the intersection of these two areas — using RL to train agentic models. One area I'm particularly focusing on is <a href="https://aws.amazon.com/security-agent/">security agents</a> that can autonomously identify and validate vulnerabilities.

I'm also broadly interested in **reasoning**. In the realm of reasoning, I've worked on:

<ul><li><strong>Building general-purpose verifier</strong> through rationale extraction from unlabelled data to provide process supervision during reasoning <a href="/publications/#supervision">[1]</a> (mentioned in Lilian Weng's <a href="https://bit.ly/44ChA3B">blog</a>)</li></ul>
<ul><li><strong>Investigating the effectiveness of CoT prompting</strong> across 100+ papers and 20 datasets and discovering CoT benefits mainly math/symbolic reasoning tasks <a href="/publications/#cot">[2]</a> (<a href="https://bit.ly/4lLMnSy">discussion</a> with Jason Wei)</li></ul>
<ul><li><strong>Theorem proving and Logical reasoning</strong> that uses theorem prover <a href="https://lean-lang.org/">Lean</a> to help with the reasoning process <a href="/publications/#lean">[3]</a></li></ul>
<ul><li><strong>Decompositional entailment</strong> that formulates a consistent and theoretically grounded approach to annotating decompositional entailment dataset <a href="/publications/#decompos">[4]</a></li></ul>


Another area I'm interested in is the **self-improvement** capability of LLMs (and LLM agents). If we begin with the "end" (superintelligence/AGI) in mind, relying on human input won't get us there. We need to teach models to interact with the environment and self-improve. Within this area, I've worked on:

<ul><li><strong>Understanding the reason</strong> that prevents LLM from effective self-improvement <a href="/publications/#self-[in]correct">[5]</a></li></ul>
<ul><li><strong>Probing the limits</strong> of self-improvement even with high-quality feedback <a href="/publications/#friction">[6]</a></li></ul>


<div class="collapsible-section">
  <div class="collapsible-header" onclick="toggleSection('research-philosophy-details')">
    <span class="toggle-icon" id="research-philosophy-details-icon">▶</span>
    <strong>More about my research</strong>
  </div>
  <div class="collapsible-content" id="research-philosophy-details" style="display: none;">
    <p>I believe reasoning and self-improvement are <strong>deeply interconnected</strong> and can synergistically enhance each other. Strong reasoning capabilities are essential for effective self-improvement, as models need to logically analyze and discriminate between good and bad generations to provide meaningful feedback. Conversely, self-improvement mechanisms are crucial for advancing reasoning capabilities, as complex logical problems often require multiple attempts and refinements to reach the correct solution. This bidirectional relationship suggests that advancing either area could create positive feedback loops that benefit both capabilities.</p>
    
    <p>I'm also interested in pursuing research in <strong>multi-modal systems</strong>, which builds upon my previous experience in speech processing and my current expertise in LLMs. The convergence of different modalities presents exciting opportunities for building stronger AI systems.</p>
  </div>
</div>
