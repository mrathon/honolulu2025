---
title: "About"
bg: clrnew
color: about
fa-icon: info-circle
iconclr: '#428bca'
titleclr: '#428bca'
---

<center><img src="https://github.com/mrathon/honolulu2025/blob/master/img/mrathon_new.png?raw=true" style="height:300px;"></center>

<p style ="text-align: center; font-weight: bold; font-size:24px;"> We organized MRathon 2025 in collaboration with the <a href="https://sites.google.com/view/mrshackathon2024/" style="color:blue;"> MRS Hackathon </a>, creating an excellent atmosphere to enable interaction between different sub-communities of ISMRM.</p>

<p style ="text-align: center; font-weight: bold; font-size:24px;"> That being said, both events will have their own hackathon tracks. For MRathon 2025, this year's theme will be on creating next-generation publications for cutting-edge MRI research. For the MRS Hackathon, please see <a href="https://sites.google.com/view/mrshackathon2024/" style="color:blue;"> here </a>.</p>

<h3 style ="text-align: center;"> For MRathon 2025, this year's theme will be on creating next-generation publications for cutting-edge MRI research.</h3> 

<p style ="text-align: center;"> For the MRS Hackathon, please see <a href="https://sites.google.com/view/mrshackathon2024/" style="color:blue;"> here </a>.</p>

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

