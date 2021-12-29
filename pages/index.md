---
layout: page
---

{% include jumbotron.html title=site.title  %}

The Plant Translocation Network is an international network of researchers, practitioners and policymakers using plant translocations to address biodiversity loss.  

### Current activities
 1. Building a diverse global membership (see <a href="membership" title="Members">Members</a> for a list of current members and judge for yourself how geographically diverse we are - we're still very underepresented in South America, Asia and Africa);
 2. Developing methods for using plant translocations to monitor the biological impacts of climate change (see <a href="SFannouncement" title="Resources">Resources</a> link for a recent collection of papers on this topic);
 3. Exploring the potential for review papers, special issues and practice-relevant publications to develop science and practice in using plant translocations to address global biodiversity loss. We are currently developing reporting and monitoring protocols for plant translocations to be published open access in 2022.

 We are always looking for new members and new ideas to help improve the use of plant translocations and our understanding of their impacts on our environment and its management.  Our members number more than 100 and include conservationists, foresters, horticulturalists, and others who move plants to try to generate a positive outcome for the planet.

For information on the Plant Translocation Network including our objectives and plans, and membership see the links above.

Updates to come...

<img src="SF_image.png" class="img-fluid">

<ul>
  {% for post in posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
  </ul>
