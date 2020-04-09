---
layout: page
title: Projects
permalink: /projects/
description: Current and past projects I have been involved in.
---

<main class="project-grid">
    {% for project in site.projects %}
    <article>
        <img src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>
        <div class="project-text">
            <h1>{{ project.title }}</h1>
            <p>{{ project.description }}</p>
            {% if project.redirect %}
                <button onclick="window.open('{{ project.redirect }}', '_blank')" type="button">{{ project.button }}</button>
            {% else %}
                <button onclick="window.location='{{ project.url | prepend: site.baseurl | prepend: site.url }}'" type="button">{{ project.button }}</button>
            {% endif %}
        </div>
    </article>
    {% endfor %}
</main>
