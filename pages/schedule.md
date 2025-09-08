---
layout: page
title: Programme
---

## Schedule

<style>
  /* let this page use the full viewport width */
  .container-md { max-width: none; }

  /* scrolling only when the table is wider than the viewport */
  .schedule-outer {
    width: 100%;
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
  }

  .schedule-wrap { margin: 0 auto; }

  .schedule-wrap table {
    /* size to fit its content; expands on wide screens */
    width: max-content;
    table-layout: auto;        /* allow columns to grow to content */
    border-collapse: separate;
    border-spacing: 0;
  }

  .schedule-wrap th,
  .schedule-wrap td {
    padding: .65rem .9rem;
    vertical-align: middle;
    /*white-space: nowrap*/       /* <<< keep everything on ONE LINE */
    overflow: visible;         /* show full content */
    text-overflow: clip;       /* no ellipsis */
  }

  /* sensible baseline widths; tweak if you like */
  .schedule-wrap col.time      { width: 12ch; }   /* e.g., “10:55–11:35” */
  .schedule-wrap col.day-col   { width: 42ch; }   /* enough for long titles */
</style>



<div class="schedule-outer">
  <div class="schedule-wrap">
    <table>
      <!-- set explicit column widths -->
      <colgroup class="schedule-wrap">
  <col class="time">
  <col class="day-col">
  <col class="day-col">
  <col class="day-col">
</colgroup>
      <thead>
        <tr>
          <th>Time</th>
          <th>8 September</th>
          <th>9 September</th>
          <th>10 September</th>
        </tr>
      </thead>
      <tbody>
    <tr>
      <td>8:30–9:30</td>
      <td>Registration</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>9:30–9:45</td>
      <td>Opening Remarks</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>9:45–10:25</td>
      <td> <a href="{{ '/pages/speakers/baldassarre' | relative_url }}"
     title="Gianluca Baldassarre - Open‑Ended Learning Robots: From the Purpose Alignment Framework to a Purpose-Biased Model">
     Gianluca Baldassarre - "Open‑Ended Learning Robots: From the Purpose Alignment Framework to a Purpose-Biased Model"
     </a>
     </td>
      <td> <a href="{{ '/pages/speakers/guckelsberger' | relative_url }}"
     title="Christian Guckelsberger - Creativity & Intrinsically Motivated, Open-Ended Learning: Three Roads to Surprise">
      Christian Guckelsberger - "Creativity & Intrinsically Motivated, Open-Ended Learning: Three Roads to Surprise"
      </a>
      </td>
      <td> <a href="{{ '/pages/speakers/braendle' | relative_url }}"
     title="Franziska Braendle - Understanding Fun: Using Video Games to Study Intrinsic Motivation">
      Franziska Braendle - "Understanding Fun: Using Video Games to Study Intrinsic Motivation"
      </a>
      </td>
    </tr>
    <tr>
      <td>10:25–10:55</td>
      <td>Coffee Break</td>
      <td>Coffee Break</td>
      <td>Coffee Break</td>
    </tr>
    <tr>
      <td>10:55–11:35</td>
      <td> <a href="{{ '/pages/speakers/rocktaeschel' | relative_url }}"
     title="Tim Rocktäschel — Open-Endedness and World Models">
     Tim Rocktäschel - "Open-Endedness and World Models"
     </a>
     </td>
      <td> <a href="{{ '/pages/speakers/foerster' | relative_url }}"
     title="Jakob Foerster - Reinforcement Learning at the Hyperscale">
      Jakob Foerster - "Reinforcement Learning at the Hyperscale"
      </a>
      </td>
      <td> <a href="{{ '/pages/speakers/herrmann' | relative_url }}"
     title="Michael Herrmann - The emotional underpinnings of self-motivated learning">
      Michael Herrmann - "The emotional underpinnings of self-motivated learning"
      </a>
      </td>
    </tr>
    <tr>
      <td>11:35–11:45</td>
      <td> <a href="{{ '/assets/abstracts/CT1.pdf' | relative_url }}" target="_blank"
     title="Abstract: Thomas Carta - HERAKLES">
      Contributed Talk: Thomas Carta - "HERAKLES: Hierarchical Skill Compilation for Open-ended LLM Agents" 
      </a>
      </td>
      <td> <a href="{{ '/assets/abstracts/CT4.pdf' | relative_url }}" target="_blank"
     title="Abstract: Émiland Garrabé - Open-ended">
      Contributed Talk: Émiland Garrabé - "Open-ended planning and grasping for robotic manipulation tasks using lightweight LLMs"
      </a>
      </td>
      <td rowspan="3">Closing Remarks</td>
    </tr>
    <tr>
      <td>11:45–11:55</td>
      <td> <a href="{{ '/assets/abstracts/CT2.pdf' | relative_url }}" target="_blank"
     title="Abstract: Oliver Obst - Empowerment under Uncertainty">
      Contributed Talk: Oliver Obst - "Empowerment under Uncertainty: Approximate Bayesian Exploration in Model-Based RL"
      </a>
      </td>
      <td>Contributed Talk: Tristan Shah - "Emergence of Diverse Social Interactions Through 'Egoistic Empowerment'"</td>
    </tr>
    <tr>
      <td>11:55–12:05</td>
      <td> <a href="{{ '/assets/abstracts/CT3.pdf' | relative_url }}" target="_blank"
     title="Abstract: Daniel Braun - Contrastive Goal Representation Learning">
      Contributed Talk: Daniel Braun - "Contrastive Goal Representation Learning for Open-Ended Reinforcement Learning"
      </a>
      </td>
      <td>Contributed Talk: John Lones - "Using (Neuro-)Hormones to generate motivations and support long term learning"</td>
    </tr>
    <tr>
      <td>12:05–13:35</td>
      <td>Lunch Break + Poster Session 1</td>
      <td>Lunch Break + Poster Session 2</td>
      <td></td>
    </tr>
    <tr>
      <td>13:35–14:15</td>
      <td><a href="{{ '/pages/speakers/jordanous' | relative_url }}"
     title="Anna Jordanous - Measuring success in open ended-learning AI models: what has been learned from computational creativity evaluation research">
      Anna Jordanous - "Measuring success in open ended-learning AI models: what has been learned from computational creativity evaluation research"
      </a>
      </td>
      <td><a href="{{ '/pages/speakers/verbelen' | relative_url }}"
     title="Tim Verbelen - Active Inference for Adaptive Robots: A First-Principles Approach to Perception, Planning, and Control">
      Tim Verbelen - "Active Inference for Adaptive Robots: A First-Principles Approach to Perception, Planning, and Control"
      </a>
      </td>
      <td></td>
    </tr>
    <tr>
      <td>14:15–15:15</td>
      <td>Panel: Ethics of Open-Ended Autonomy</td>
      <td>Panel: Intrinsic Motivation and Open-Endedness - the Future of AI! The Future of AI?</td>
      <td></td>
    </tr>
    <tr>
      <td>15:15–16:15</td>
      <td>Long Coffee Break 1 (Mentorship)</td>
      <td>Long Coffee Break 2 (Project Dating)</td>
      <td></td>
    </tr>
    <tr>
      <td>16:15–16:55</td>
      <td> <a href="{{ '/pages/speakers/simsek' | relative_url }}"
     title="Özgür Şimşek - Learning multi-level skill hierarchies in reinforcement learning">
      Özgür Şimşek - "Learning multi-level skill hierarchies in reinforcement learning"
      </a>
      </td>
      <td> <a href="{{ '/pages/speakers/levin' | relative_url }}"
     title="Michael Levin - Diverse intelligence: intrinsic motivation in evolved, engineered, and hybrid systems">
      Michael Levin - "Diverse intelligence: intrinsic motivation in evolved, engineered, and hybrid systems"
      </a>
      </td>
      <td></td>
    </tr>
    <tr>
      <td>16:55-17:00</td>
      <td>Closing Remarks</td>
      <td>Closing Remarks</td>
      <td></td>
    </tr>
      </tbody>
    </table>

  </div>
