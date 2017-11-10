---
layout: gold
title: Programs
permalink: /programs/

[//]: #Page Header
circle: "#1250ed"
---
<div class="fullwidth_bg">
    <div class="programs_content inner_wrapper">
        <div class="frow row-between">
            {% for item in site.data.programs %}
            <div class="program_item">
                <div class="programs_title">
                    {{ item.title }}
                </div>
                <div class="programs_group">
                    ({{ item.group }})
                </div>
                <div class="programs_text">
                    {{ item.summary }}
                </div>
            </div>
            {% endfor %}
        </div>
    </div>
</div>
