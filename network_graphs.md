---
layout: page
title: Network Graphs
---



<div class="graphs-grid">

  <div class="graph-card">
    <h3>Performers and Composers</h3>
    <p>
      This visualisation represents all instances in which two performers took part in the same musical event, as well as all instances in which a performer performed the music of a given composer. It consists of 2,466 nodes and 11,423 unique edges, with a total weight of 52,282 effective relationships. 
    </p>
    <a class="graph-preview" href="https://raw.githubusercontent.com/martinnicastro/martinnicastro.github.io/64c0bc2a31d2ebe7fd8d3c86de1fefafb6284e68/modularity.svg" target="_blank" rel="noopener noreferrer">
      <img src="{{ '/images/perf_comp_ok.png' | relative_url }}" alt="Preview of the Performers and Composers network graph">
    </a>
    <p class="graph-links">
      <a href="https://raw.githubusercontent.com/martinnicastro/martinnicastro.github.io/64c0bc2a31d2ebe7fd8d3c86de1fefafb6284e68/modularity.svg" target="_blank" rel="noopener noreferrer">
        Open full graph
      </a>
      (given the dimension of the file it will be necessary to zoom out).
    </p>
  </div>

  <div class="graph-card">
    <h3>Performers and Venues</h3>
    <p>
      This graph connects Milanese music venues with the performers who appeared there between 1958 and 1962. It includes 1,985 nodes (123 venues and 1,741 performers) connected by 2,517 individual edges. Each edge is assigned a weight based on the number of times a performer appeared at a given venue, resulting in a total of 18,371 effective ties. The colours of both nodes and edges reflect venue categories. 
    </p>
    <a class="graph-preview" href="https://raw.githubusercontent.com/musictopography/musictopography.github.io/1985207c7729d63a6fc610d7962af9496443b931/spazi_musicisti_nomi.svg" target="_blank" rel="noopener noreferrer">
      <img src="{{ '/images/spaces_perf.png' | relative_url }}" alt="Preview of the Performers and Venues graph">
    </a>
    <p class="graph-links">
      <a href="https://raw.githubusercontent.com/musictopography/musictopography.github.io/1985207c7729d63a6fc610d7962af9496443b931/spazi_musicisti_nomi.svg" target="_blank" rel="noopener noreferrer">
        Open full graph
      </a><br>
      <a href="https://raw.githubusercontent.com/musictopography/musictopography.github.io/0db387992a7c7b3b10f2db49f9dfd844d75e5da3/images/modularity_total.svg" target="_blank" rel="noopener noreferrer">
        Open modularity analysis
      </a>
    </p>
  </div>

  <div class="graph-card">
    <h3>Venues and Music Genres</h3>
    <p>
      The network relates performance spaces to musical genres. It features 122 nodes, divided into 99 venues and 23 musical genres, and 309 weighted edges, amounting in total to 11,434 relationships. 
    </p>
    <a class="graph-preview" href="https://raw.githubusercontent.com/musictopography/musictopography.github.io/14d4d07b1e5c1b46db9ab25eb276252d07f0ab75/images/generi_spazi.svg" target="_blank" rel="noopener noreferrer">
      <img src="{{ '/images/genres_spaces.png' | relative_url }}" alt="Preview of the Venues and Music Genres graph">
    </a>
    <p class="graph-links">
      <a href="https://raw.githubusercontent.com/musictopography/musictopography.github.io/14d4d07b1e5c1b46db9ab25eb276252d07f0ab75/images/generi_spazi.svg" target="_blank" rel="noopener noreferrer">
        Open full graph
      </a>
    </p>
  </div>

</div>
