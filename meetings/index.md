---
layout: page
title: Meetings
permalink: /meetings/
---

## 2016-05-31 -- 2nd Users' meeting -- Amsterdam

<div class="row">
{% for i in site.data.20160531 %}
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



## 2015-11-11 -- 1st Users' meeting -- Utrecht

<div class="row">
{% for i in site.data.20151111 %}
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




