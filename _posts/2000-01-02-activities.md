---
title: "About"
bg: clrnew
color: about
fa-icon: info-circle
iconclr: '#428bca'
titleclr: '#428bca'
---

# A hackathon for increasing MRI accessibility

### 2-3 May 2024

<p style ="text-align: center; font-weight: bold; font-size:24px;"> We organized MRathon 2024 in collaboration with the <a href="https://ezymri-nerdfest.sciencesconf.org/" style="color:blue;"> ezyMRI NerdFest </a>, focusing on the increasing the accessibility of MRI through open-source and vendor-neutral pulse sequence programming.</p>

<center>
<p style ="text-align: center;  font-size:20px;">MRathon aims to bring together experts to share knowledge and collaborate on new solutions for ensuring transparency and accessibility in MRI research.</p>
 </center>
<hr>
 <h3>A stellar list of MRI experts</h3>

 <p style ="text-align: center;  font-size:20px;"> Experts who specialize in implementing cutting-edge research into open-source projects will be present during the hackathon to offer valuable insights on the latest developments in the vendor-neutral ecosystem. </p>

<div class="team" style="margin-top:10px;">
<div class="row" style="justify-content:center;">
{% for person in site.data.committee.speakers %}
<div class="col-sm-2">
<center>
<div class="team-player">
    <img src="img/organization/{{ person.image }}" alt="Thumbnail Image" class="img-raised img-circle" style="width:100px;height:100px;border-radius: 50%;">
    <h5 class="title" style="color: black;">{{ person.name }}<br>
        <small class="text-muted" style="color: black;">{{ person.affiliation }}</small>
    </h5>
    <!-- <p style="color: darkgray;"> {{ person.affiliation }}</p> -->
</div>
</center>
</div>
  {% endfor %}

<div>
<div>
<hr>
<center>
 <h3>A sprint to push boundaries for collective creativity</h3>

 <p style ="text-align: center;  font-size:20px;">Participants who would like to work on a coding project are welcome to submit their project idea for making MRI research more accessible!</p>
</center>

