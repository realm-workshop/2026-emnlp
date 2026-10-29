---
layout: page
permalink: /schedule/
title: Schedule
description:
nav: true
nav_order: 5
_styles: |
  .poster-board-notice {
    margin: 0 0 1.5rem;
    padding: 0.75rem 1rem;
    border: 1px solid var(--global-divider-color);
    border-left: 4px solid var(--global-theme-color);
    border-radius: 4px;
    background: var(--global-card-bg-color);
  }
  .poster-board-notice > strong {
    color: var(--global-theme-color);
  }
  .poster-board-notice li strong {
    color: var(--global-text-color);
  }
  .talk-abstract-box {
    min-width: 0;
    margin: 0.5rem 0 0;
    padding: 0.5rem 1rem 0.75rem;
    border: 1px dashed var(--global-text-color);
    border-radius: 4px;
  }
  .talk-abstract-box legend {
    float: none;
    width: auto;
    margin: 0;
    padding: 0 0.4rem;
    font-size: 0.9rem;
    font-weight: 600;
    line-height: inherit;
  }
  .talk-abstract-toggle .talk-abstract-icon {
    display: inline-block;
    transition: transform 0.15s ease;
  }
  .talk-abstract-toggle[aria-expanded="true"] .talk-abstract-icon {
    transform: rotate(90deg);
  }
  @media (prefers-reduced-motion: reduce) {
    .talk-abstract-toggle .talk-abstract-icon {
      transition: none;
    }
  }
---

**Date:** Oct 29, 2026

