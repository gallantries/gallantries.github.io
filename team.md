---
layout: page
title: Our Team
---

<div class="people">
  {% for entry in site.data['people'] %}
    {% assign username = entry[0] %}
    {% include _includes/people.html username=username %}
  {% endfor %}
</div>

# Current partners and sponsors

Primary partners
- The Carpentries provides the training material template and in particular the material relating to the Genomics workshop using R.
- Galaxy community and Galaxy Training Network provide the technical infrastructure (as the European instance of Galaxy), the training material template and in particular the material relating to the Reference based RNA-Seq workshop.

Both will also provide the training infrastructure; i.e. hosting the material, impact assessment, instructors' community.


Supporting Partners
- [de.NBI](https://www.denbi.de/) is supporting BB and HR through in-kind contribution. Moreover, all the computational resources of the European instance of Galaxy are provided by de.NBI. Any partner workshops in Germany will be funded and run by de.NBI staff.
- [DTL](https://www.dtls.nl/) is supporting Mateusz Kuzak through in-kind contribution
- [INAB|CERTH](http://inab.certh.gr) is supporting Fotis Psomopoulos through in-kind contribution.
- EMC is supporting SH through in-kind contribution.
- [Mozilla foundation](https://foundation.mozilla.org/en/) is supporting via a [Mozilla Open Science Mini-Grants](https://foundation.mozilla.org/en/awards/)
