---
layout: page
title: The Mine
description: exploring the influence of users in an online dialogue
img: assets/img/the_mine/theMine_front.png
importance: 2
category: DSI (Reichman University)
---

In this project, we use Natural language processing (NLP) techniques to <b>quantify the influence</b> within a conversation between two users. We use existing NLP algorithms as well as developing new ones in order to estimate the influence solely based on textual data.

We use social media data for the project purpose. We focus on <b>Twitter</b> due to the high activity volume in the platform and the availability of the data. We focus on spoken Arabic language. We do no limit our research to a specific domain (e.g., politics, sports) within the Arabic corpus.

<!--<a href="TBD" class="card-link">Project website</a>-->
<a href="https://www.runi.ac.il/en/research-institutes/business/dsi/focus-areas/the-mine-project/" class="card-link"><font size="+1">Project description (on the DSI website)</font></a>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/the_mine/the_mine_structure.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    High level flow of the project.
</div>

<div class="card">
    <div class="card-body">
        <h5 class="card-title">Human-Directed Sentiment Analysis</h5>
        <p class="card-text">As part of The Mine project, we introduced a new sentiment analysis task for detecting the <b>sentiment</b> that is expressed by a user <b>toward another user</b> in a discussion thread. The paper, describing this new task has been published on <a href="http://nsurl.org/">NSURL, 2022</a></p>    
    </div>
    <ul class="list-group list-group">
        <li class="list-group-item"><u>Date Sources:</u> Twitter threads. </li>
        <li class="list-group-item"><u>Data Annotation:</u> human annotation of sentiment between two users on a Twitter conversation.</li>
        <li class="list-group-item"><u>Modeling:</u> BERT models to predict the human-directed sentiment.</li>
    </ul>
    <div class="card-body">
        <a href="https://aclanthology.org/2022.nsurl-1.4.pdf" class="card-link">Publication</a>
        <a href="https://huggingface.co/DSI/human-directed-sentiment" class="card-link">HuggingFace Model</a>
        <a href="https://github.com/idc-dsi/Human-Directed-Sentiment" class="card-link">Git Repository</a>      
    </div>
</div>
