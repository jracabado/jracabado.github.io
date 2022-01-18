---
layout: page
title: Diagram
permalink: /diagram/
---

*Redis Tests Exploration*

Redis test suite follows a client server architecture. The server is used to orchestrate and summarise the results of each group of tests which run as clients in a separate processes. 

A .tcl file in the tests folder will define various test cases, run with test { } {}, and the test setup is done via start_server {} {}. 

The tests are grouped in folders alongside the following categories:
- unit
- integration
- cluster
- sentinel

Other relevant folders are:
- assets
- helpers
- modules
- support
- tmp

To better understand how a given test is run I will start by looking at entry point for most tests /tests/support/server.tcl:start_server. 

This how it's used:

<excerpt from /test/unit/string.tcl>

start_server launches a Redis server which is then used for the execution of the Redis commands defined on the tests. These Redis commands are define as <TODO>

<script type="text/javascript"

  src="https://unpkg.com/mermaid@8.0.0-rc.8/dist/mermaid.min.js">

</script>

<script>

$(document).ready(function() {

    mermaid.initialize({

        theme: 'forest'

    });

});

</script>

<div class="mermaid">

    graph TD

      B[peace]

      B-->C[fa:fa-ban forbidden]

      B-->D(fa:fa-spinner);

      B-->E(fa:fa-camera-retro perhaps?);

</div>

[jekyll-organization]: https://github.com/jekyll
