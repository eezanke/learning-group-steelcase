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
[et_pb_section admin_label="section"][et_pb_row admin_label="row" make_fullwidth="off" use_custom_width="off" width_unit="on" use_custom_gutter="off" padding_mobile="off" allow_player_pause="off" parallax="off" parallax_method="off" make_equal="off" parallax_1="off" parallax_method_1="off" padding_right_1="0px" padding_left_1="0px" padding_1_last_edited="on|phone" column_padding_mobile="off" custom_padding="|||0px" custom_padding_last_edited="on|desktop" custom_margin="50px|||"][et_pb_column type="4_4"][et_pb_text admin_label="Clara Dropdown Model" background_layout="light" text_orientation="left" use_border_color="off" border_color="#ffffff" border_style="solid"]

Clara Dropdown Model

<style type="text/css">
<p>#content > div {<br />  position: absolute;<br />  top: 0px;<br />  left: 650px;<br />  visibility: hidden;<br />}</p>
<p>@media (max-width: 700px) {<br />  #content > div {<br />    top: 500px;<br />    left: 0px;<br />  }<br />}</p>
<p>.italic {<br />  font-style: italic;<br />  font-size: 18px;<br />}</p>
<p>.normal {<br />  font-style: normal;<br />  font-size: 12px;<br />}</p>
<p>.oblique {<br />  font-style: oblique;<br />  font-size: 22px;<br />}</p>
</style>

&nbsp;

&nbsp;
<div id="player" style="width: 600px; height: 400px;"></div>
<div id="controls"></div>
<div id="content">
<div id="wellbeing" class="italic">

<img src="https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg" />
<ul>
 	<li>Coffee</li>
 	<li>Tea</li>
 	<li>Milk</li>
</ul>
</div>
<div id="workplace" class="normal">

<img src="https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg" />
<ul>
 	<li>Coffee</li>
 	<li>Tea</li>
 	<li>Milk</li>
</ul>
</div>
<div id="postures" class="oblique">

<img src="https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg" />
<ul>
 	<li>Coffee</li>
 	<li>Tea</li>
 	<li>Milk</li>
</ul>
</div>
<div id="antimicrobial" class="italic">

<img src="https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg" />
<ul>
 	<li>Coffee</li>
 	<li>Tea</li>
 	<li>Milk</li>
</ul>
</div>
<div id="collab" class="normal">

<img src="https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg" />
<ul>
 	<li>Coffee</li>
 	<li>Tea</li>
 	<li>Milk</li>
</ul>
</div>
<div id="cables" class="oblique">

<img src="https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg" />
<ul>
 	<li>Coffee</li>
 	<li>Tea</li>
 	<li>Milk</li>
</ul>
</div>
<div id="sensing" class="italic">

<img src="https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg" />
<ul>
 	<li>Coffee</li>
 	<li>Tea</li>
 	<li>Milk</li>
</ul>
</div>
<div id="health" class="normal">

<img src="https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg" />
<ul>
 	<li>Coffee</li>
 	<li>Tea</li>
 	<li>Milk</li>
</ul>
</div>
</div>
<script src="https://steelcase.clara.io/js/claraplayer.min.js"></script>

<script>
const ids = {
  '9db43c80-4671-4c85-b481-17d1b4c92c3b': 'wellbeing',
  '7774b92d-ba6b-44e8-b2e8-00a5e3c494d5': 'workplace',
  'e665f0d5-60e9-492f-b67c-9ff95fe6fb01': 'postures',
  'ea9d7ad8-0ebe-4dc7-892a-3b3d8ae5b66d': 'antimicrobial',
  '8766ff74-8d88-466e-ba06-46b87c0b1a66': 'collab',
  '64976508-875c-4d93-83f3-8335857ffe96': 'cables',
  '3a9b7cf9-6000-450c-a11e-ab194636c00c': 'sensing',
  '6f924f5c-80c7-4b0e-906e-48cb6f96747c': 'health',
};

const cameraSelect = document.getElementById('cameraSelect');
cameraSelect.onchange = function(ev) {
   var id = ev.target.value;
   var divs = document.getElementById('content').children;
   for(var i = 0; i < divs.length; i++) { var state = 'hidden'; if(divs[i].id === ids[ev.target.value]) state = 'visible'; divs[i].style.visibility = state; } clara.player.animateCameraTo(id, 500); } var clara = claraplayer('clara-embed'); clara.on('loaded', function() { console.log('Clara player is loaded and ready'); }); clara.sceneIO.fetchAndUse("1613b124-6f9f-48ca-a2c5-52e40db046aa"); clara.on('loaded', () => { 
  const cameras = clara.scene.getAll({type: 'Camera', property: 'name'}); 
  for(let id in cameras) { 
    cameraSelect.options[cameraSelect.options.length] = new Option(cameras[id], id);
  } 
  clara.player.hideTool('orbit');
  clara.player.hideTool('pan');
  clara.player.hideTool('zoom');
  clara.player.hideTool('home');
  clara.player.hideTool('fullscreen');
  clara.player.hideTool('VR mode');
});


</script>

&nbsp;

[/et_pb_text][/et_pb_column][/et_pb_row][et_pb_row admin_label="Row"][et_pb_column type="4_4"][et_pb_text admin_label="Text" background_layout="light" text_orientation="left" use_border_color="off" border_color="#ffffff" border_style="solid"]

[scormcloud.training:58e64f0555699]

[/et_pb_text][/et_pb_column][/et_pb_row][/et_pb_section]