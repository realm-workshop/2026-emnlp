---
layout: page
permalink: /invited_talks/
title: Invited Talks
description: Thursday, October 29, 2026 · All times are local to Budapest.
nav: true
nav_order: 4
_styles: |
  .invited-talk {
    display: grid;
    grid-template-columns: 180px minmax(0, 1fr);
    gap: 1.5rem;
    padding: 2rem 0;
    border-bottom: 1px solid var(--global-divider-color);
    scroll-margin-top: 6rem;
  }
  .invited-talk:first-child {
    padding-top: 0;
  }
  .invited-talk:last-child {
    border-bottom: 0;
  }
  .invited-talk-photo {
    width: 180px;
    height: 180px;
    object-fit: cover;
    border-radius: 4px;
  }
  .invited-talk h2 {
    margin-top: 0;
    font-size: 1.5rem;
  }
  .invited-talk-title {
    font-size: 1.25rem;
    font-weight: 700;
    line-height: 1.4;
    margin-bottom: 1rem;
  }
  .invited-talk h3 {
    font-size: 1rem;
    font-weight: 600;
    margin-top: 1.5rem;
  }
  @media (max-width: 575.98px) {
    .invited-talk {
      grid-template-columns: minmax(0, 1fr);
      gap: 1rem;
    }
  }
---

<section class="invited-talk" id="baptiste-roziere" aria-labelledby="baptiste-roziere-name">
  <a href="https://fr.linkedin.com/in/baptisteroziere">
    <img class="invited-talk-photo" src="{{ '/assets/img/speakers/baptiste.jpg' | relative_url }}" alt="Baptiste Rozière" width="180" height="180" loading="lazy">
  </a>
  <div>
    <h2 id="baptiste-roziere-name"><a href="https://fr.linkedin.com/in/baptisteroziere">Baptiste Rozière</a></h2>
    <p class="mb-1">Mistral AI</p>
    <p class="text-muted">09:30–10:00</p>
    <p class="invited-talk-title">Building code models: scale and beyond</p>
    <h3>Abstract</h3>
    <p>Code agents have made remarkable progress in the past few months, and much of that progress is directly due to scale: more compute and data have saturated benchmarks once considered nearly impossible. It could be tempting to believe that scaling is the only thing that matters and that nothing can be achieved by small teams with limited compute. Yet, code agents remain surprisingly fragile, sometimes failing on seemingly easy issues, or producing code that falls short of production quality standards.</p>
    <p>In this talk, we will first explore how scaling is done in practice at companies such as Mistral. Afterwards, we will discuss the types of issues that pure scaling will not solve and where resource-constrained teams are well positioned to make impactful contributions.</p>
    <h3>Bio</h3>
    <p>Baptiste leads the code generation team at Mistral AI. Previously, he was a research scientist at Meta AI in Paris working on Code Generation. He contributed to Llama and led Code Llama.<br>
    During his PhD at Meta AI and Université Paris Dauphine, Baptiste conducted research on unsupervised translation of programming languages and model pre-training for code. His work was featured in dozens of news articles in more than ten languages.</p>
  </div>
</section>