**Location:** HUNGEXPO Budapest Congress & Exhibition Center ([map](https://maps.app.goo.gl/JMeQhyWTkoKJUMqE6))

**Room:** P1

<aside class="poster-board-notice" aria-label="Poster board assignments">
  <strong>Assigned poster boards</strong><br>
  Sections <b>6 and 7</b> &middot; Boards <b>251–315</b>
  <ul class="mt-2 mb-0 pl-3" style="font-size: 0.875em;">
    <li><strong>Board selection:</strong> Use any available board within the assigned range.</li>
    <li><strong>Setup:</strong> Begin no earlier than 15 minutes before your session.</li>
    <li>Posters left unattended at the end of a session may be removed. Staff and volunteers are not responsible for unattended items.</li>
    <li>Poster presentations must conclude promptly at the scheduled end time.</li>
  </ul>
</aside>

## Program Schedule

<table class="table table-borderless" style="width: 100%;">
  <thead>
    <tr>
      <th class="border-bottom border-2 pb-2 px-2" style="text-align: left; white-space: nowrap; min-width: 110px;">Time</th>
      <th class="border-bottom border-2 pb-2 px-2" style="text-align: left;">Event</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="py-2 px-2" style="white-space: nowrap; min-width: 110px;">09:15 - 09:30</td>
      <td class="py-2 px-2">Opening Remarks</td>
    </tr>
    <tr>
      <td class="py-2 px-2" style="vertical-align: top; white-space: nowrap; min-width: 110px;">09:30 - 10:00</td>
      <td class="py-2 px-2">Invited Talk 1: <strong>Baptiste Rozière</strong><br>
        <a class="talk-abstract-toggle" href="#invited-talk-1-abstract" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="invited-talk-1-abstract" title="Show or hide abstract"><span class="talk-abstract-icon" aria-hidden="true">▸</span>&nbsp;<em>Building code models: scale and beyond</em></a>
        <div class="collapse" id="invited-talk-1-abstract">
          <fieldset class="talk-abstract-box">
            <legend>Abstract</legend>
            <p>Code agents have made remarkable progress in the past few months, and much of that progress is directly due to scale: more compute and data have saturated benchmarks once considered nearly impossible. It could be tempting to believe that scaling is the only thing that matters and that nothing can be achieved by small teams with limited compute. Yet, code agents remain surprisingly fragile, sometimes failing on seemingly easy issues, or producing code that falls short of production quality standards.</p>
            <p class="mb-0">In this talk, we will first explore how scaling is done in practice at companies such as Mistral. Afterwards, we will discuss the types of issues that pure scaling will not solve and where resource-constrained teams are well positioned to make impactful contributions.</p>
          </fieldset>
        </div>
      </td>
    </tr>
    <tr>
      <td class="py-2 px-2" style="vertical-align: top; white-space: nowrap; min-width: 110px;">10:00 - 10:30</td>
      <td class="py-2 px-2">Oral presentations (10 min each)<br>
        <span style="display:block; margin-left:1.5em;"><strong>Sina Hajimiri:</strong> <em style="font-size:0.9em;">Are Online Skill and Memory Modules Always Worth Their Tokens? A Budget-Constrained Study of Web&nbsp;Agents</em></span>
        <span style="margin-left:1.5em;"><strong>Youmna Farag:</strong> <em>CAPSafe: A Benchmark for Contextual Action and Plan Safety Reasoning in Embodied Agents</em></span><br>
        <span style="margin-left:1.5em;"><strong>Luyang Zhang:</strong> <em>Agents Repair — or Just Reply? Public Correction in Deployed Agent Forums</em></span><br>
      </td>
    </tr>
    <tr style="background-color: #e9ecef;">
      <td class="py-2 px-2" style="white-space: nowrap; min-width: 110px;"><strong>10:30 - 11:30</strong></td>
      <td class="py-2 px-2"><strong>Coffee Break & Poster session 1</strong></td>
    </tr>
    <tr>
      <td class="py-2 px-2" style="vertical-align: top; white-space: nowrap; min-width: 110px;">11:30 - 12:00</td>
      <td class="py-2 px-2">Oral presentations (10 min each)<br>
        <span style="margin-left:1.5em;"><strong>Bardia Mohammadi:</strong> <em>The Working Set of a Coding Agent: Coherence Debt in Repository-Scale Tasks</em></span><br>
        <span style="margin-left:1.5em;"><strong>Jing-Jing Li:</strong> <em>STAC: When Innocent Tools Form Dangerous Chains for LLM Agents</em></span><br>
        <span style="margin-left:1.5em;"><strong>Muhammad Saadat:</strong> <em>Causal Decomposition of LLM Agent Failure via Oracle-State Intervention</em></span><br>
      </td>
    </tr>
    <tr>
      <td class="py-2 px-2" style="vertical-align: top; white-space: nowrap; min-width: 110px;">12:00 - 12:30</td>
      <td class="py-2 px-2">Invited Talk 2: <strong>Maria Brbić</strong><br>
        <em>AI Agents for Open-Ended Scientific Discovery</em>
      </td>
    </tr>
    <tr>
      <td class="py-2 px-2" style="vertical-align: top; white-space: nowrap; min-width: 110px;">12:30 - 13:00</td>
      <td class="py-2 px-2">Invited Talk 3: <strong>Marc-Alexandre Côté</strong><br>
        <a class="talk-abstract-toggle" href="#invited-talk-3-abstract" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="invited-talk-3-abstract" title="Show or hide abstract"><span class="talk-abstract-icon" aria-hidden="true">▸</span>&nbsp;<em>TALES: What text adventures reveal about dependable, long-horizon agents</em></a>
        <div class="collapse" id="invited-talk-3-abstract">
          <fieldset class="talk-abstract-box">
            <legend>Abstract</legend>
            <p class="mb-0">When an agent fails, was it the planning or the interface? TALES tests this with 122 text-adventure tasks, one minimal prompt for every model, and detectors that attribute failures to specific skills. While synthetic text worlds are nearly solved, human-written games are still providing some challenges. Interestingly, we found that coding agents show the same failures: repeating failed commands, acting on stale state, losing the overall goal.</p>
          </fieldset>
        </div>
      </td>
    </tr>
    <tr style="background-color: #e9ecef;">
      <td class="py-2 px-2" style="white-space: nowrap; min-width: 110px;"><strong>13:00 - 14:00</strong></td>
      <td class="py-2 px-2"><strong>Lunch Break</strong></td>
    </tr>
    <tr>
      <td class="py-2 px-2" style="white-space: nowrap; min-width: 110px;">14:00 - 14:30</td>
      <td class="py-2 px-2">Invited Talk 4: <strong>Graham Neubig</strong><br>
        <a class="talk-abstract-toggle" href="#invited-talk-4-abstract" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="invited-talk-4-abstract" title="Show or hide abstract"><span class="talk-abstract-icon" aria-hidden="true">▸</span>&nbsp;<em>Recursive Agent Optimization</em></a>
        <div class="collapse" id="invited-talk-4-abstract">
          <fieldset class="talk-abstract-box">
            <legend>Abstract</legend>
            <p class="mb-0">In this talk, I will introduce Recursive Agent Optimization (RAO), a reinforcement learning approach for training recursive agents: agents that can spawn and delegate sub-tasks to new instantiations of themselves recursively. Recursive agents implement an inference-time scaling algorithm that naturally allows agents to scale to longer contexts and generalize to more difficult problems via divide-and-conquer. RAO provides a method to train models to best take advantage of such recursive inference, teaching agents when and how to delegate and communicate. We find that recursive agents trained in this way enjoy better training efficiency, can scale to tasks that go beyond the model's context window, generalize to tasks much harder than the ones the agent was trained on, and can enjoy reduced wall-clock time compared to single-agent systems.</p>
          </fieldset>
        </div>
      </td>
    </tr>
    <tr>
      <td class="py-2 px-2" style="vertical-align: top; white-space: nowrap; min-width: 110px;">14:30 - 15:00</td>
      <td class="py-2 px-2">Invited Talk 5: <strong>Perouz Taslakian</strong><br>
        <a class="talk-abstract-toggle" href="#invited-talk-5-abstract" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="invited-talk-5-abstract" title="Show or hide abstract"><span class="talk-abstract-icon" aria-hidden="true">▸</span>&nbsp;<em>What Agents Reveal: When helpful agents share too much</em></a>
        <div class="collapse" id="invited-talk-5-abstract">
          <fieldset class="talk-abstract-box">
            <legend>Abstract</legend>
            <p>AI agents increasingly access our emails, calendars, and private data, search the web, and coordinate with other agents on our behalf. Each action involves a decision about what information to reveal, to whom, and for what purpose. Yet privacy failures often arise not from malicious attacks, but from helpful agents sharing information in the wrong context.</p>
            <p class="mb-0">In this talk, I frame agent privacy through the lens of contextual integrity: information flows should respect the norms of the contexts in which they occur. I will present three benchmarks that expose distinct gaps in current evaluations. <strong>MosaicLeaks</strong> reveals how seemingly harmless tool calls can collectively leak sensitive information. <strong>PiSAs</strong> examines privacy in shared agent environments, where leaks can occur through agent communication and memory. <strong>PrivacyAlign</strong> uses human judgments to evaluate and train agents to avoid both oversharing and unnecessary withholding. Together, these benchmarks offer a practical path toward building agents that are both capable and privacy-aware.</p>
          </fieldset>
        </div>
      </td>
    </tr>
    <tr>
      <td class="py-2 px-2" style="vertical-align: top; white-space: nowrap; min-width: 110px;">15:00 - 15:30</td>
      <td class="py-2 px-2">Invited Talk 6: <strong>Vishrav Chaudhary</strong><br>
        <a class="talk-abstract-toggle" href="#invited-talk-6-abstract" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="invited-talk-6-abstract" title="Show or hide abstract"><span class="talk-abstract-icon" aria-hidden="true">▸</span>&nbsp;<em>Evaluating Multilingual AI Agents as End-to-End Systems</em></a>
        <div class="collapse" id="invited-talk-6-abstract">
          <fieldset class="talk-abstract-box">
            <legend>Abstract</legend>
            <p class="mb-0">AI agents are increasingly expected to plan, search, use tools, and recover from errors for users across languages and regions. Yet most agent benchmarks remain English-first, while translated evaluations often miss failures involving local entities, conventions, tools, and cultural context. This talk surveys emerging multilingual agentic benchmarks, examines where language-dependent failures arise, and discusses limitations in translation, localization, and evaluator validity. The motivation is to develop more diagnostic evaluations that separate linguistic competence from planning, tool execution, retrieval, recovery, and real-world task success.</p>
          </fieldset>
        </div>
      </td>
    </tr>
    <tr style="background-color: #e9ecef;">
      <td class="py-2 px-2" style="white-space: nowrap; min-width: 110px;"><strong>15:30 - 16:30</strong></td>
      <td class="py-2 px-2"><strong>Coffee Break & Poster session 2</strong></td>
    </tr>
  </tbody>
</table>
