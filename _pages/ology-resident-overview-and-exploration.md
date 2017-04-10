---
ID: 119546
post_title: 'Ology Resident: Overview and Exploration'
author: Eric Zanke
post_date: 2017-03-23 19:18:03
post_excerpt: ""
layout: page
permalink: >
  http://newlearning.steelcase.com/product/ology-resident-overview-and-exploration/
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
[et_pb_section admin_label="section"][et_pb_row admin_label="row" make_fullwidth="off" use_custom_width="off" width_unit="on" use_custom_gutter="off" padding_mobile="off" allow_player_pause="off" parallax="off" parallax_method="off" make_equal="off" parallax_1="off" parallax_method_1="off" padding_right_1="0px" padding_left_1="0px" padding_1_last_edited="on|phone" column_padding_mobile="off" custom_padding="|||0px" custom_padding_last_edited="on|desktop" custom_margin="50px|||"][et_pb_column type="4_4"][et_pb_text admin_label="Text" background_layout="light" text_orientation="left" use_border_color="off" border_color="#ffffff" border_style="solid"]

<h1>Ology Resident</h1>
Ology height-adjustable desks support the physiology and biology of workers to make the workplace a more health-conscious environment.

[/et_pb_text][et_pb_code admin_label="Code"]&lt;meta charset=&quot;utf-8&quot;&gt;
&lt;title&gt;Clara Dropdown Model&lt;/title&gt;
&lt;style type=&quot;text/css&quot;&gt;


#content &gt; div {
  position: absolute;
  top: 0px;
  left: 650px;
  visibility: hidden;
  padding-top:2rem;
}

@media (max-width: 700px) {
  #content &gt; div {
    top: 500px;
    left: 0px;
  }
}


.italic {
  font-style: italic;
  font-size: 18px;
}

.normal {
  font-style: normal;
  font-size: 12px;
}

.oblique {
  font-style: oblique;
  font-size: 22px;
}

/* MODAL WINDOW STYLES */
* {
  -webkit-box-sizing:border-box;
  -moz-box-sizing:border-box;
  box-sizing:border-box;
}
html, body {
  height: 100%;
}
.container {
  display: table;
  width: 100%;
  height: 100%;
}
.interior {
  display: table-cell;
  /*vertical-align: middle;
  text-align: center;*/
  padding-top:1rem;
}
body {
  font:14px/1.5 sans-serif;
  padding: 2rem;
  /*background-color: #ffffff;*/
}
.btn {
  background-color: #333;
  padding: 1em 3em;
  border-radius: 3px;
  color: #ffffff;
  text-decoration: none;
  z-index:10000;
}
.modal-window {
  position:fixed;
  background-color: rgba(0,0,0,0.5);
  top:0;
  right:0;
  bottom:0;
  left:0;
  z-index:999;
  opacity:0;
  pointer-events:none;
  -webkit-transition:all 0.3s;
  -moz-transition:all 0.3s;
  transition:all 0.3s;
}
.modal-window:target {
  opacity:1;
  pointer-events:auto;
}
.modal-window&gt;div {
  max-width:1024px;
  position:relative;
  margin:10% auto;
  padding:2rem;
  background:#fff;
  color:#444;
}
.modal-window header {
  font-weight:bold;
}
.modal-close {
  display:block;
  /*padding:.25%;
  background-color: rgba(255,255,255,1);
  border-radius:50%;*/
  color:#666666;
  line-height:50px;
  font-size:80%;
  position:absolute;
  right:0;
  text-align:center;
  top:0;
  width:70px;
  text-decoration:none;
  z-index:1000;
}
.modal-close:hover {
  color:#000;
  background-color: rgba(255,255,255,1);
}
.modal-window .h-text{
  width:50%!important;
  }
.modal-window h1 {
  font-size: 150%;
  margin: 0 0 15px;
}
&lt;/style&gt;



