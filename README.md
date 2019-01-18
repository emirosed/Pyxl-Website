<!DOCTYPE html>
<html>
<title>Pyxl Clan Website</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}
body, html {
    height: 100%;
    line-height: 1.8;
}
/* Full height image header */
.bgimg-1 {
    background-position: center;
    background-size: cover;
    background-image: url("pyxlbanner.png");
    min-height: 100%;
}
.w3-bar .w3-button {
    padding: 16px;
}
    .card{
  flex: 1;
   display: inline-flex;
  display: grid;
    height: 700px;
  flex-direction: column;
  justify-content: space-between;
    justify-content: space-around;
        
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
}
    }
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-card" id="myNavbar">
    <a href="#home" class="w3-bar-item w3-button w3-wide">PYXL CLAN</a>
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small">
      <a href="#about" class="w3-bar-item w3-button">ABOUT</a>
      <a href="#team" class="w3-bar-item w3-button"><i class="fa fa-user"></i> TEAM</a>
      <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-envelope"></i> CONTACT</a>
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">ABOUT</a>
  <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">TEAM</a>
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTACT</a>
</nav>

<!-- Header with full-height image -->
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-left w3-text-white" style="padding:48px">
  </div> 
  <div class="w3-display-bottomleft w3-text-grey w3-large" style="padding:24px 48px">
    <i class="fa fa-twitter w3-hover-opacity"></i>
  </div>
</header>

<!-- About Section -->
<div class="w3-container" style="padding:128px 16px" id="about">
  <h3 class="w3-center">ABOUT PYXL CLAN</h3>
  <p class="w3-center w3-large">We are a gaming team that strives to embody integrity, accountability, adaptability, positivity, and gracious professionalism. However we are also a family that is full of support for our team-mates and fans in the gaming world. Our members work hard to improve as gamers and team members. Pyxl is currently a growing clan and we are dedicated to make a name for ourselves, so check out our team and spread the word. </p>
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
</div>

<!-- Promo Section -->
<div class="w3-container w3-light-grey" style="padding:128px 16px">
  <div class="w3-row-padding w3-grayscale">
    <div class="w3-col m6">
      <h3>WE PLAY GAMES</h3>
      <p> We are a team that is mostly comprised of fortnite players and has a focus on fortnite gaming and streaming. However, members are open to playing and streaming games other than fortnite as well.</p>
    </div>
    <div class="w3-col m6">
      <img class="w3-image w3-round-large" src="fortniteimg1.jpg" alt="fortniteimg" width="700" height="394">
    </div>
  </div>
</div>

