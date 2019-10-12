---
layout: outcomes
title: "Day 2: Sharing Session"
---

# Sharing Session

## About

On this page, we have included copies of the lesson plans that were created during the collaborative lesson planning activity on Day 2 of the workshop.

## Plans

You can view and download the lesson plans created during the workshop from the table below.

<table class="table table-striped table-bordered">
    <thead>
        <tr>
            <th>Group</th>
            <th>Syllabus</th>
            <th>Outcomes Addressed</th>
            <th></th>
        </tr>
    </thead>
    <tbody>
        {% for plan in site.data.shared_plans %}
        <tr>
            <td>{{ plan.group }}</td>
            <td>{{ plan.syllabus }}</td>
            <td>{{ plan.outcomes }}</td>
            <td>
                <a href="plans/{{ plan.group }}.pdf" target="_blank">
                    View Plan
                </a>
                <i class="fas fa-file-pdf session-icon"></i>
            </td>
        </tr>
        {% endfor %}
    </tbody>
</table>
