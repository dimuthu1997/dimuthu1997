<a href="#"><img width="100%" height="auto" src="https://i.imgur.com/iXuL1HG.png" height="175px"/></a>


<script>
window.addEvent('domready', function(){

var location = '${user.State}'

	if(!$('welcomeBanner')){
		if(Cookie.read('slideDownWelcome') != "true"){

			var url = window.location.href;
			var site = '';
			if (url.contains('ventingdirect.com')){
				var siteColor = '#B1B1B1';
				var textColor = 'white';
				var bannerBg = 'url(/images/header/navbar.gif) #A2B033 top repeat-x';
				var borderColors = '#EFEFEF';
			} else if (url.contains('lightingdirect.com')){
				var siteColor = $('callCenterHours').getStyle('color');
				var textColor = 'white';
				var bannerBg = 'url(/images/header/navbar.gif) #C76F36 top repeat-x';
				var borderColors = '#EFEFEF';
				var site = 'lighting';
			} else if ((url.contains('ventingpipe.com'))){
				var siteColor = $('callCenterHours').getStyle('color');
				var textColor = 'white';
				var bannerBg = 'url(/images/header/navbar.gif) #393939 top repeat-x';
				var borderColors = '#CCC';
			} else if (url.contains('handlesets.com')){
				var siteColor = $('callCenterHours').getStyle('color');
				var textColor = 'white';
				var bannerBg = 'url(/images/header/navbar.gif) #800 top repeat-x';
				var borderColors = '#999';
			} else if (url.contains('pullsdirect.com')){
				var siteColor = $('callCenterHours').getStyle('color');
				var textColor = 'white';
				var bannerBg = 'url(/images/header/navbar.gif) #878868 top repeat-x';
				var borderColors = '#ccc';
			} else if (url.contains('build.com')){
				var siteColor = $('callCenterHours').getStyle('color');
				var textColor = '#2B2B2B';
				var bannerBg = 'url(/images/header/navbar.gif) #EFEFEF top repeat-x';
				var borderColors = '#CCC';
			} else if (url.contains('faucetdirect.com')){
				var siteColor = $('callCenterHours').getStyle('color');
				var textColor = $('callCenterHours').getStyle('color');
				var bannerBg = '#F0F6FE';
				var borderColors = '#6EAEF4';
			}
			var welcomeBanner = new Element('div', {
				'id' : 'welcomeBanner',
				'html' : '<span id="borderFoldleft"></span><span id="welcomeMessage">Pay no tax on your purchase except when shipping to California</span><div onmousedown="mboxTrack(\'header\', \'closeWelcome\');" id="closeButton">X</div><span id="borderFoldright"></span>'

			});

			$(welcomeBanner).inject($('max'), 'top');

			if ((url.contains('lightingdirect.com')) || (url.contains('faucetdirect.com')) || (url.contains('ventingdirect.com')) || (url.contains('pullsdirect.com'))){
				$('welcomeBanner').setStyle('margin-bottom', 0);
			}

			if (url.contains('handlesets.com')){
				$('welcomeBanner').setStyle('width', '1010px');
				$('welcomeBanner').setStyle('margin-left', '-8px');
			}


			$('welcomeMessage').setStyle('color', textColor);

			$('welcomeBanner').setStyle('border', '1px solid ' + borderColors);
			$('welcomeBanner').setStyle('background', bannerBg);

			$('closeButton').setStyle('background-color', 'white');
			$('closeButton').setStyle('color', siteColor);
			$('closeButton').setStyle('border', '2px solid ' + siteColor);

			$('borderFoldleft').setStyle('border-top', '8px solid ' + siteColor);

			$('borderFoldright').setStyle('border-top', '8px solid ' + siteColor);

			//add effects
			$('welcomeBanner').set('morph', {duration: 'long'});

			$('welcomeBanner').morph({'margin-top' : 2, 'top' : 0});


			$('closeButton').addEvent('click', function(e){
				e.stop();

				$('welcomeBanner').morph({'margin-top' : -35, 'top' : -5});

				Cookie.write('slideDownWelcome', true);
			});

		}

	}

});
</script>
<style>
	#welcomeBanner{
		border: 1px solid;
		height: 25px;
		margin-top: -35px;
		padding-top: 7px;
		width: 1011px;
		margin-left: -9px;
		position: relative;
		top: -5px;
		margin-bottom: 6px;
	}
	#welcomeMessage{
		float: center;
		color: red;
	}
	#closeButton{
		border-radius: 50%; 
		background-color: #FFF; 
		color: #603814; 
		float: right;
		width: 20px;
		margin-right: 10px;
		border: 2px solid #dbccbf;
		margin-top: -3px;
		padding-top: 1px;
		font-weight: bold;
		cursor: pointer;
	}
	#borderFoldleft{
		width: 0px;
		height: 0px;
		line-height: 0px;
		border-left: 7px solid transparent;
		border-top: 8px solid #937961;
		position: absolute;
		top: 100%;
		left: 0px;
	}
	#borderFoldright{
		width: 0px;
		height: 0px;
		line-height: 0px;
		border-right: 7px solid transparent;
		border-top: 8px solid #937961;
		position: absolute;
		top: 100%;
		right: 0;
	}

</style>










### <i>Hi there, 👋 I'm Dimuthu. A final-year undergraduate in the Department of Information Communication Technology at the Rajarata University of Sri Lanka.</i>
<p align="left"> <img src="https://komarev.com/ghpvc/?username=dimuthu1997&label=Profile%20views&color=0e75b6&style=flat" alt="dimuthu1997" /> </p>

- ✍ You can find my projects here 
- 🔭 I’m currently not involved in any project and willing to contribute to any. 
- 🌱 I’m currently learning and/or refreshing my knowledge on Object Oriented Programming in Java, MySQL and whatever possible.
- 👯 I’m looking to collaborate on open source
- 💬 Ask me about Anything here. If it is something I know, I can help you!


<br />



---

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/dimuthu-dilshan-204351166/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="rishav-chanda-b89a791b3" height="30" width="40" /></a>
<a href="https://www.instagram.com/dimuthudilshan1997/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="rishav_chanda" height="30" width="40" /></a>
<a href="https://www.youtube.com/channel/UCQ6Gnkp2yKaJwxAkS_ifmIQ" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="rishav chanda" height="30" width="40" /></a>
</p>
<br />



---

<h3 align="left">Languages and Tools:</h3>
<p align="left"> </a> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://flutter.dev" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/> </a>  <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>  <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.adobe.com/in/products/illustrator.html" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://kotlinlang.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="kotlin" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> <a href="https://opencv.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://unity.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/unity3d/unity3d-icon.svg" alt="unity" width="40" height="40"/> </a> <a href="https://www.adobe.com/products/xd.html" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/adobe-xd.svg" alt="xd" width="40" height="40"/> </a> </p>
<br />

---





[instagram]: https://www.instagram.com/holistic_developer/

[linkedin]:  https://www.linkedin.com/in/dimuthu-dilshan-204351166/









### GitHub Stats:
![dimuthu1997's GitHub stats](https://github-readme-stats.vercel.app/api?username=dimuthu1997&show_icons=true&theme=radical)
<br />
<br />



---
### Most Used Languages:
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=dimuthu1997&layout=compact)](https://github.com/dimuthu1997/github-readme-stats)
















