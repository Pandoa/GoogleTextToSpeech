<div class="pv-hero">
<div class="pv-hero-content">
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
<div class="pv-preview-wrap"></div>
</div>

<div class="pv-section">
<div class="pv-section-header">
<span>{{section_quick_start}}</span>
<h2>{{docs_title}}</h2>
</div>
<div class="pv-grid">
<a href="/GoogleTextToSpeech/setup" class="pv-card" onclick="gtag('event', 'card_click', {'event_category': 'hero_card', 'event_label': 'Quick Start - Setup'});">
<div class="pv-card-top">
<div class="pv-card-icon">SET</div>
<div class="pv-arrow">→</div>
</div>
<h3>{{feature_1_title}}</h3>
<p>{{feature_1_description}}</p>
</a>
<a href="/GoogleTextToSpeech/synth" class="pv-card" onclick="gtag('event', 'card_click', {'event_category': 'hero_card', 'event_label': 'Quick Start - Synth'});">
<div class="pv-card-top">
<div class="pv-card-icon">SYN</div>
<div class="pv-arrow">→</div>
</div>
<h3>{{feature_2_title}}</h3>
<p>{{feature_2_description}}</p>
</a>
<a href="/GoogleTextToSpeech/editor" class="pv-card" onclick="gtag('event', 'card_click', {'event_category': 'hero_card', 'event_label': 'Quick Start - Editor'});">
<div class="pv-card-top">
<div class="pv-card-icon">EDT</div>
<div class="pv-arrow">→</div>
</div>
<h3>{{feature_3_title}}</h3>
<p>{{feature_3_description}}</p>
</a>
</div>
</div>

<div class="pv-section">
<div class="pv-section-header">
<span>{{section_support}}</span>
<h2>{{support_title}}</h2>
</div>
<div class="pv-grid">
<a href="/GoogleTextToSpeech/troubleshoting" class="pv-card" onclick="gtag('event', 'card_click', {'event_category': 'hero_card', 'event_label': 'Support - Troubleshooting'});">
<div class="pv-card-top">
<div class="pv-card-icon">TSH</div>
<div class="pv-arrow">→</div>
</div>
<h3>{{support_feature_1_title}}</h3>
<p>{{support_feature_1_description}}</p>
</a>
<a href="/GoogleTextToSpeech/support" class="pv-card" onclick="gtag('event', 'card_click', {'event_category': 'hero_card', 'event_label': 'Support - Contact'});">
<div class="pv-card-top">
<div class="pv-card-icon">SUP</div>
<div class="pv-arrow">→</div>
</div>
<h3>{{support_feature_2_title}}</h3>
<p>{{support_feature_2_description}}</p>
</a>
</div>
</div>

<style>
.pv-hero{
display:grid;
grid-template-columns:minmax(0,1.2fr) minmax(0,.8fr);
gap:64px;
align-items:center;
padding:24px 0 12px;
}
.pv-hero-content{min-width:0;}
.pv-tag{
display:inline-flex;
align-items:center;
height:34px;
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
margin:22px 0 0;
font-size:clamp(72px,9vw,128px);
line-height:.88;
letter-spacing:-.04em;
font-weight:800;
color:white;
}
.pv-subtitle{
margin:28px 0 0;
max-width:680px;
font-size:19px;
line-height:1.8;
color:rgba(255,255,255,.6);
}
.pv-subtitle a{color:#70a2ff !important;}
.pv-actions{margin-top:38px;}
.pv-button{
display:inline-flex;
align-items:center;
justify-content:center;
gap:14px;
height:60px;
padding:0 26px;
border-radius:18px;
background:#70a2ff;
color:#121212 !important;
font-size:15px;
font-weight:800;
text-decoration:none !important;
transition:transform .18s ease, box-shadow .18s ease, background .18s ease;
box-shadow:0 18px 50px rgba(112,162,255,.25);
}
.pv-button:hover{
transform:translateY(-2px);
background:#8cb7ff;
box-shadow:0 26px 70px rgba(112,162,255,.32);
}
.pv-button-icon{
width:32px;
height:32px;
display:block;
flex:none;
border-radius: 0;
border: none;
box-shadow: none;
}
.pv-preview-wrap{
position:relative;
display:flex;
justify-content:flex-end;
align-items:center;
min-height:420px;
}
.pv-preview-wrap::before{
content:"";
position:absolute;
inset:0;
background:radial-gradient(circle at center, rgba(112,162,255,.22), transparent 70%);
filter:blur(70px);
z-index:0;
}
.pv-section{margin-top:68px;}
.pv-section-header{
margin-bottom:32px;
}
.pv-section-header span{
display:block;
margin-bottom:10px;
font-size:11px;
font-weight:700;
letter-spacing:.14em;
color:rgba(255,255,255,.32);
}
.pv-section-header h2{
margin:0 0 8px 0;
font-size:44px;
line-height:1;
letter-spacing:-.06em;
color:white;
}
.pv-grid{
display:grid;
grid-template-columns:repeat(2,minmax(0,1fr));
gap:20px;
}
.pv-card{
display:flex;
flex-direction:column;
gap:22px;
padding:32px;
min-height:240px;
border-radius:32px;
text-decoration:none !important;
background:rgba(255,255,255,.02);
border:1px solid rgba(255,255,255,.05);
transition: all .18s ease;
}
.pv-card:hover{
transform:translateY(-4px);
border-color:rgba(112,162,255,.18);
background:rgba(255,255,255,.03);
}
.pv-card-top{display:flex;align-items:center;justify-content:space-between;}
.pv-card-icon{
display:flex;
align-items:center;
justify-content:center;
width:52px;
height:52px;
border-radius:18px;
background:rgba(112,162,255,.08);
border:1px solid rgba(112,162,255,.12);
font-size:12px;
font-weight:700;
letter-spacing:.08em;
color:#70a2ff;
}
.pv-arrow{
font-size:24px;
color:rgba(255,255,255,.2);
transition:all .18s ease;
}
.pv-card:hover .pv-arrow{
transform:translateX(4px);
color:#70a2ff;
}
.pv-card h3{
margin:0;
font-size:34px;
line-height:1.05;
letter-spacing:-.06em;
color:white;
}
.pv-card p{
margin:0;
font-size:16px;
line-height:1.8;
color:rgba(255,255,255,.58);
}
@media (max-width:1100px){
.pv-hero{grid-template-columns:1fr;gap:42px;}
.pv-preview-wrap{justify-content:center;}
}
@media (max-width:780px){
.pv-grid{grid-template-columns:1fr;}
}
</style>