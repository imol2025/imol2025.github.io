---
layout: page
title: Schedule
---
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
      <td>Contributed Talk: Thomas Carta - "HERAKLES: Hierarchical Skill Compilation for Open-ended LLM Agents" </td>
      <td>Contributed Talk: Émiland Garrabé - "Open-ended planning and grasping for robotic manipulation tasks using lightweight LLMs"</td>
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
     title="Abstract: Fabian Wurzberger - Contrastive Goal Representation Learning">
      Contributed Talk: Fabian Wurzberger - "Contrastive Goal Representation Learning for Open-Ended Reinforcement Learning"
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
