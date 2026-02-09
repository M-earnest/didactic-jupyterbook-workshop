# Why Use Jupyter Book?

Among the various tools available for creating OERs, why is our approach based on Jupyter Book?

**Great question!**

Jupyter Book is a powerful and flexible tool for creating open and interactive educational content. It is an open source tool that has been developed by the [Project Jupyter](https://jupyter.org/about), a non-profit and open-source project that aimed to support interactive data science. However, Jupyter Book is agnostic and can be used for any type of content. 

Below are some key reasons to consider using Jupyter Book for your next project:

````{dropdown} 1. Easy formatting
**Text can be easily formatted in Markdown files**  (text), and code can be written in Jupyter notebooks.

Here are some formatting basics:

1) Use hashtags `#` before your heading to create various levels of headings:
```
# Heading 1
## Heading 1.1
### Heading 1.1.1
```

2) Add a `*` before and after a word to make your text *italic* and add `**` to make it **bold**  
`*italic*`--> *italic*  
`**bold**`--> **bold**  


3) Build (nested) lists by using either `*` or `-` before a list item
```
* item 1
* item 2
  - item a
  - item b  
- item 3
```
to create such a list:

* item 1
* item 2
  - item a
  - item b  
- item 3
````


````{dropdown} 2. Multimedia integration
**Integrate visualizations, audio, videos, live code, equations, citations, cross-references and text seamlessly** into a single document to create an engaging learning experience.

**Image/Gif integration** 🖼️
<iframe src="https://giphy.com/embed/YPzvV7N0Cnlbbrigvp" width="480" height="271" style="" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/bigbangtheory-season-1-episode-9-big-bang-theory-YPzvV7N0Cnlbbrigvp">via GIPHY</a></p>

**Audio integration** 🎧  
<iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/3GJ6jnDrapgXAmxEXO6fWw?utm_source=generator" 
        width="100%" height="352" frameborder="0" 
        allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy">
</iframe>

**Video integration** 📺  
<iframe width="560" height="315" src="https://www.youtube.com/embed/9YuNGB3vNOw?si=dPCD8xeLaUuimvYP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Integration of presentations** 
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTJvUAN-dg7r7Dbj-KpxcNO6ssd7akDQjBbHzhTTBBU7zSBZ4sTfjYPtHZL6V7GmM0VQvo6Aviu5oSG/embed?start=false&loop=false&delayms=10000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
````

```{dropdown} 3. Collaboration and sharing
**Collaborate and share easily**, thanks to its open-source nature and GitHub integration.

Here, I have added my colleague to the project:

![Image showing the GitHub settings where collaborators are added](../static/collaborators.png)

Now, both of us can track all changes (called _commits_) made to the project:

![Image of a list of commits on GitHub](../static/commit-list.png)

By inspecting a specific commit, we can review the exact changes that were applied:

![Image of tracked changes in one commit example](../static/commit-example.png)
```

```{dropdown} 4. Interactive elements
**Enhance exercises and quizzes** with interactive elements such as sliders and dropdowns.

When you read this, you already opened a dropdown, that can be used for tips, hints, spoilers, warnings, etc.
```

```{dropdown} 5. Accessibility
**Make your materials accessible across platforms** with multiple export formats (HTML, PDF, EPUB). This also allows you to easily cite your course website in your CV or on your personal website.

You can download this page by clicking on the download button on the upper right side. 
 
![Image of the download button on the upper right side](../static/download-button.png)
```

```{dropdown} 5. Strong community and support
**Rely on a strong community and extensive support**, as Jupyter Book builds on the widely used Jupyter Notebook ecosystem.

Here are, e.g., the [community forum](https://discourse.jupyter.org/) and a freely accessible [documentation](https://jupyterbook.org/en/stable/intro.html). 
```

By leveraging Jupyter Books, educators can create dynamic, reusable, and interactive learning experiences that not only meet modern teaching and research needs but also align more effectively with the principles of open science and [FAIR](https://www.nature.com/articles/sdata201618) research than conventional approaches.

````{card} 
**Let's take a look!**
^^^
Please browse the [gallery of Jupyter Books created by the community](https://executablebooks.org/en/latest/gallery/) and choose one example to explore:
- What didactic challenges does it address?
- What elements have been integrated?
- Which features might be useful or inspiring for your own teaching?

Take about 10 minutes for this activity. We will then discuss your impressions together. 
````

```{note}
I know, some of these examples look really polished and complex! But don’t worry. On the next page, you’ll find information about our framework and the easy-to-adapt template that will make creating your own course website really simple.
```
