---
layout: archive
title: "Research"
permalink: /publications/
sitemap: false
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %} -->

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'pPublications')" id="pPublicationsDefaultOpen">Publications</button>
  <button class="tablinks" onclick="openCity(event, 'pPatents')">Patents</button>
</div>

<!-- Tab content -->
<div id="pPublications" class="tabcontent" markdown="1">

**Analysing the Extent of Misinformation in Cancer Related Tweets**  
*ICWSM 2020* (to appear)  
Rakesh Bal, Sayan Sinha, Swastika Dutta, Rishabh Joshi, <ins> Sayan Ghosh </ins>, Ritam Dutt  
[[pdf]](https://arxiv.org/pdf/2003.13657.pdf)  

**Exploring Color Variations for Vector Graphics**  
*ACM SIGGRAPH 2019 (Poster)*  
<ins> Sayan Ghosh </ins>, Jose Echevarria, Vineet Batra, Ankit Phogat  
[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3306214.3338552)  

**DeepTagRec: A Content-cum-User based Tag Recommendation Framework for Stack Overflow**  
*ECIR 2018*  
Suman Kalyan Maity, Abhishek Panigrahi, <ins> Sayan Ghosh </ins>, Arundhati Banerjee, Pawan Goyal, Animesh Mukherjee  
[[pdf]](https://arxiv.org/pdf/1903.03941.pdf) [[code]](https://github.com/b18arundhati/DeepTagRec-A-Content-cum-User-based-Tag-Recommendation-Framework-for-Stack-Overflow)  

**Public Sphere 2.0: Targeted Commenting in Online News Media**  
*ECIR 2018*  
Ankan Mullick, <ins> Sayan Ghosh </ins>, Ritam Dutt, Avijit Ghosh, Abhijnan Chakraborty  
[[pdf]](https://arxiv.org/pdf/1902.07946.pdf)  
Won best poster presentation award [[ECIR 2019 awards list]](http://ecir2019.org/best-paper-awards/)

**QoS-Aware Dynamic Caching for Destroyed Virtual Machines in Sensor-Cloud Architecture**  
*ICDCN 2018*  
Arijit Roy, Sudip Misra, <ins> Sayan Ghosh </ins>  
[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3154273.3154341)  

**Mining Twitter and Taxi Data for Predicting Taxi Pickup Hotspots**  
*ASONAM 2017*  
Sankarshan Mridha, <ins> Sayan Ghosh </ins>, Robin Singh, Sourangshu Bhattacharya, Niloy Ganguly  
[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3110025.3110106)  

</div>

<div id="pPatents" class="tabcontent" markdown="1">

**Flow-Based Color Transfer from Source Graphic to Target Graphic**  
Ankit Phogat, <ins> Sayan Ghosh </ins>, Vineet Batra, Stephen DiVerdi, Scott Cohen  
*Filed Aug 2019*

**Weighted Color Palette Generation**  
Ankit Phogat, <ins> Sayan Ghosh </ins>, Vineet Batra
*Filed Nov 2019*

</div>



<script>
document.getElementById("pPublicationsDefaultOpen").click();
function openCity(evt, cityName) {
  // Declare all variables
  var i, tabcontent, tablinks;

  // Get all elements with class="tabcontent" and hide them
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }

  // Get all elements with class="tablinks" and remove the class "active"
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }

  // Show the current tab, and add an "active" class to the button that opened the tab
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>