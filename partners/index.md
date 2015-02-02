---
layout: page
title: Partners
permalink: /partners/
---


<div class="row">
{% for p in site.data.partners %}
  <div class="col-xs-4 col-md-2">
    <a href="{{ p.url }}" class="thumbnail">
      <img src="{{ "/img/partners/" | append: p.img | prepend: site.baseurl }}" alt="">
    </a>
  </div>
{% endfor %}
</div>

- - - 

# Contacts

<div class="table-responsive">
  <table class="table table-striped">
    <thead>
      <tr>
        <th style="text-align: left">Name</th>
        <th style="text-align: left"></th>
        <th style="text-align: left">Organisation</th>
        <th style="text-align: left">email</th>
        <th style="text-align: left">Webpage</th>
      </tr>
    </thead>
    <tbody>
    {% assign peoples = site.data.people | sort:"surname"  %}
    {% for p in peoples %}
      <tr>
        <td style="text-align: left">{{ p.surname }}</td>
        <td style="text-align: left">{{ p.name }}</td>
        <td style="text-align: left">{{ p.org }}</td>
        <td style="text-align: left">{{ p.email }}</td>
      {% if p.url %}
        <td style="text-align: left"><a href="{{ p.url }}"><i class="fa fa-external-link"></i></a></td>
      {% else %}
        <td style="text-align: left"></td>
      {% endif %}
      </tr>
    {% endfor %}
    </tbody>  
  </table>
</div>

