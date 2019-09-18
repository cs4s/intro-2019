---
layout: default
title: Resources - CS4S Introduction Workshop @ UON 2019
---

<div class="container">
    <div class="showcase">
        <div class="container">
            <h1>Resources</h1>

            If you are interested in finding out more about Coding, Computational Thinking, Computer Science and the Digital Technologies Curriculum, we have provided some resources for you to explore.
            
            <p></p>
            {% capture links_websites %}{% include_relative tables/links_websites.md %}{% endcapture %}
            {{ links_websites | markdownify }}
            {% capture links_online_courses %}{% include_relative tables/links_online_courses.md %}{% endcapture %}
            {{ links_online_courses| markdownify }}
            {% capture links_lessons %}{% include_relative tables/links_lessons.md %}{% endcapture %}
            {{ links_lessons | markdownify }}
        </div>
    </div>
</div>