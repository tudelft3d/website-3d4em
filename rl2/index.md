---
layout: page
title: Research line 2 
---

## Storage, update and dissemination of massive 3D city objects

<div class="row">
  <div class="col-sm-4 hidden-xs nopadding"><img class="img-responsive" src="{{ "img/1.png" | prepend: site.baseurl }}"></div>
  <div class="col-sm-4 hidden-xs nopadding"><img class="img-responsive" src="{{ "img/2.png" | prepend: site.baseurl }}"></div>
  <div class="col-sm-4 hidden-xs nopadding"><img class="img-responsive" src="{{ "img/4.png" | prepend: site.baseurl }}"></div>
</div>

- - -

The aim of this research line is to investigate and develop methods to efficiently store and maintain 3DTOP10NL in a database, and to disseminate it to practitioners.
The [existing open-source database solutions](http://www.3dcitydb.org) for managing 3D volumetric objects will be tested with massive datasets and improved, if necessary.

The biggest challenge is the management of massive TINs (triangulated irregular networks) in a database.
We will investigate, design and develop new data structures (eg based on [this](http://www.cs.cmu.edu/~blelloch/papers/BBCK05.pdf) and [that](http://3dgeoinfo.bk.tudelft.nl/hledoux/pdfs/13_gsis_pgtet.pdf)), implement them, and compare different alternatives (in terms of storage space, query time, etc).

Furthermore, a prototype download service that generates 3D datasets tailored to specific applications will be explored, eg [WFS](http://www.opengeospatial.org/standards/wfs) for 3D objects and massive triangulations.

