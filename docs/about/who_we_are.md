---
layout: about
title: Who we are?
date: 30 October 2023
date-modified: last-modified
authors:
  - name: Maximilian Koslowski
    github: maximikos
    roles:
      - writing
      - editing, review
      - validation
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---
<h1>{{ .layout.title }}</h1>

<h1>{{ .Layout.title }}</h1>

<h1>{{ layout.title }}</h1>

<h1>{{ Layout.title }}</h1>

<h1>{{ content.title }}</h1>

<h1>{{ Content.title }}</h1>

{{ title }}

{ title }

# Who we are

hello {{ $.Page.title }}

hello {{ $.Page.Param.title }}

# hello {{ $frontmatter.title }}

# {{ frontmatter.title }}

{ frontmatter.title }
{frontmatter.title}

> *Last edited by* <a href=”https://github.com/maximikos“><img src="https://github.com/maximikos.png" alt="GitHub user" title="Max Koslowski" width="40" style="border-radius: 50%" /></a> *on* <i><a id="current_date"></a></i>

# {{ about.title }}

# {% $frontmatter.title %}

The world is complex. And here we want to show you how we can account for this complexity and the associated environmental and socio-economic repercussions. Methods such as life cycle assessment and material flow analysis are introduced and applied in many small examples. In addition, actual research insights are provided which are broken down into simple language - as much as this is possible.

The idea for providing such an overview has been developed and was refined by [Max Koslowski](https://www.ntnu.edu/employees/maximilian.koslowski), a doctoral researcher at NTNU's [Industrial Ecology programme](https://www.ntnu.edu/indecol/).

This website is now about to be updated as part of the ISIE website project.

# {{ params.title }}

````{tab-set}
```{tab-item} LCA
Some brief description of LCA
```

```{tab-item} MFA
Some brief description of MFA with `some code`!
```
````

# {{ .title }}

# {{ $.title }}

% This HTML activates utterances only on this page
```{raw} html
<script
   type="text/javascript"
   src="https://utteranc.es/client.js"
   async="async"
   repo="maximikos/indeco"
   issue-term="pathname"
   theme="github-light"
   label="💬 comment"
   crossorigin="anonymous"
/>
```