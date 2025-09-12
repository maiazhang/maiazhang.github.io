---
title: "Earthquake Clustering in the Japan Subduction Zone"
last_modified_at: 2016-03-09T16:20:02-05:00
published: true
categories:
  - Blog
---

I am looking at earthquake clustering in one of the most complete earthquake catalogs in the world, the Japan Meteorological Agency Catalog (JMAC). I apply a nearest-neighbors clustering method developed by <a href="https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/jgrb.50179"> Zaliapin & Ben-Zion </a>, looking to scale the approach from a point-source model (which cannot be reliably assumed for larger earthquakes) to one which can incorporate fault plane length and focal mechanisms. 

![](/assets/images/jpnclust.png)
*Nearest neighbors clustering applied to a subset of the JMAC demonstrating the limitations of a point-source assumption at large magnitude events like the $$M_{w}$$ 9.1 2011 Tohoku earthquake. This may be true for smaller events too (note that the "streaking" over short rescaled time intervals and large rescaled distance intervals remains visible pre-Tohoku).*

<div style="border: 1px solid #ccc; padding: 15px; background-color: #efdce2ff; border-radius: 5px; text-align: center;">
    <!-- Content and hyperlink will go here -->
  <a href="https://agu.confex.com/agu/agu24/meetingapp.cgi/Paper/1748162"> See AGU ('24) presentation abstract </a>
</div>