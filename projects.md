---
layout: default
title: Projects
permalink: /projects/
---

## Recent Projects and Updates

The project tab contains a complete list of project.

<div>
    <ul style="padding: 0; list-style: none;">
    {% for post in site.posts %}
        <li style="margin-bottom: 20px;">
            <a href="{{ site.baseurl }}{{ post.url }}">
                <div class="card">
                    <div class="card-container">
                        <h4 style="float: right;">{{ post.date }}</h4>
                        <h3><b>{{ post.title }}</b></h3> 
                        <h4>{{ post.description }}</h4>
                    </div>
                </div>
            </a>
        </li>
    {% endfor %}
    </ul>
</div>