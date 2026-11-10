<div class="pv-hero">
<div class="pv-tag">{{tag}}</div>
<h1>{{hero_title}}</h1>
<p class="pv-subtitle">{{hero_subtitle}}</p>
<div class="pv-actions">
<a href="https://www.fab.com/listings/1ed738da-6aac-46c2-bbee-d2b42c68c3a9" class="pv-button" onclick="gtag('event', 'download_plugin_click', {'event_category': 'outbound', 'event_label': 'Fab Marketplace Download'});">
<span style="text-transform: uppercase;font-weight:bold">{{primary_cta_text}}</span>
<img class="pv-button-icon" src="https://pandoa.github.io/FirebaseFeatures/_images/buyueicon.png" alt="{{cta_icon_alt}}"/>
</a>
</div>
</div>

<div class="pv-section">
<div class="pv-section-header">
<span>{{section_quick_start}}</span>
<h2>{{docs_title}}</h2>
</div>
<ul class="pv-link-list">
<li>
<a href="/GoogleTextToSpeech/setup" onclick="gtag('event', 'card_click', {'event_category': 'hero_card', 'event_label': 'Quick Start - Setup'});">
<div class="pv-link-icon">SET</div>
<div class="pv-link-body">
<h3>{{feature_1_title}}</h3>
<p>{{feature_1_description}}</p>
</div>
<span class="pv-arrow">→</span>
</a>
</li>
<li>
<a href="/GoogleTextToSpeech/synth" onclick="gtag('event', 'card_click', {'event_category': 'hero_card', 'event_label': 'Quick Start - Synth'});">
<div class="pv-link-icon">SYN</div>
<div class="pv-link-body">
<h3>{{feature_2_title}}</h3>
<p>{{feature_2_description}}</p>
</div>
<span class="pv-arrow">→</span>
</a>
</li>
<li>
<a href="/GoogleTextToSpeech/editor" onclick="gtag('event', 'card_click', {'event_category': 'hero_card', 'event_label': 'Quick Start - Editor'});">
<div class="pv-link-icon">EDT</div>
<div class="pv-link-body">
<h3>{{feature_3_title}}</h3>
<p>{{feature_3_description}}</p>
</div>
<span class="pv-arrow">→</span>
</a>
</li>
</ul>
</div>

<div class="pv-section">
<div class="pv-section-header">
<span>{{section_support}}</span>
<h2>{{support_title}}</h2>
</div>
<ul class="pv-link-list">
<li>
<a href="/GoogleTextToSpeech/troubleshoting" onclick="gtag('event', 'card_click', {'event_category': 'hero_card', 'event_label': 'Support - Troubleshooting'});">
<div class="pv-link-icon">TSH</div>
<div class="pv-link-body">
<h3>{{support_feature_1_title}}</h3>
<p>{{support_feature_1_description}}</p>
</div>
<span class="pv-arrow">→</span>
</a>
</li>
<li>
<a href="/GoogleTextToSpeech/support" onclick="gtag('event', 'card_click', {'event_category': 'hero_card', 'event_label': 'Support - Contact'});">
<div class="pv-link-icon">SUP</div>
<div class="pv-link-body">
<h3>{{support_feature_2_title}}</h3>
<p>{{support_feature_2_description}}</p>
</div>
<span class="pv-arrow">→</span>
</a>
</li>
</ul>
</div>

<style>
.pv-hero{
position:relative;
padding:40px 0 36px;
border-bottom:1px solid rgba(255,255,255,.06);
}
.pv-hero::before{
content:"";
position:absolute;
top:-80px;left:-120px;
width:520px;height:520px;
background:radial-gradient(circle, rgba(112,162,255,.14), transparent 70%);
filter:blur(80px);
pointer-events:none;
z-index:0;
}
.pv-hero > *{position:relative;z-index:1;}
.pv-tag{
display:inline-flex;
align-items:center;
height:32px;
padding:0 14px;
border-radius:999px;
background:rgba(112,162,255,.08);
border:1px solid rgba(112,162,255,.14);
color:#70a2ff;
font-size:11px;
font-weight:700;
letter-spacing:.14em;
}
.pv-hero h1{
margin:20px 0 0;
font-size:clamp(56px,7vw,88px);
line-height:1;
letter-spacing:-.04em;
font-weight:800;
color:white;
}
.pv-subtitle{
margin:20px 0 0;
max-width:660px;
font-size:18px;
line-height:1.75;
color:rgba(255,255,255,.6);
}
.pv-subtitle a{color:#70a2ff !important;}
.pv-actions{margin-top:28px;}
.pv-button{
display:inline-flex;
align-items:center;
justify-content:center;
gap:12px;
height:52px;
padding:0 24px;
border-radius:12px;
background:#70a2ff;
color:#121212 !important;
font-size:14px;
font-weight:800;
text-decoration:none !important;
transition:transform .15s ease, box-shadow .15s ease, background .15s ease;
box-shadow:0 10px 30px rgba(112,162,255,.22);
}
.pv-button:hover{
transform:translateY(-1px);
background:#8cb7ff;
box-shadow:0 14px 40px rgba(112,162,255,.3);
}
.pv-button-icon{
width:28px;
height:28px;
display:block;
flex:none;
border-radius:0;
border:none;
box-shadow:none;
}
.pv-section{margin-top:52px;}
.pv-section-header{margin-bottom:20px;}
.pv-section-header span{
display:block;
margin-bottom:8px;
font-size:11px;
font-weight:700;
letter-spacing:.14em;
color:rgba(255,255,255,.32);
}
.pv-section-header h2{
margin:0;
font-size:32px;
line-height:1.15;
letter-spacing:-.03em;
color:white;
}
.pv-link-list{
list-style:none;
margin:0;
padding:0;
border-top:1px solid rgba(255,255,255,.06);
}
.pv-link-list li{
border-bottom:1px solid rgba(255,255,255,.06);
}
.pv-link-list a{
display:flex;
align-items:center;
gap:18px;
padding:20px 14px;
text-decoration:none !important;
transition:background .12s ease;
}
.pv-link-list a:hover{background:rgba(255,255,255,.02);}
.pv-link-icon{
display:flex;
align-items:center;
justify-content:center;
flex:none;
width:46px;
height:46px;
border-radius:12px;
background:rgba(112,162,255,.08);
border:1px solid rgba(112,162,255,.12);
font-size:11px;
font-weight:700;
letter-spacing:.08em;
color:#70a2ff;
}
.pv-link-body{flex:1;min-width:0;}
.pv-link-body h3{
margin:0;
font-size:18px;
line-height:1.35;
font-weight:600;
color:white;
}
.pv-link-body p{
margin:4px 0 0;
font-size:14px;
line-height:1.65;
color:rgba(255,255,255,.55);
}
.pv-arrow{
flex:none;
font-size:18px;
color:rgba(255,255,255,.15);
transition:transform .12s ease, color .12s ease;
}
.pv-link-list a:hover .pv-arrow{
transform:translateX(3px);
color:#70a2ff;
}
@media (max-width:780px){
.pv-hero{padding:24px 0 24px;}
.pv-link-list a{padding:16px 10px;gap:14px;}
}
</style>