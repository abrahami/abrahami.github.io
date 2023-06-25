---
layout: page
title: DiaCorpus
description: a collaboration project with the Israel Innovation Authority
img: assets/img/diaCorpus_front.JPG
importance: 1
category: DSI (Reichman University)
---

The goal of this project is to develop of a large, comprehensive, and annotated corpora in Israeli/Palestinian Arabic dialect. The project is part of the <a href="https://github.com/NNLP-IL/NNLP-IL">National NLP Plan of Israel</a>. I am the lead data scientist of this project, which consists of 12 more researchers and two teams of 6-10 annotators each.

The endeavor encompasses two distinct undertakings:
<style>
    ol {
        line-height: 2.5; /* Adjust this value to increase or decrease line spacing */
    }
</style>
<ol type="a">
  <li><a href="#parta">Spoken Arabic Corpora Creation</a></li>
  <li><a href="#partb">Textual (dialectical) Arabic Corpora Creation</a></li>
</ol>

<!-- I have taken the card template from here: https://getbootstrap.com/docs/4.0/components/card/-->
<a id="parta"></a>
<div class="card">
    <div class="card-body">
        <h5 class="card-title"> a. Spoken Arabic Corpora Creation</h5>
        <p class="card-text">Creating dialectic Arabic corpora from recorded speech -- podcasts and interviews.</p>
    </div>
    <ul class="list-group list-group">
        <li class="list-group-item"><u>Date Sources:</u> publicly available podcasts, and personal interviews.</li>
        <li class="list-group-item"><u>Data Transcription:</u> automatic Azure speech to text technology and manual spelling corrections.</li>
        <li class="list-group-item"><u>Data Annotation:</u> each text chunk is humanly annotated according to three NLP tags: sentiment, emotion, and NER.</li>
        <li class="list-group-item"><u>Modeling:</u> per task, we build and publish an NLP predictive model.</li>
    </ul>
    <div class="card-body">
        <a href="https://idc-dsi.github.io/DiaCorpus/" class="card-link">Project website</a>
        <a href="https://www.runi.ac.il/en/research-institutes/business/dsi/focus-areas/diacorpus/recorded-speech-to-text/" class="card-link">Project description</a>
    </div>
    <img class="card-img-bottom" src="../../assets/img/dsi-program.png" alt="Card image cap">
</div>

<p>
</p>

<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/DiaCorpus_part1.jpg" title="DiaCorpus, first part" class="img-fluid rounded z-depth-1" %}
</div>
<div class="caption">
        Corpora creation flow - spoken Arabic.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/julian_interviews/julian1.jpg" title="julian1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/julian_interviews/julian2.jpg" title="julian2" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/julian_interviews/julian3.jpg" title="julian3" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/julian_interviews/julian4.jpg" title="julian4" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Personal interviews we recorded as part of the project. The pictures were taken by <a href="https://twitter.com/juliancharbel?lang=en">Julian Jubran</a> , the interviewer of all participants in the project.
</div>

<a id="partb"></a>
<div class="card">
    <div class="card-body">
        <h5 class="card-title">b. Textual (dialectical) Arabic Corpora Creation</h5>
        <p class="card-text">Creating dialectic Arabic corpora from textual sources for three distinct NLP tasks-- sentiment, coreference resolution, and summarization.</p>
    </div>
    <ul class="list-group list-group">
        <li class="list-group-item"><u>Date Sources:</u> dialectical Arabic texts (e.g., Twitter data, transcribed podcasts). </li>
        <li class="list-group-item"><u>Data PreProcessing:</u> data filtering and NLP pre-processes (e.g., tokenization).</li>
        <li class="list-group-item"><u>Data Annotation:</u> human annotation of the text, per task (i.e., sentiment, coreference resolution, and summarization).</li>
        <li class="list-group-item"><u>Modeling:</u> per task, we build and publish an NLP predictive model.</li>
    </ul>
    <div class="card-body">
        <!--<a href="TBD" class="card-link">Project website</a>-->
        <a href="https://www.runi.ac.il/en/research-institutes/business/dsi/focus-areas/diacorpus/textual-data-corpora/" class="card-link">Project description</a>
    </div>
    <img class="card-img-bottom" src="../../assets/img/dsi-program.png" alt="Card image cap">
</div>

<p>
</p>

