---
layout: page
title: "Kurrawong AI"
permalink: /
---
<div style="float:right; width: 300px; padding: 10px; margin: 10px; border:solid 5px black; border-radius: 10px; text-align:center;">
See information about Kurrawong AI in <a href="http://localhost:4000/.ttl">machine-readable (RDF) form</a>.
</div>
Kurrawong AI is a small, Artificial Intelligence, company in Australia specialising in [Knowledge Graphs](https://en.wikipedia.org/wiki/Knowledge_graph). 

We use KGs for data storage, as a transfer format, when serialised, and as inputs to advanced reasoning and data processing tasks, such as [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning).

We model data using the [Semantic Web](https://www.w3.org/standards/semanticweb/) so it's in the richest, most open and most extensibe form data can be.

<h3>Current work</h3>

<section>
  <div class="content hideContent">
    <h4>Queensland Spatial Information Dataset Redesign</h4>
    <p>Kurrawong AI has recently (June, 2022) completed modelling the Address and Place Names datasets of Queensland and their replation to Cadastral information via a a <a href="https://frontiersi.com.au/">FrontierSI</a> consortium with the following, outputs:</p>
    <ul>
        <li>
            <a href="https://nicholascar.com/qsi-supermodel/supermodel.html">Queensland Spatial Information Supermodel</a>
            <ul><li>overarching framework linking the Address & Place Names models to Cadastral data</li></ul>
        </li>
        <li>
            <a href="https://nicholascar.com/anz-nat-addr-model-candidate/model.html">Candidate National Address Model</a>
            <ul>
                <li>aligns with ICSM <em>Addressing 2035 strategy</em>, national & international models</li>
                <li>provides graph and relational DB implementations of Qld testing data</li>
                <li>used by the Linked Data version of the G-NAF soon to be online via a <a href="https://www.ga.gov.au">Geoscience Australia</a> Foundational Spatial Data Framework initiative</li>
            </ul>
        </li>
        <li>
            <a href="https://w3id.org/profile/qsi-placenames">QSI Place Names Model</a>
            <ul><li>A profile of the ANZ National Address Model and the Place Names Ontology for the representation of Place Names in Queensland</li></ul>
        </li>
    </ul>
  </div>
  <a class="show-more" href="#">Show more...</a>
</section>

<section>
  <div class="content hideContent">
    <h4>Semantic Web system scaling consulting</h4>
    <p>Kurrawong AI will provide an analysis of the Semantic Web system's used by the <a href="https://www.tern.org.au">Terrestrial Ecosystems Research Network (TERN)</a> to ensure they can scale to meet growing data and usage demands over July/September, 2022.</p>
    <p>TERN are perhaps the most "Semantic Web native" government/educational unit in Australia and to work with them is an honour.</p>
  </div>
  <a class="show-more" href="#">Show more...</a>
</section>

<img id="graph" src="style/graph.png" style="float:right;" />

### Availability 

Kurrawong AI can be contracted directly and is on several government panels. Please just contact us to make arrangements.

### Contact

To find out more about Kurrawong, just contact us using the details in the footer below!


<script>
    var elements = document.getElementsByClassName("show-more");

    var click_event = function() {
            var linkText = this.innerHTML.toUpperCase();
        if (linkText === "SHOW MORE...") {
                this.innerHTML = "Show less";
            this.previousElementSibling.classList.remove("hideContent");
            this.previousElementSibling.classList.add("showContent");

        }
        else {
                this.innerHTML = "Show more...";
            this.previousElementSibling.classList.remove("showContent");
            this.previousElementSibling.classList.add("hideContent");
        }
    };

    for (var i = 0; i < elements.length; i++) {
        elements[i].addEventListener('click', click_event, false);
    }
</script>

<style>
    section {
        margin: 20px;
    }
    .hideContent {
        overflow: hidden;
        line-height: 1em;
        height: 8em;
    }
    .showContent {
        line-height: 1.5em;
        height: auto;
    }
    .show-more {
        padding-top: 15px;
        text-align: center;
        font-size: smaller;
        font-style: italic;
    }    
</style>