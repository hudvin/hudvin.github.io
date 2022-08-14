---
layout: post
title: ""
author: "Vadym Bartko"
permalink: /photo_galleries/
---

{%  for post in site.posts %}
{%       if post.tags contains 'Photos' %}
   <p><a href="{{post.url}}">{{post.title}}</a></p> 
{%       endif %}
{%  endfor %}