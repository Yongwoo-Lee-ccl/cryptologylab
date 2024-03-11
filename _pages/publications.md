---
title: "Cryptology Lab - Publications"
layout: gridlay
excerpt: "Cryptology Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## International conferences

{% for publi in site.data.intconf %}

  <a href="{{ publi.link.url }}">{{ publi.title }}</a> <br />
  <em style="color: gray;">{{ publi.authors }} </em><br />{{ publi.link.display }}

{% endfor %}

## International journals

{% for publi in site.data.intjournal %}

  <a href="{{ publi.link.url }}">{{ publi.title }}</a> <br />
  <em style="color: gray;">{{ publi.authors }} </em><br />{{ publi.link.display }}

{% endfor %}

## ePrints

{% for publi in site.data.eprint %}

  <a href="{{ publi.link.url }}">{{ publi.title }}</a> <br />
  <em style="color: gray;">{{ publi.authors }} </em><br />{{ publi.link.display }}

{% endfor %}


## Domestic conferences

{% for publi in site.data.domconf %}

  <a href="{{ publi.link.url }}">{{ publi.title }}</a> <br />
  <em style="color: gray;">{{ publi.authors }} </em><br />{{ publi.link.display }}

{% endfor %}


<!-- ## Domestic journals

{% for publi in site.data.domjournal %}

  <a href="{{ publi.link.url }}">{{ publi.title }}</a> <br />
  <em style="color: gray;">{{ publi.authors }} </em><br />{{ publi.link.display }}

{% endfor %} -->

## Patents

{% for publi in site.data.patents %}

  <a href="{{ publi.link.url }}">{{ publi.title }}</a> <br />
  <em style="color: gray;">{{ publi.authors }} </em><br />{{ publi.link.display }}

{% endfor %}
