<script src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script>

[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://github.com/maximikos/indeco)
![Static Badge](https://img.shields.io/badge/under_development-orange)
[![Static Badge](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)


# Welcome 👋

> *Last edited by* <a href=”https://github.com/maximikos“ target="_blank"><img src="https://github.com/maximikos.png" alt="GitHub user" title="Max Koslowski" width="40" style="border-radius: 50%" /></a> *on* <i><a id="current_date"></a></i>

In our modern globalised world, pressures on ecosystems and the resulting impacts are ever increasing. Pollution, land use, and water stress are just a few of these dimensions. In the end, human activities are responsible for the major part of global environmental change, both directly and indirectly. Over the course of the last few decades multiple research streams got established with the focus of analysis this environmental change, its causes, and its implications. These research streams can be summarised under the terms industrial ecology and quantitative systems analysis. This is a short introduction to these fields of research fields.



```{note}
If the terms industrial ecology and quantitative systems analysis don\'t ring a bell, let us give you some examples:

- Have you ever wondered how much greenhouse gases are emitted when producing a plastic bag?
- Do you have an idea of how much aluminium circulates around the world?
- What is your guess on how many species go extinct because of our normal household consumption?

If you are curious to learn how this kind of questions can be answered, you might be interested in checking out the following sections.
```

:::{admonition} What can you expect?
:class: tip, dropdown
On the following pages, you will be introduced to the general mindset necessary for such complex analysis, the research methods as such (including life cycle assessment, material flow analysis, and input-output analysis), and examples of how they are applied. In addition, we are planning on presenting real-life research examples.
:::

<iframe style='display: block; margin: 0 auto;' width="560" height="315" src="https://www.youtube.com/embed/4LQQZMaXMSY?si=jxlDLFIs8ZpU7bOk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<div id="current_date">
    <script>
        const daysOfWeek = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
        const date = new Date();
        const dayName = daysOfWeek[date.getDay()];
        document.getElementById("current_date").innerHTML = `${dayName}, ${date.toLocaleDateString()}`;
    </script>
</div>


<script src="https://utteranc.es/client.js"
        repo="maximikos/indeco"
        issue-term="pathname"
        label="🔮"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>

<script>
  if (window.netlifyIdentity) {
    window.netlifyIdentity.on("init", user => {
      if (!user) {
        window.netlifyIdentity.on("login", () => {
          document.location.href = "/admin/";
        });
      }
    });
  }
</script>