<!-- Team Section1 -->
<div class="w3-container" style="padding:128px 16px" id="team">
  <h3 class="w3-center">THE TEAM</h3>
  <div class="w3-row-padding w3-grayscale" style="margin-top:64px">
      
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/alecohn" target="_blank"><img src="pyxlalecohn.png" alt="alec" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl AlecOhn</h3>
          <p class="w3-opacity">Founder & Leader</p>
          <p>Alec is 19 years old. He plays Fortnite, Roblox, R6 Siege, and CS:GO. He loves gaming because of the positive escape it can provide from the negativity of the outside world. In his free-time he likes listening to music.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/" target="_blank"><img src="pyxlreguluh.png" alt="reguluh" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Reguluh</h3>
          <p class="w3-opacity">Member</p>
          <p>Reguluh is 18 years old. She plays Fortnite and Black Ops. She loves gaming because its the only thing that truly makes her happy nowadays and it’s super fun and she meets so many great people. In her free-time she likes to paint and draw, or go out with friends.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/blitzgirl007" target="_blank"><img src="pyxlblitzgirl.png" alt="blitz" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl BlitzGirl</h3>
          <p class="w3-opacity">Manager & Leader</p>
          <p> BlitzGirl is 17 years old. She plays Fortnite, Diablo 3, Dota 2, and Mariokart. She loves gaming because of the supportive, caring community and the escape they provide. In her free-time she likes to surf and build robots.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/steezy_tv" target="_blank"><img src="pyxlsteezy.png" alt="steezy" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Steezy</h3>
          <p class="w3-opacity">Member</p>
          <p>Steezy is 23 years old. He plays Fortnite, League of Legends, PUBG, Overwatch, and more. He likes gaming because it’s fun and helps cope with stress. In his free-time he enjoys exercising and going to parties with friends.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/yezzeh" target="_blank"><img src="pyxlyezzeh.png" alt="yezzeh" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Yezzeh</h3>
          <p class="w3-opacity">Manager & Member</p>
          <p>Yezzeh is 21 years old. He plays Fortnite and World of Warcraft. He loves gaming because it’s an escape from real life, and you can get immersed in any world. In his free-time he likes to make music with friends and watch sports.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/ixamot" target="_blank"><img src="pyxlxamot.png" alt="xamot" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Xamot</h3>
          <p class="w3-opacity">Member</p>
          <p>Xamot is 19 years old. He plays Fortnite, Black Ops, Skyrim, and R6 Siege. He loves gaming because it helps him get away from everything. In his free-time he likes to go out with friends and spend time with his girlfriend and dogs.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/" target="_blank"><img src="pyxlkyle.png" alt="kyle" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Kyle</h3>
          <p class="w3-opacity">Member</p>
          <p>Kyle is 16 years old. He plays Fortnite, CS:GO, R6 Siege, and more. He loves gaming because he was exposed at a young age and became a natural. In his free-time he likes to play piano and baseball.</p>
        </div>
      </div>
    </div>
       <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/alpha_galixqe" target="_blank"><img src="pyxlgalixqe.png" alt="galixqe" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Galixqe</h3>
          <p class="w3-opacity">Member</p>
          <p>Galixqe is 13 years old. He plays Fortnite, Overwatch, and Battlefield 1. He loves gaming because its fun, and very team based and you make a lot of friends. In his free-time he likes playing trumpet and football.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/theswolegamer_" target="_blank"><img src="pyxlswole.png" alt="swolegamer" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl TheSwoleGamer</h3>
          <p class="w3-opacity">Member</p>
          <p>TheSwoleGamer is 23 years old. He plays Fortnite and a little Minecraft. He loves gaming because of the community and how he can meet new people and rekindle old friendships. In his free-time he loves fitness.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/elite360" target="_blank"><img src="pyxlelite360.png" alt="elite360" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Elite360</h3>
          <p class="w3-opacity">Manager & Member</p>
          <p>Elite360 is 14 years old. He plays Fortnite and Call of Duty. He loves gaming because they’re made to have fun and he likes to have fun playing them. In his free-time he likes to play sports and exercise and hang out with family.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/alexamcfn" target="_blank"><img src="pyxlalexa.png" alt="alexa" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Alexa</h3>
          <p class="w3-opacity">Social Media Manager & Member</p>
          <p>Alexa is 15 years old. She plays Fortnite, Black Ops, and occasionally Minecraft. She loves gaming because it's a way for her to escape from real world stress. In her free-time she likes to sing, play guitar, and make video edits for her instagram.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/mrfishey904" target="_blank"><img src="pyxlmrfishy.png" alt="mrfishy" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Mr.Fishy</h3>
          <p class="w3-opacity">Moderator & Member</p>
          <p>Mr. Fishy is 17 years old. He mainly plays Fortnite. He loves gaming because it gives him time to cool down, chill out, and have fun. In his free-time he enjoys singing and listening to music as well as drawing and sketching. </p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/javipoisonk1l1" target="_blank"><img src="pyxlpoison.png" alt="poison" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Poison</h3>
          <p class="w3-opacity">Member</p>
          <p>Poison is 15 years old. He plays Fortnite and Black Ops. He loves gaming because it’s something his dad showed him when he was barely 5 years old on the PS2. In his free-time, his favorite thing to do is just read a book.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/banditeh" target="_blank"><img src="pyxlbanditeh.png" alt="banditeh" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Banditeh</h3>
          <p class="w3-opacity">Analyst & Member</p>
          <p>Banditeh is 13 years old. He plays Fortnite and CS:GO. He loves gaming because he enjoys being good at them, winning games, and they’re overall fun. In his free-time he plays soccer.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/cpu_express" target="_blank"><img src="pyxlricko.png" alt="ricko" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Ricko</h3>
          <p class="w3-opacity">Editor & Member</p>
          <p>Ricko is 18 years old. He plays lot of different games and a talented video editor for the team. He loves gaming because it’s a nice way for him to connect with people and play with friends. In his free-time he enjoys listening to music and editing videos.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/hazeylive" target="_blank"><img src="pyxlhazey.png" alt="hazey" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Hazey</h3>
          <p class="w3-opacity">Member</p>
          <p>Hazey is 13 years old. He plays Fortnite. He loves gaming because he loves the satisfaction of beating a challenge and sometimes you meet really cool people. In his free-time he plays soccer and loves hanging out with friends.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/" target="_blank"><img src="pyxlenvy.png" alt="envy" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Envy</h3>
          <p class="w3-opacity">Member</p>
          <p>Envy is 13 years old. He plays Fornite, Black Ops, League of Legends, and Red Dead Redemption. He loves gaming because he started from a young age and wants to become a big streamer in the future. In his free-time he likes to play football.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv" target="_blank"><img src="pyxlchewy.png" alt="chewy" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Chewy</h3>
          <p class="w3-opacity">Member</p>
          <p>Chewy is 9 years old. He mainly plays Fortnite. He loves gaming because there are more interesting new games released every and because he can meet more people that help him with his gaming and are fun to play with. In his free-time he likes playing board games, chatting with friends and watching other streamers.</p>
        </div>
      </div>
    </div>
      <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/nic_fleury" target="_blank"><img src="pyxlnicfleury.png" alt="fleury" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Nic Fleury</h3>
          <p class="w3-opacity">Member</p>
          <p>Nic Fleury is 18 years old. He plays Fortnite as well as any other games with a good storyline and gameplay. He loves gaming because he enjoys talking with others and playing games with other people for the fun of it. In his free-time he likes learning to play the piano and guitar and just hang out with friends.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv/" target="_blank"><img src="pyxlunite.png" alt="unite" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Unite</h3>
          <p class="w3-opacity">Moderator & Member</p>
          <p>Unite is 17 years old. He plays Fifa and Fortnite. He loves gaming because he’s had a passion for games from a young age. In his free-time he enjoys playing soccer and table tennis or hanging out and watching Netflix.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="card">
          <a href="https://www.twitch.tv" target="_blank"><img src="pyxlhybrid.png" alt="hybrid" style="width:100%"></a>
        <div class="w3-container">
          <h3>Pyxl Hybrid</h3>
          <p class="w3-opacity">Member</p>
          <p>Hybrid is 16 years old. He plays Fortnite, Black Ops, and NBA2K. He loves gaming because he can talk to people without judgement and it’s really fun. In his free-time he enjoys playing basketball.</p>
        </div>
      </div>
    </div>
  </div>