&lt;div class=&quot;container&quot;&gt;
    &lt;div class=&quot;interior&quot;&gt;
      &lt;a class=&quot;btn&quot; href=&quot;#open-modal&quot;&gt;Launch 3D Scene&lt;/a&gt;
    &lt;/div&gt;
  &lt;/div&gt;
  &lt;div id=&quot;open-modal&quot; class=&quot;modal-window&quot;&gt;
    &lt;div&gt;
      &lt;a href=&quot;#modal-close&quot; title=&quot;Close&quot; class=&quot;modal-close&quot;&gt;[ X ] Close&lt;/a&gt;
       &lt;div class=&quot;h-text&quot;&gt;
         &lt;h1&gt;Ology Resident&lt;/h1&gt;
         &lt;div&gt;&lt;p&gt;Ology height-adjustable desks support the physiology and biology of workers to make the workplace a more health-conscious environment.&lt;/p&gt;
       &lt;/div&gt;
    &lt;/div&gt;
      &lt;div&gt;
        &lt;div id=&quot;controls&quot;&gt;
          &lt;select id=&quot;cameraSelect&quot;&gt;
          &lt;/select&gt;
        &lt;/div&gt;
        &lt;div id=&quot;player&quot; style=&quot;width: 600px; height: 400px;&quot;&gt;
          &lt;div id=&quot;clara-embed&quot; style=&quot;width: 600px; height: 400px;&quot;&gt;&lt;/div&gt;
        &lt;/div&gt;
        
        &lt;div id=&quot;content&quot;&gt;
          &lt;div id=&quot;wellbeing&quot; class=&quot;italic&quot;&gt;
            &lt;img src=&quot;https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg&quot;&gt;
            &lt;ul&gt;
              &lt;li&gt;Coffee&lt;/li&gt;
              &lt;li&gt;Tea&lt;/li&gt;
              &lt;li&gt;Milk&lt;/li&gt;
            &lt;/ul&gt;
          &lt;/div&gt;
          &lt;div id=&quot;workplace&quot; class=&quot;normal&quot;&gt;
            &lt;img src=&quot;https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg&quot;&gt;
            &lt;ul&gt;
              &lt;li&gt;Coffee&lt;/li&gt;
              &lt;li&gt;Tea&lt;/li&gt;
              &lt;li&gt;Milk&lt;/li&gt;
            &lt;/ul&gt;
          &lt;/div&gt;
          &lt;div id=&quot;postures&quot; class=&quot;oblique&quot;&gt;
            &lt;img src=&quot;https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg&quot;&gt;
            &lt;ul&gt;
              &lt;li&gt;Coffee&lt;/li&gt;
              &lt;li&gt;Tea&lt;/li&gt;
              &lt;li&gt;Milk&lt;/li&gt;
            &lt;/ul&gt;
          &lt;/div&gt;
          &lt;div id=&quot;antimicrobial&quot; class=&quot;italic&quot;&gt;
            &lt;img src=&quot;https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg&quot;&gt;
            &lt;ul&gt;
              &lt;li&gt;Coffee&lt;/li&gt;
              &lt;li&gt;Tea&lt;/li&gt;
              &lt;li&gt;Milk&lt;/li&gt;
            &lt;/ul&gt;
          &lt;/div&gt;
          &lt;div id=&quot;collab&quot; class=&quot;normal&quot;&gt;
            &lt;img src=&quot;https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg&quot;&gt;
            &lt;ul&gt;
              &lt;li&gt;Coffee&lt;/li&gt;
              &lt;li&gt;Tea&lt;/li&gt;
              &lt;li&gt;Milk&lt;/li&gt;
            &lt;/ul&gt;
          &lt;/div&gt;
          &lt;div id=&quot;cables&quot; class=&quot;oblique&quot;&gt;
            &lt;img src=&quot;https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg&quot;&gt;     
            &lt;ul&gt;
              &lt;li&gt;Coffee&lt;/li&gt;
              &lt;li&gt;Tea&lt;/li&gt;
              &lt;li&gt;Milk&lt;/li&gt;
            &lt;/ul&gt;
          &lt;/div&gt;
          &lt;div id=&quot;sensing&quot; class=&quot;italic&quot;&gt;
            &lt;img src=&quot;https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg&quot;&gt;    
            &lt;ul&gt;
              &lt;li&gt;Coffee&lt;/li&gt;
              &lt;li&gt;Tea&lt;/li&gt;
              &lt;li&gt;Milk&lt;/li&gt;
            &lt;/ul&gt;
          &lt;/div&gt;
          &lt;div id=&quot;health&quot; class=&quot;normal&quot;&gt;
            &lt;img src=&quot;https://dumy1g3ng547g.cloudfront.net/content/themes/steelcase/img/logo.svg&quot;&gt;     
            &lt;ul&gt;
              &lt;li&gt;Coffee&lt;/li&gt;
              &lt;li&gt;Tea&lt;/li&gt;
              &lt;li&gt;Milk&lt;/li&gt;
            &lt;/ul&gt;
          &lt;/div&gt;
        &lt;/div&gt;&lt;!--CLARA CONTENT--&gt;
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;&lt;!--END MODAL WINDOW FRAMEWORK--&gt;
  
