---
title: "Home"
layout: "index"
---

# Welcome to My Website

This is the homepage content.

## List of Departments

This is a list of departments from the index.md file. 

{{ partial "departments.html" . }}

## List of Teams

This is a list of teams from the index.md file. 

{{ partial "teams.html" . }}

## Testing the Jazz

This is an attempt to display the jazz documentation example. 

{{ range $.Site.Data.jazz.bass }}
  {{ partial "artist.html" . }}
{{ end }}
