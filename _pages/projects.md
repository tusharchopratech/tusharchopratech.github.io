---
# layout: archive
title: "Projects"
excerpt: "Projects"
permalink: /projects
author_profile: true
---



<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<style>
.all:hover, .machine_learning:hover, .software:hover  {
  cursor: pointer;
}
.underline{
    text-decoration:underline;
}
.list_item{
  display:flex; align-items: center; margin-bottom: 25px;
}
</style>

<script>

$(document).on("click", ".all", function(){
    $("#div_software").hide();
    $("#div_machine_learning").hide();
    $("#div_all").fadeIn();
    $(".all" ).css( "text-decoration", "underline" );
    $(".machine_learning" ).css( "text-decoration", "none" );
    $(".software" ).css( "text-decoration", "none" );
});

$(document).on("click", ".machine_learning", function(){
    $("#div_software").hide();
    $("#div_all").hide();
    $("#div_machine_learning").fadeIn();
    $(".all" ).css( "text-decoration", "none" );
    $(".machine_learning" ).css( "text-decoration", "underline" );
    $(".software" ).css( "text-decoration", "none" );
});

$(document).on("click", ".software", function(){
    $("#div_machine_learning").hide();
    $("#div_all").hide();
    $("#div_software").fadeIn();
    $(".all" ).css( "text-decoration", "none" );
    $(".machine_learning" ).css( "text-decoration", "none" );
    $(".software" ).css( "text-decoration", "underline" );
});

$( document ).ready(function() {
    $(".all" ).css( "text-decoration", "underline" );
    $("#div_machine_learning").hide();
    $("#div_software").hide();
});

</script>

<div style="display: flex;  justify-content: flex-end;">
  <p class="all">All</p>  
    &nbsp;
  <p>|</p>
    &nbsp;
  <p class="machine_learning">Machine Learning</p>
    &nbsp;
  <p>|</p>
    &nbsp;
<p class="software">Software</p> 
</div>


<div id="div_all" markdown="1">

<!-- 
<div style="display:flex;">

  <div style="display:flex; align-items: center; flex-direction:column; flex=1; width:100%;">
      <div style="padding-right: 20px;">
        <img style="float: left; width: auto;  height:200px; border-radius: 20%;" src="/images/profile_pic.png">
      </div>
      <div style="flex: 2;">
        <h2 style="margin-top: 0px;">Impulse</h2>
        <p>It improves user's reaction time of mouse click for gamers. The system consist of both hardware and software communicated via serial port.</p>
        <p>Stack - Electron/React/Node Js, C/C++, Python, TCP Sockets, Microsoft Win32</p>
      </div>
  </div>

  <div style="display:flex; align-items: center; flex-direction:column; flex=1; width:100%;">
      <div style="padding-right: 20px;">
        <img style="float: left; width: auto;  height:200px; border-radius: 20%;" src="/images/profile_pic.png">
      </div>
      <div style="flex: 2;">
        <h2 style="margin-top: 0px;"> Machine Learning</h2>
        <li>Tushar Chopra</li>
        <li>Tushar Chopra</li>
      </div>
  </div>


</div> -->



Impulse 
------
<p>Bionic glove powered by Machine Learning and surface EMG to predict mouse clicks in gaming. This gives tacatitcal advantage to gamers by reducing the reaction delay of gamers upto 80ms.</p>
<a href="https://www.brinkbionics.com/" rel="some text"> <img src="/images/link.png" width="30" style="box-shadow: none;"></a> | Stack - C/C++, Python, Sklearn, Electron/React/Node Js, TCP Sockets, Microsoft Win32.
<!-- * First user do a training session, which is used to train machine leaning parameters, followed by real time game play. The gamers can click upto 80ms faster in time. -->

Shorthand Practice 
------
<p>Shorthand language learning platform for journalists and court typewriters. Android app is used as front end to deliver  audio recordings dictations and ratings, supported by Django backend.</p>
<a href="https://play.google.com/store/apps/details?id=com.shorthand&hl=en" rel="some text"> <img src="/images/google-play-6.png" width="40" style="box-shadow: none;"></a> | Stack - Python, DJango, Android, React, Postgresql, Rest Services, Digital Ocean.

Sourc. 
------
<p>Media app to deliver user-specific trending social media content and news in less than 60 words. System was supported by the team of data scientists, who provide content using REST services.</p>
<a href="https://apkpremier.com/details/co-sourc" rel="some text"> <img src="/images/google-play-6.png" width="40" style="box-shadow: none;"></a> | Stack - Android, Html/Javacript, GIF, Sqlite, Rest Services, AWS, Youtube.

SnipClip
------
<p>Snipclip provides video snippets (< 30 secs) of trending social media videos in Youtube, Vimeo and Facebook based on the algorithm patented by the company.</p>
<a href="https://apkpure.com/snipclip/co.snipclipper.snipclip" rel="some text"> <img src="/images/google-play-6.png" width="40" style="box-shadow: none;"></a> | Stack - Android, Html/Javacript, Sqlite, Rest Services, AWS,  Youtube, Vimeo.

