---
layout: vertical
title: Schedule
---

# TENTATIVE SCHEDULE

THINGS ARE VERY LIKELY TO SHIFT AROUND - I'LL UPDATE THE SCHEDULE AS THINGS CHANGE, BUT KEEP AN EYE OUT ON PIAZZA AND EMAIL TOO.

<!--table border="1"-->
<table>
  <thead>
    <tr>
      <td><strong>Date&nbsp;&nbsp;</strong></td>
      <td><strong>Module</strong></td>
      <td><strong>Topic</strong></td>
      <td><strong>Reading&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</strong></td>
      <td><strong>Quizzes</strong></td>
      <td><strong>Projects</strong></td>
    </tr>
  </thead>
  <tbody>
    {% for item in site.data.22Summer-3630-Schedule %}
    <tr style="font-size: 10pt">
      <td>{{item.Month}} {{item.Date}}</td>
      <td>{{item.Module}}</td>
      <td>{{item.Topic}}</td>
      <td>{{item.Reading}}</td>
      <!-- <td>
        {% unless item.Slides == "-" %}
          <a href="Slides/{{item.Slides}}.pdf">pdf</a>
        {% endunless %}
      </td> -->
      <!-- <td>
        {% unless item.Reading == "-" %}
          <a href="notes/{{item.Reading}}.pdf">pdf</a>
        {% endunless %}
      </td> -->
      <td>{{item.Quizzes}}</td>
      <td>{{item.Projects}}</td>
    </tr>
    {% endfor %}
  </tbody>
</table>
