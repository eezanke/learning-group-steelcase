---
ID: 119546
post_title: CLARA-OVERLAY-MODEL-TEST
author: Eric Zanke
post_date: 2017-03-23 19:18:03
post_excerpt: ""
layout: page
permalink: >
  http://newlearning.steelcase.com/product/clara-overlay-model-test/
published: true
eg_sources_html5_mp4:
  - ""
eg_sources_html5_ogv:
  - ""
eg_sources_html5_webm:
  - ""
eg_sources_youtube:
  - ""
eg_sources_vimeo:
  - ""
eg_sources_wistia:
  - ""
eg_sources_image:
  - ""
eg_sources_iframe:
  - ""
eg_sources_soundcloud:
  - ""
eg_vimeo_ratio:
  - "0"
eg_youtube_ratio:
  - "0"
eg_wistia_ratio:
  - "0"
eg_html5_ratio:
  - "0"
eg_soundcloud_ratio:
  - "0"
eg_settings_custom_meta_skin:
  - ""
eg_settings_custom_meta_element:
  - ""
eg_settings_custom_meta_setting:
  - ""
eg_settings_custom_meta_style:
  - ""
eg-my-custom-url:
  - ""
eg-lightbox-iframe:
  - ""
---
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>CLARA-OVERLAY-MODEL</title>


  <!-- CSS -->

  <style type="text/css">
  	
  	html{
  		font-size:150%;
  	}

  	body{
  		padding:0!important;
		margin:0!important;
  	}

  	#wrapper{
		width:98%;
		max-width:1080px;
		height:auto;
		margin:0 auto;
		display:table;
  	}

  	
  	#clara-embed{
  		width:600px;
  		height:400px;
  		width: 700px;
	    width: 100%;
	    height: 500px;
	    max-height:auto;
  		
  	}
  	
  	#content, #unique {
  		display:table-cell;
  		width:48%;
  		
  	}

  	#unique {
		visibility: hidden; 
		width:42%;
		vertical-align:top;

		}
	#text{
		
		font-family:Roboto, Arial, Helvetica, sans-serif;
		font-size:.75rem;
		line-height:150%;
		width:98%;
		margin:2% auto 0 auto;
	}
	p{
	}


	input{border:0;}

	button{
		padding:1.8% 2%;
		margin: 0 1% 1% 0;
		background-color:#666;
		color:#ffffff;
		border:0;
		font-size:1.8rem;
		}
	button:hover{
		background-color:#333;
	}
	button:focus, button:active{
		outline:0;
	}
	@media screen and (min-width: 1366px) {

	}

	@media screen and (min-width: 1280px) {

	}

	@media screen and (min-width: 1200px) {

	}

	@media screen and (min-width: 1080px) {

	}

	@media screen and (min-width: 960px) {

	}


	@media screen and (min-width: 768px) { 
		#content, #unique{
			display:block!important;
			width:100%!important;
		}
	}
	@media screen and (min-width: 480px) { 
		#text{
			font-size:1.5rem;
		}
	}

	@media screen and (min-width: 320px) {
		#text{
			font-size:1.5rem;
		}
	}
	

	
	
  </style>
  
</head>

<body>
<div id="wrapper">
	<div id="content">
	  <div id="clara-embed"></div>
	</div>

	<div id="unique">
	  <p id="text"><!-- INSIDE THIS GOES THE DYNAMIC TEXT --></p>
	</div>
</div>		

<script src="https://steelcase.clara.io/js/claraplayer.min.js"></script> 


 <!-- JS -->
  <script>

const content = {
  'Designed for Wellbeing': 
    'Something about Designed for Wellbeing. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.',

  'Workplace Wellbeing': 
    'something about Workplace Wellbeing',

  'Encouraging Health Postures': 
    'something about Encouraging Health Postures',

  'Antimicrobial': 
    'Something about Antimicrobial. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.',

  'Collaboration Button': 
    'something about Collaboration Button',

  'Variety of Cable Management Options': 
    'something about Variety of Cable Management Options',

  'Obstruction Sensing': 
    'something about Obstruction Sensing',

  'Health Conscious Environment': 
    'something about Health Conscious Environment',
};

const textDiv = document.getElementById('unique');
const textEl = document.getElementById('text');


var clara = claraplayer('clara-embed'); 
clara.on('loaded', function() { console.log('Clara player is loaded and ready'); }); 
clara.sceneIO.fetchAndUse("1613b124-6f9f-48ca-a2c5-52e40db046aa"); 
clara.on('loaded', () => { 
  const cameras = clara.scene.getAll({type: 'Camera', property: 'name'}); 
  for(let id in cameras) { 
    console.log(cameras[id]);
    let button = document.createElement('button'); 
    button.innerText = cameras[id]; 
    button.onclick = (ev) => { 
      clara.player.animateCameraTo(id, 500); 
      showTextForCamera(cameras[id]);
    }
    document.getElementById('content').appendChild(button); 
  } 
});

function showTextForCamera(name) {
  textDiv.style.visibility = 'visible';
  textEl.innerText = content[name] || '';
}

</script>
</body>
</html>