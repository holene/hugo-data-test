---
title: "Home"
layout: "index"
---

# Welcome to My Website

This is the homepage content.

## List of Departments

{{ partial "departments.html" . }}

## List of Teams

{{ partial "teams.html" . }}

## Testing the Jazz

{{ range $.Site.Data.jazz.bass }}
  {{ partial "artist.html" . }}
{{ end }}