</div>

---

## Poster Sessions

### Poster Session 1 — *Monday, 8 September* · *12:05–13:35* (SPECTRA building, Floor 1 open space)

- *Richard Bornemann* — “Discrete Hierarchical Skill Spaces as a Next Frontier of Quality Diversity Methods”  
- *Erik M. Lintunen, Nadia M. Ady, Sebastian Deterding, Christian Guckelsberger* — “Employing Intrinsically Motivated Reinforcement Learning Towards a Formal Specification of the Need for Competence”  
- *Dominik Sobania, Martin Briesch* — “Open-Ended Evolution of Tools for Large Language Model-Based Problem Solving”  
- *Barthélémy Dang-Nhu, Louis Annabi, Sylvain ARGENTIERI* — “Linear Disentanglement through Action Group Learning”  
- *Mathilde Kappel, Mahdi Khoramshahi, Faiz BEN AMAR, Louis Annabi, Stephane Doncieux* — “Towards Robust Prehensile Manipulation in Open-Ended Environments”  
- *Zakaria LEMHAOURI, Laura COHEN, Ann Nowe, Lola Cañamero* — “Comparing Motivation-Based and Passive Language Learning Approaches for Robots in Ambiguous Environments”  
- *Theodora Hamilton-Holbrook, John Lones* — “Prima Facie: Neuromodulation to Support Motivation Interplay”  
- *Alexander David Wickham, Dongao Zhai, J. Michael Herrmann* — “Emergent Properties in Swarm Robotics: Towards Adaptive and Versatile Behaviour”  
- *Dari Trendafilov* — “Empowerment-based prediction of swarm performance in collective perception”  
- *Benjamin Fele, Jan Babic* — “Exploration via Junction States: Scalable Estimation with Door(s)”  
- *Miklos Kepes, Paul O'Dowd, Chanelle Lee* — “Beyond Copying: Selective Goal-Driven Imitation for Continual Adaptation of Autonomous Agents”  
- *Faizan Rasheed, Daniel Polani, Kenzo Clauw, Nicola Catenacci Volpi* — “Object Empowerment as an Intrinsic Drive for Tool Selection in Reinforcement Learning”  
- *Eleni Nisioti, Akhi Mocherla, Cédric Colas, Pierre-Yves Oudeyer, Clément Moulin-Frier, Jérémy Perez, Maxime Derex* — “Evolving Interaction Protocols for Open-Ended Collective Innovation”  
- *Fabian Wurzberger, Sebastian Gottwald, Daniel Alexander Braun* — “Contrastive Goal Representation Learning for Open-Ended Reinforcement Learning”  
- *Roberto Santana* — “A neuroevolutionary algorithm for plasticity loss mitigation based on neuron coverage”  
- *Loris Gaven, Thomas Carta, Clément ROMAC, Cédric Colas, Sylvain Lamprier, Olivier Sigaud, Pierre-Yves Oudeyer* — “MAGELLAN: Metacognitive predictions of learning progress guide autotelic LLM agents in large goal spaces”  
- *Julien Pourcel, Cédric Colas, Pierre-Yves Oudeyer* — “Self-Improving Language Models for Evolutionary Program Synthesis: A Case Study on ARC-AGI”  
- *Thomas Carta, Clément ROMAC, Loris Gaven, Pierre-Yves Oudeyer, Olivier Sigaud, Sylvain Lamprier* — “HERAKLES: Hierarchical Skill Compilation for Open-ended LLM Agents”  
- *Guillaume Pourcel, Thomas Carta, Grgur Kovač, Cédric Colas, Pierre-Yves Oudeyer* — “Learning Progress-Guided LLM Goal Generation for Autotelic Skill Learning”  
- *Frank Förster* — “Social Motivations - An Overlooked Topic in the Intrinsic Motivation Landscape?”  
- *William B. Langdon* — “Open-Ended Evolution with Linear Genetic Programming”  



