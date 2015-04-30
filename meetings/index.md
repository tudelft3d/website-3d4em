---
layout: page
title: Meetings
permalink: /meetings/
---

## 2015-01-14 -- Kick-off meeting -- Rotterdam

<div class="row">
{% for i in site.data.20150114 %}
  <div class="col-xs-12 col-md-4">
    <div class="thumbnail">
      {{ i.link }}
      <div class="caption">
        <h4>{{ i.title }}
        <br />
        <small>{{ i.name }}</small>
        </h4>
      </div>
    </div>
  </div>
{% endfor %}
</div>