</div>
      
      <!-- Discord Section -->
<div class="w3-container w3-light-grey" style="padding:120px 16px">
  <div class="w3-row-padding">
    <div class="w3-col m6">
      <h3>JOIN THE DISCORD</h3>
      <p>Come support us on our discord! Join us in games, talk to us in voice chat or in the text channels, and tryout to be a member and part of the family. Stay up to date with events, tournaments, and everything Pyxl!</p>
    </div>
    <div class="w3-col m6">
      <iframe src="https://discordapp.com/widget?id=513439813207064576&theme=dark" width="555" height="230" allowtransparency="true" frameborder="0"></iframe>
    </div>
  </div>
</div>
 <br>
      

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-xxlarge w3-black w3-padding-large w3-display-topright" title="Close Modal Image">×</span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- Contact Section -->
<div class="w3-container w3-light-grey" style="padding:128px 16px" id="contact">
  <h3 class="w3-center">CONTACT</h3>
  <p class="w3-center w3-large">Lets get in touch. Send us a message:</p>
  <div style="margin-top:48px">
    <p><i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i> Email: Pyxlclan123@gmail.com</p>
    <br>
    <form action="mailto:pyxlclan123@gmail.com" method="get">
      <p><input type="text" class="w3-input w3-border" type="text" placeholder="Name" required name="first_name"></p>
      <p><input type="text" class="w3-input w3-border" type="text" placeholder="Email" required name="email_address"></p>
      <p><input type="text" name="message" class="w3-input w3-border" type="text" placeholder="Message" required name="message"></p>
      <p>
        <button class="w3-button w3-black" type="submit" value="send">
          <i class="fa fa-paper-plane"><form method="post" action="send_mail.php"><p></p> </form> </i> SEND MESSAGE
        </button>
      </p>
    </form>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <button class="w3-xlarge w3-section w3-black" type="submit">
    <a href="https://twitter.com/Pyxlc"><i class="fa fa-twitter w3-hover-opacity"></a></i>
    </button>
     </footer>
      
<script>

// Toggle between showing and hiding the sidebar when clicking the menu icon
var mySidebar = document.getElementById("mySidebar");

function w3_open() {
    if (mySidebar.style.display === 'block') {
        mySidebar.style.display = 'none';
    } else {
        mySidebar.style.display = 'block';
    }
}

// Close the sidebar with the close button
function w3_close() {
    mySidebar.style.display = "none";
}
</script>

</body>
</html>