&lt;script src=&quot;https://steelcase.clara.io/js/claraplayer.min.js&quot;&gt;&lt;/script&gt; 

&lt;script&gt;
const ids = {
  &#x27;7774b92d-ba6b-44e8-b2e8-00a5e3c494d5&#x27;: &#x27;workplace&#x27;,
  &#x27;9db43c80-4671-4c85-b481-17d1b4c92c3b&#x27;: &#x27;wellbeing&#x27;,
  &#x27;e665f0d5-60e9-492f-b67c-9ff95fe6fb01&#x27;: &#x27;postures&#x27;,
  &#x27;ea9d7ad8-0ebe-4dc7-892a-3b3d8ae5b66d&#x27;: &#x27;antimicrobial&#x27;,
  &#x27;8766ff74-8d88-466e-ba06-46b87c0b1a66&#x27;: &#x27;collab&#x27;,
  &#x27;64976508-875c-4d93-83f3-8335857ffe96&#x27;: &#x27;cables&#x27;,
  &#x27;3a9b7cf9-6000-450c-a11e-ab194636c00c&#x27;: &#x27;sensing&#x27;,
  &#x27;6f924f5c-80c7-4b0e-906e-48cb6f96747c&#x27;: &#x27;health&#x27;,
};

const cameraSelect = document.getElementById(&#x27;cameraSelect&#x27;);
cameraSelect.onchange = function(ev) {
   var id = ev.target.value;
   var divs = document.getElementById(&#x27;content&#x27;).children;
   for(var i = 0; i &lt; divs.length; i++) {
     var state = &#x27;hidden&#x27;;
     if(divs[i].id === ids[ev.target.value])
       state = &#x27;visible&#x27;;
     divs[i].style.visibility = state;
   }
   clara.player.animateCameraTo(id, 500);
}

var clara = claraplayer(&#x27;clara-embed&#x27;); 
clara.on(&#x27;loaded&#x27;, function() { console.log(&#x27;Clara player is loaded and ready&#x27;); }); 
clara.sceneIO.fetchAndUse(&quot;1613b124-6f9f-48ca-a2c5-52e40db046aa&quot;); 
clara.on(&#x27;loaded&#x27;, () =&gt; { 
  const cameras = clara.scene.getAll({type: &#x27;Camera&#x27;, property: &#x27;name&#x27;}); 
  for(let id in cameras) { 
    cameraSelect.options[cameraSelect.options.length] = new Option(cameras[id], id);
  } 
  clara.player.hideTool(&#x27;home&#x27;);
  clara.player.hideTool(&#x27;pan&#x27;);
  clara.player.hideTool(&#x27;zoom&#x27;);
  clara.player.hideTool(&#x27;orbit&#x27;);
});


&lt;/script&gt;[/et_pb_code][/et_pb_column][/et_pb_row][/et_pb_section]