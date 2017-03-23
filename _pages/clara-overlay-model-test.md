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
[et_pb_section admin_label="section"][et_pb_row admin_label="row"][et_pb_column type="4_4"][et_pb_code admin_label="Code"]&lt;meta charset=&quot;UTF-8&quot;&gt;
  &lt;title&gt;CLARA-OVERLAY-MODEL&lt;/title&gt;


  &lt;!-- CSS --&gt;

  &lt;style type=&quot;text/css&quot;&gt;
  	
  	#unique {
		visibility: hidden; 
		}

  &lt;/style&gt;
  

 
 



  &lt;div id=&quot;content&quot;&gt;
  &lt;div id=&quot;clara-embed&quot; style=&quot;width: 600px; height: 400px;&quot;&gt;&lt;/div&gt;
&lt;/div&gt;

&lt;div id=&quot;unique&quot;&gt;
  &lt;p id=&quot;text&quot;&gt;&lt;/p&gt;
&lt;/div&gt;

&lt;script src=&quot;https://steelcase.clara.io/js/claraplayer.min.js&quot;&gt;&lt;/script&gt;


 &lt;!-- JS --&gt;
  &lt;script&gt;
const content = {
  &#x27;Designed for Wellbeing&#x27;: 
    &#x27;something about Designed for Wellbeing&#x27;,
  &#x27;Workplace Wellbeing&#x27;: 
    &#x27;something about Workplace Wellbeing&#x27;,
  &#x27;Encouraging Health Postures&#x27;: 
    &#x27;something about Encouraging Health Postures&#x27;,
  &#x27;Antimicrobial&#x27;: 
    &#x27;something about Antimicrobial&#x27;,
  &#x27;Collaboration Button&#x27;: 
    &#x27;something about Collaboration Button&#x27;,
  &#x27;Variety of Cable Management Options&#x27;: 
    &#x27;something about Variety of Cable Management Options&#x27;,
  &#x27;Obstruction Sensing&#x27;: 
    &#x27;something about Obstruction Sensing&#x27;,
  &#x27;Health Conscious Environment&#x27;: 
    &#x27;something about Health Conscious Environment&#x27;,
};

const textDiv = document.getElementById(&#x27;unique&#x27;);
const textEl = document.getElementById(&#x27;text&#x27;);


var clara = claraplayer(&#x27;clara-embed&#x27;); 
clara.on(&#x27;loaded&#x27;, function() { console.log(&#x27;Clara player is loaded and ready&#x27;); }); 
clara.sceneIO.fetchAndUse(&quot;1613b124-6f9f-48ca-a2c5-52e40db046aa&quot;); 
clara.on(&#x27;loaded&#x27;, () =&gt; { 
  const cameras = clara.scene.getAll({type: &#x27;Camera&#x27;, property: &#x27;name&#x27;}); 
  for(let id in cameras) { 
    console.log(cameras[id]);
    let button = document.createElement(&#x27;button&#x27;); 
    button.innerText = cameras[id]; 
    button.onclick = (ev) =&gt; { 
      clara.player.animateCameraTo(id, 500); 
      showTextForCamera(cameras[id]);
    }
    document.getElementById(&#x27;content&#x27;).appendChild(button); 
  } 
});

function showTextForCamera(name) {
  textDiv.style.visibility = &#x27;visible&#x27;;
  textEl.innerText = content[name] || &#x27;&#x27;;
}
&lt;/script&gt;[/et_pb_code][/et_pb_column][/et_pb_row][/et_pb_section]