### Poster Session 2 — *Tuesday, 9 September* · *12:05–13:35* (SPECTRA building, Floor 1 open space)

- *Fei-Yang Huang, Fabian Grabenhorst* — “Compositional Nutrient-Reward Valuation for Nutrient-sensitive Reinforcement Learning”  
- *Leticia Berto, Ricardo R. Gudwin, Esther Luna Colombini* — “Towards Autonomy: An Incremental, Intrinsically Motivated Approach for Cognitive Robots”
- *Erik M. Lintunen* — “VendiRL: A Framework for Learning Diversely Diverse Skills Under a Single Reward Formalism”  
- *Alejandro Romero, Gianluca Baldassarre, Richard J. Duro, Vieri Giuliano Santucci* — “A Motivational Architecture for Open-Ended Learning Challenges in Robots”
- *Michal Vavrecka, Gabriela Sejnova, Karla Stepanova, Radoslav Škoviera* — “PRAG: Procedural Action Generator”  
- *Jan Lemeire, Jure Zabkar, Domen Soberl, Marco Van Cleemput, Ruben Spolmink* — “Qualitative Models – The Missing Link for Self-Learning Embodied Agents”
- *John Lones* — “Using (Neuro-)Hormones to generate motivations and support long term learning”  
- *Timur Ryspekov, Yevgeniy Ussatov* — “iCon: A Modular AI Architecture for Open-Ended, Self-Supervised Learning”
- *Soumya Banerjee* — “Wu-Wei in the Machine: Open-Ended Learning in Goal-Free Generative Agent Societies”  
- *Ruben Spolmink, Marco Van Cleemput, Jan Lemeire* — “Skill learning using qualitative models”
- *Oksana Hagen* — “Task-Agnostic Representation Learning for Policy Learning in Embodied Agents: A Scoping Review”  
- *Andrey E Ustyuzhanin, Ivar Martin, Serg Bell* — “Mini-Bang Intelligence Benchmark: A Parametric Framework for Measuring Emergence Comprehension”
- *Emiland Garrabé, Julien Gleyze, Mahdi Khoramshahi, Stephane Doncieux* — “Open-ended planning and grasping for robotic manipulation tasks using lightweight LLMs”  
- *Mohan Sridharan* — “Toward Open-Ended Reasoning and Learning in Robotics”
- *Tristan Alexander Shah, Ilya Nemenman, Daniel Polani, Stas Tiomkin* — “Emergence of Diverse Social Interactions Through Egoistic Empowerment”  
- *Andrea Fanti, Roberto Capobianco* — “Unsupervised Reward Design”
- *Oliver Obst, Fabian C Weigend, Lisa Graf* — “Empowerment under Uncertainty: Approximate Bayesian Exploration in Model-Based RL”  
- *Tojoarisoa Rakotoaritina, Gaganpreet Jhajj, Chris Reinke, Kenji Doya* — “Information-Theoretic Formulation and Combination of Intrinsic Rewards: Novelty, Surprise and Empowerment”
- *Stavros T Anagnou* — “Empowerment for intrinsically motivated social conformity”  
- *Nicola Catenacci Volpi, Karen Archer, Emil Dmitruk, Kenzo Clauw, Frederick Richard, Emilio Cartoni, Gianluca Baldassarre* — “Empowerment for Goal-driven Open-Ended Learning”
- *Hampus Åström* — “"Environment Agnostic Goal-Conditioning, A Study of Reward-Free Autonomous Learning”  