Curefy 
------
<p>Online medical consultation app involves calling, chatting and document sharing with doctors, supported by a companion doctor’s app to give consultations and services to patients.</p>
<a href="https://play.google.com/store/apps/details?id=in.curefy.curefyn&hl=it" rel="some text"> <img src="/images/google-play-6.png" width="40" style="box-shadow: none;"></a> | Stack - Go, Postgresql, Entity-Boundary-Interactor, Android, Rest Services, Azure.

Curefy Doctor's Panel 
------
<p>Mobile app and web panel used to manage medical records, assign orders and team management and for billing for a startup in Delhi, IN.</p>
<a href="https://docpanel.curefy.in/" rel="some text"> <img src="/images/link.png" width="30" style="box-shadow: none;"></a> <a href="https://play.google.com/store/apps/details?id=com.ssqtech.curefypanel&hl=en_GB" rel="some text"> <img src="/images/google-play-6.png" width="40" style="box-shadow: none;"></a> | Stack - Go, Google Polymer, React, Rest Services, Web Sockets, Microsoft Azure.

Buckler Security 
------
<p>Used to locate mobile device or person under odd real life circumstances. Consist of 4 features which controls ringer-silent mode preferences and location informations of the device.</p>
<a href="https://apkcombo.com/buckler-android/com.bucklerandroid/" rel="some text"> <img src="/images/google-play-6.png" width="40" style="box-shadow: none;"></a> | Stack - Android, Broadcast Receivers, Shared Preferences, Sqlite.

Nuclear Hazard Zone Estimation
------
<p>Estimates the immediate hazardous zone in a city due to nuclear accident. It takes square map, wind direction, intensity of explosion etc as input to predict the zone to evacuate first.</p>
<a href="https://drdo.gov.in/labs-and-establishments/institute-systems-studies-analyses-issa" rel="some text"> <img src="/images/link.png" width="30" style="box-shadow: none;"></a> | Stack - Java, Swings, MS Access.

College Fest and Events
------
<p>Mobile app to deliver information about upcoming festivals in various universities in India. Web-crawlers were used to scrape information from various website and delivered via REST APIs.</p>
<a href="https://apkpure.com/college-fest-n-events/example.collegefest" rel="some text"> <img src="/images/google-play-6.png" width="40" style="box-shadow: none;"></a> | Stack - Android, Sqlite, REST, Java.

Medicom 
------
<p>Identifies the generic drug of the prescribed medicine by doctor, then suggest its cheaper alternative. Android app is used as consumer deliverable.</p>
University Contest | Stack - Android, Sqlite, REST, Java.


Other
------
Stack - Arduino, ICs, Electronics, Java, php, Android, mysql, multithreading, REST API, ORM etc.
* *<u>Vocab 15</u>* - Provides combined form of english vocabulary words. Similar words together and their opposites are togther, which facilitates the speed of learning.
* *<u>RoboSapians</u>* - Robots made for a contest whose theme was “Rescuing People from Kedarnath Tragedy” in India. Project had 2 robots, one was autonomous and other was mechanical.
* *<u>Line Follower Robot</u>* -  self explainatory
* *<u>Maze Solving Robot</u>* -  self explainatory
* *<u>Clap Switch</u>* -  self explainatory
* *<u>Digital Dice</u>* -  self explainatory
* *<u>Gre Verbal Sentence Completion</u>* -  self explainatory
* *<u>Reading Comprehensions</u>* - self explaintory
* *<u>Hotel Management</u>* etc. 


</div>

<div id="div_machine_learning" markdown="1">
<!-- Impulse
------
<a href="https://play.google.com/store/apps/details?id=com.shorthand&hl=en" rel="some text"> <img src="/images/google-play-6.png" width="40" style="box-shadow: none;"></a> | Stack - Python, DJango, Android, Javascript, React, Postgresql.
* Android app for the students learning Shorthand language, provides online dictations for practice with solutions. Over 400K users at Google Play Store.
* Tools: Crashlytics, Google Analytics, Ngnix, Cloudflare, FCM (Former GCM) notifications, In-app purchase etc. -->
</div>

<div id="div_software" markdown="1">
<!-- Shorthand Practice 
------
<a href="https://play.google.com/store/apps/details?id=com.shorthand&hl=en" rel="some text"> <img src="/images/google-play-6.png" width="40" style="box-shadow: none;"></a> | Stack - Python, DJango, Android, Javascript, React, Postgresql.
* Android app for the students learning Shorthand language, provides online dictations for practice with solutions. Over 400K users at Google Play Store.
* Tools: Crashlytics, Google Analytics, Ngnix, Cloudflare, FCM (Former GCM) notifications, In-app purchase etc. -->
</div>




