---
layout: welcome
---

<div style="height: 50px;"></div>

## Recent Projects and Updates

The project tab contains a complete list of project.

<ul style="padding: 0; list-style-type: none;">
  {% for post in site.posts %}
    <li style="margin-bottom: 20px;">
        <a href="{{ site.baseurl }}{{ post.url }}">
            <div class="card">
                <div class="card-container">
                    <h3><b>{{ post.title }}</b></h3> 
                    <h4>Details</h4> 
                </div>
            </div>
        </a>
    </li>
  {% endfor %}
</ul>