<section class="invited-talk" id="maria-brbic" aria-labelledby="maria-brbic-name">
  <a href="https://brbiclab.epfl.ch/team/">
    <img class="invited-talk-photo" src="{{ '/assets/img/speakers/maria.jpg' | relative_url }}" alt="Maria Brbić" width="180" height="180" loading="lazy">
  </a>
  <div>
    <h2 id="maria-brbic-name"><a href="https://brbiclab.epfl.ch/team/">Maria Brbić</a></h2>
    <p class="mb-1">EPFL</p>
    <p class="text-muted">12:00–12:30</p>
    <p class="invited-talk-title">AI Agents for Open-Ended Scientific Discovery</p>
    <h3>Bio</h3>
    <p><strong>Maria Brbić</strong> is an Assistant Professor of Computer Science and Life Sciences at EPFL. She is affiliated with the <a href="https://ai.epfl.ch/"><strong>EPFL AI Center</strong></a> and the <a href="https://www.epfl.ch/research/domains/bioengineering/"><strong>EPFL Institute of Bioengineering</strong></a>. Maria is a <a href="https://cifar.ca/research-programs/cifar-macmillan-multiscale-human/"><strong>CIFAR Fellow</strong></a> in the Multiscale Human Program. Her research bridges AI and biology, focusing on developing new AI methods that drive advances in biology and biomedicine.</p>
    <p>Prior to joining the EPFL faculty in 2022, Maria was a postdoctoral fellow at Stanford University, Department of Computer Science, where she worked with Jure Leskovec. She was a member of the Chan Zuckerberg Biohub at Stanford. Maria received her Ph.D. from the University of Zagreb in 2019, earning an Outstanding Thesis Award. During her PhD, she also conducted research at Stanford University as a Fulbright Scholar. Among other recognitions, she was named a Rising Star in EECS by MIT in 2021, received an Early Career Award from SIB in 2023, and was awarded the SNSF Starting Grant in 2024. Maria is an ELLIS Scholar.</p>
  </div>
</section>

<section class="invited-talk" id="marc-alexandre-cote" aria-labelledby="marc-alexandre-cote-name">
  <a href="https://www.microsoft.com/en-us/research/people/macote/">
    <img class="invited-talk-photo" src="{{ '/assets/img/speakers/marc_alexandre_cote.jpeg' | relative_url }}" alt="Marc-Alexandre Côté" width="180" height="180" loading="lazy">
  </a>
  <div>
    <h2 id="marc-alexandre-cote-name"><a href="https://www.microsoft.com/en-us/research/people/macote/">Marc-Alexandre Côté</a></h2>
    <p class="mb-1">Microsoft Research</p>
    <p class="text-muted">12:30–13:00</p>
    <p class="invited-talk-title">TALES: What text adventures reveal about dependable, long-horizon agents</p>
    <h3>Abstract</h3>
    <p>When an agent fails, was it the planning or the interface? TALES tests this with 122 text-adventure tasks, one minimal prompt for every model, and detectors that attribute failures to specific skills. While synthetic text worlds are nearly solved, human-written games are still providing some challenges. Interestingly, we found that coding agents show the same failures: repeating failed commands, acting on stale state, losing the overall goal.</p>
    <h3>Bio</h3>
    <p>Marc-Alexandre Côté is a Principal Research Manager at MSR Montréal. His research focuses on reinforcement learning and language agents, with an emphasis on building interactive environments like TextWorld that make it possible to study how agents learn, plan, gather information, and act over long horizons. More recently, with the MSR Montréal Froggy team, they released FrogNano, a 4B coding agent trained through RL on synthetically generated software-engineering tasks, showing how adaptive environments and task generation can enable capable, efficient agents without traditional distillation.</p>
  </div>
</section>

