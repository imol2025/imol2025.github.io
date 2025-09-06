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
      <td>Invited Talk: Gianluca Baldassarre</td>
      <td>Invited Talk: Christian Guckelsberger</td>
      <td>Invited Talk: Franziska Braendle</td>
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
     Tim Rocktäschel - Open-Endedness and World Models
     </a>
     </td>
      <td>Invited Talk: Jakob Foerster</td>
      <td>Invited Talk: Michael Herrmann</td>
    </tr>
    <tr>
      <td>11:35–11:45</td>
      <td>Contributed Talk 1</td>
      <td>Contributed Talk 4</td>
      <td rowspan="3">Closing Remarks</td>
    </tr>
    <tr>
      <td>11:45–11:55</td>
      <td>Contributed Talk 2</td>
      <td>Contributed Talk 5</td>
    </tr>
    <tr>
      <td>11:55–12:05</td>
      <td>Contributed Talk 3</td>
      <td>Contributed Talk 6</td>
    </tr>
    <tr>
      <td>12:05–13:35</td>
      <td>Lunch Break + Poster Session 1</td>
      <td>Lunch Break + Poster Session 2</td>
      <td></td>
    </tr>
    <tr>
      <td>13:35–14:15</td>
      <td>Invited Talk: Anna Jordanous</td>
      <td>Invited Talk: Tim Verbelen</td>
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
      <td>Invited Talk: Özgür Şimşek</td>
      <td>Invited Talk: Michael Levin</td>
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