<section class="invited-talk" id="graham-neubig" aria-labelledby="graham-neubig-name">
  <a href="https://www.phontron.com/">
    <img class="invited-talk-photo" src="{{ '/assets/img/speakers/graham.jpg' | relative_url }}" alt="Graham Neubig" width="180" height="180" loading="lazy">
  </a>
  <div>
    <h2 id="graham-neubig-name"><a href="https://www.phontron.com/">Graham Neubig</a></h2>
    <p class="mb-1">Carnegie Mellon University / OpenHands</p>
    <p class="text-muted">14:00–14:30</p>
    <p class="invited-talk-title">Recursive Agent Optimization</p>
    <h3>Abstract</h3>
    <p>In this talk, I will introduce Recursive Agent Optimization (RAO), a reinforcement learning approach for training recursive agents: agents that can spawn and delegate sub-tasks to new instantiations of themselves recursively. Recursive agents implement an inference-time scaling algorithm that naturally allows agents to scale to longer contexts and generalize to more difficult problems via divide-and-conquer. RAO provides a method to train models to best take advantage of such recursive inference, teaching agents when and how to delegate and communicate. We find that recursive agents trained in this way enjoy better training efficiency, can scale to tasks that go beyond the model's context window, generalize to tasks much harder than the ones the agent was trained on, and can enjoy reduced wall-clock time compared to single-agent systems.</p>
    <h3>Bio</h3>
    <p>Graham Neubig is an associate professor at the Language Technologies Institute of Carnegie Mellon University and Chief Scientist at OpenHands. His research focuses on large language models, including both fundamental advances in model capabilities and applications to tasks such as software development. His final goal is that every person in the world should be able to communicate with each-other, and with computers in their own language. He also contributes to making NLP research more accessible through open publishing of research papers, advanced NLP course materials and video lectures, and open-source software, all of which are available on his web site.</p>
  </div>
</section>

<section class="invited-talk" id="perouz-taslakian" aria-labelledby="perouz-taslakian-name">
  <a href="https://perouz.github.io/">
    <img class="invited-talk-photo" src="{{ '/assets/img/speakers/perouz.jpg' | relative_url }}" alt="Perouz Taslakian" width="180" height="180" loading="lazy">
  </a>
  <div>
    <h2 id="perouz-taslakian-name"><a href="https://perouz.github.io/">Perouz Taslakian</a></h2>
    <p class="mb-1">McGill University / Mila</p>
    <p class="text-muted">14:30–15:00</p>
    <p class="invited-talk-title">What Agents Reveal: When helpful agents share too much</p>
    <h3>Abstract</h3>
    <p>AI agents increasingly access our emails, calendars, and private data, search the web, and coordinate with other agents on our behalf. Each action involves a decision about what information to reveal, to whom, and for what purpose. Yet privacy failures often arise not from malicious attacks, but from helpful agents sharing information in the wrong context.</p>
    <p>In this talk, I frame agent privacy through the lens of contextual integrity: information flows should respect the norms of the contexts in which they occur. I will present three benchmarks that expose distinct gaps in current evaluations. <strong>MosaicLeaks</strong> reveals how seemingly harmless tool calls can collectively leak sensitive information. <strong>PiSAs</strong> examines privacy in shared agent environments, where leaks can occur through agent communication and memory. <strong>PrivacyAlign</strong> uses human judgments to evaluate and train agents to avoid both oversharing and unnecessary withholding. Together, these benchmarks offer a practical path toward building agents that are both capable and privacy-aware.</p>
    <h3>Bio</h3>
    <p>Perouz Taslakian is a Principal Research Scientist at ServiceNow AI Research, an Adjunct Professor at McGill University, and an Associate Industry Member at Mila. Her research focuses on building capable and trustworthy AI systems, with an emphasis on LLM agents and multimodal learning. Her recent work investigates how to improve agent capabilities while addressing challenges in privacy, safety, and alignment.</p>
  </div>
</section>

<section class="invited-talk" id="vishrav-chaudhary" aria-labelledby="vishrav-chaudhary-name">
  <a href="https://www.linkedin.com/in/vishrav">
    <img class="invited-talk-photo" src="{{ '/assets/img/speakers/vishrav.jpg' | relative_url }}" alt="Vishrav Chaudhary" width="180" height="180" loading="lazy">
  </a>
  <div>
    <h2 id="vishrav-chaudhary-name"><a href="https://www.linkedin.com/in/vishrav">Vishrav Chaudhary</a></h2>
    <p class="mb-1">Meta Superintelligence Labs</p>
    <p class="text-muted">15:00–15:30</p>
    <p class="text-muted">Talk title forthcoming.</p>
    <h3>Bio</h3>
    <p class="text-muted">Bio forthcoming.</p>
  </div>
</section>

