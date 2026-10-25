<!DOCTYPE html>
<html lang="en"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>BIDA MARKET HUB – Discover Bida. Shop Local.</title>
<style>
:root{--g:#0f5132;--g2:#0b3d26;--gold:#c8962e;--goldt:#8a6410;--bg:#fbf6e9;--card:#fff;--tx:#1d2a22;--mu:#56635a;--bd:#e3dcc6;--err:#b3261e;color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme=light]){--g:#3f9b6b;--g2:#0e2a1d;--gold:#e0b24f;--goldt:#e0b24f;--bg:#111a15;--card:#1a2620;--tx:#f1ecdc;--mu:#a9b5ab;--bd:#2c3b33;--err:#ff8a80;color-scheme:dark}}
:root[data-theme=dark]{--g:#3f9b6b;--g2:#0e2a1d;--gold:#e0b24f;--goldt:#e0b24f;--bg:#111a15;--card:#1a2620;--tx:#f1ecdc;--mu:#a9b5ab;--bd:#2c3b33;--err:#ff8a80;color-scheme:dark}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}body{margin:0;background:var(--bg);color:var(--tx);font:16px/1.55 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
a{color:var(--g)}h1,h2,h3{line-height:1.2;margin:0 0 .5em}h2{font-size:1.4rem}
.w{max-width:1080px;margin:0 auto;padding:0 16px}
header{background:var(--g2);color:#fff;position:sticky;top:0;z-index:5}
header .w{display:flex;align-items:center;gap:10px;flex-wrap:wrap;padding-top:10px;padding-bottom:10px}
.logo{font-weight:800;letter-spacing:.5px;color:#fff;text-decoration:none;font-size:1.1rem}.logo span{color:#e8b94a}
nav{display:flex;gap:4px;flex-wrap:wrap;flex:1}nav a{color:#fff;text-decoration:none;padding:10px 10px;border-radius:8px;font-size:.95rem}nav a:hover,nav a.on{background:rgba(255,255,255,.15)}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:6px;min-height:44px;padding:10px 18px;border-radius:10px;border:2px solid transparent;font:600 1rem inherit;font-family:inherit;cursor:pointer;text-decoration:none;background:var(--g);color:#fff}
.btn.gold{background:#e8b94a;color:#1d2a22}.btn.wa{background:#1a7f3c;color:#fff}.btn.out{background:transparent;border-color:var(--g);color:var(--g)}.btn.sm{min-height:40px;padding:6px 12px;font-size:.9rem}
.btn[disabled],.btn.dis{opacity:.55;cursor:not-allowed}
:focus-visible{outline:3px solid var(--gold);outline-offset:2px}
.hero{background:linear-gradient(135deg,var(--g2),var(--g));color:#fff;padding:36px 0 30px}.hero h1{font-size:clamp(1.9rem,6vw,3rem)}.hero p{max-width:620px;opacity:.95}
.sb{display:flex;gap:8px;flex-wrap:wrap;margin-top:16px}.sb input{flex:1 1 220px}
input,select,textarea{width:100%;min-height:44px;padding:10px 12px;border:1.5px solid var(--bd);border-radius:10px;background:var(--card);color:var(--tx);font:inherit}
textarea{min-height:100px}label{display:block;font-weight:600;margin:12px 0 4px}.hint{color:var(--mu);font-size:.88rem;font-weight:400}
section{padding:26px 0}.grid{display:grid;gap:14px;grid-template-columns:repeat(auto-fill,minmax(240px,1fr))}
.card{background:var(--card);border:1px solid var(--bd);border-radius:14px;overflow:hidden;display:flex;flex-direction:column}.card .b{padding:14px;display:flex;flex-direction:column;gap:6px;flex:1}
.ph{height:130px;background:linear-gradient(135deg,#e9dfbd,#f6efd6);display:flex;align-items:center;justify-content:center;font-size:2.6rem}.ph img{width:100%;height:100%;object-fit:cover}
@media(prefers-color-scheme:dark){:root:not([data-theme=light]) .ph{background:#24352c}}
.price{font-weight:800;color:var(--g);font-size:1.15rem}.mu{color:var(--mu);font-size:.9rem}
.tag{display:inline-block;font-size:.75rem;font-weight:700;padding:2px 8px;border-radius:99px;background:#fff3cf;color:#6b4a00;border:1px solid #e0c36a}.tag.f{background:var(--gold);color:#1d2a22;border-color:var(--gold)}
.cats{display:grid;gap:10px;grid-template-columns:repeat(auto-fill,minmax(130px,1fr))}.cat{background:var(--card);border:1px solid var(--bd);border-radius:12px;padding:14px 8px;text-align:center;cursor:pointer;color:var(--tx);font:inherit;min-height:44px}.cat:hover{border-color:var(--gold)}.cat i{display:block;font-size:1.8rem;font-style:normal}
.filters{display:grid;gap:10px;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));background:var(--card);border:1px solid var(--bd);padding:14px;border-radius:14px;margin-bottom:16px}
.notice{background:#fff3cf;color:#4d3600;border:1px solid #e0c36a;border-radius:10px;padding:10px 14px;margin:12px 0;font-size:.92rem}
.err{background:#fdecea;color:#7a1710;border:1px solid #f1a9a3;border-radius:10px;padding:10px 14px;margin:10px 0}.err:empty{display:none}.fe{color:var(--err);font-size:.85rem;min-height:1em}
.empty{text-align:center;padding:36px 12px;color:var(--mu);border:2px dashed var(--bd);border-radius:14px}
.sk{height:230px;border-radius:14px;background:linear-gradient(90deg,var(--bd),var(--card),var(--bd));background-size:200% 100%;animation:s 1.2s infinite}@keyframes s{to{background-position:-200% 0}}
@media(prefers-reduced-motion:reduce){.sk{animation:none}}
.steps{display:grid;gap:14px;grid-template-columns:repeat(auto-fit,minmax(260px,1fr))}.steps ol{padding-left:20px;margin:0}
.band{background:var(--card);border-block:1px solid var(--bd)}.stars{color:var(--gold);letter-spacing:2px}
.sr{display:flex;gap:4px}.sr label{margin:0;font-size:1.8rem;cursor:pointer;color:var(--bd)}.sr input{position:absolute;opacity:0;width:1px;min-height:0}.sr input:checked~label,.sr label.h{color:var(--gold)}
footer{background:var(--g2);color:#e9e4d0;padding:26px 0;margin-top:30px}footer a{color:#f0cf7a}
dialog{border:none;border-radius:14px;max-width:440px;width:92%;background:var(--card);color:var(--tx)}
.row{display:flex;gap:8px;flex-wrap:wrap;align-items:center}table{width:100%;border-collapse:collapse;font-size:.9rem}td,th{border-bottom:1px solid var(--bd);padding:8px;text-align:left}.ov{overflow-x:auto}
.ad{border:1px dashed var(--gold);border-radius:12px;padding:12px;text-align:center;color:var(--mu)}
</style></head><body>
<header><div class="w"><a class="logo" href="#home" data-r="home">BIDA <span>MARKET</span> HUB</a>
<nav aria-label="Main"><a href="#home" data-r="home">Home</a><a href="#browse" data-r="browse">Browse</a><a href="#nearby" data-r="nearby">Nearby shops</a><a href="#about" data-r="about">About</a><a href="#help" data-r="help">Help</a></nav>
<a class="btn gold sm" href="#register" data-r="register">Register your business</a></div></header>
<main id="app" class="w" tabindex="-1"></main>
<footer><div class="w"><strong>BIDA MARKET HUB</strong><p class="mu" style="color:#c9d2c4">A local marketplace for Bida, Niger State and nearby communities.</p>
<p><a href="#help" data-r="help">Help &amp; contact</a> · <a href="#legal" data-r="legal">Privacy &amp; terms</a> · <a href="#about" data-r="about">About</a> · <a href="#admin" data-r="admin">Admin</a></p></div></footer>
<dialog id="dlg"></dialog>
<script>
/* ===== DATA: edit/replace this block (or use Admin page) – no page code changes needed ===== */
const CATS=[["Farm produce","🌾"],["Fashion","🧵"],["Food","🍲"],["Electronics","📱"],["Home","🛋️"],["Beauty","💇"],["Building","🧱"],["Services","🔧"]];
const SEED={biz:[
{id:"d1",name:"Example Farm Stall",desc:"Demo business showing how a farmer's profile looks.",cat:"Farm produce",area:"Bida (example area)",phone:"",wa:"",hours:"Not supplied (demo)",photos:[],demo:1,status:"approved",featured:0},
{id:"d2",name:"Example Tailoring Studio",desc:"Demo business showing how a fashion designer's profile looks.",cat:"Fashion",area:"Bida (example area)",phone:"",wa:"",hours:"Not supplied (demo)",photos:[],demo:1,status:"approved",featured:0},
{id:"d3",name:"Example Phone Repair",desc:"Demo business showing how a service provider's profile looks.",cat:"Services",area:"Bida (example area)",phone:"",wa:"",hours:"Not supplied (demo)",photos:[],demo:1,status:"approved",featured:0}],
lst:[
{id:"l1",biz:"d1",title:"Example: Bag of yams",desc:"Demo listing. Real sellers describe size and quality here.",cat:"Farm produce",type:"Product",price:5000,avail:"In stock",seller:"Example seller",loc:"Bida (example area)",photos:[],demo:1,status:"approved",featured:0},
{id:"l2",biz:"d1",title:"Example: Fresh tomatoes (basket)",desc:"Demo listing for illustration only.",cat:"Farm produce",type:"Product",price:3500,avail:"Limited",seller:"Example seller",loc:"Bida (example area)",photos:[],demo:1,status:"approved",featured:0},
{id:"l3",biz:"d2",title:"Example: Custom native outfit",desc:"Demo listing for illustration only.",cat:"Fashion",type:"Service",price:15000,avail:"Takes orders",seller:"Example seller",loc:"Bida (example area)",photos:[],demo:1,status:"approved",featured:0},
{id:"l4",biz:"d2",title:"Example: Ankara fabric (6 yards)",desc:"Demo listing for illustration only.",cat:"Fashion",type:"Product",price:8000,avail:"In stock",seller:"Example seller",loc:"Bida (example area)",photos:[],demo:1,status:"approved",featured:0},
{id:"l5",biz:"d3",title:"Example: Phone screen replacement",desc:"Demo listing for illustration only.",cat:"Services",type:"Service",price:12000,avail:"Available",seller:"Example seller",loc:"Bida (example area)",photos:[],demo:1,status:"approved",featured:0}],
rev:[{id:"r1",biz:"d1",name:"Sample reviewer",stars:4,text:"Sample review: this is an example of what a customer review looks like.",demo:1},{id:"r2",biz:"d2",name:"Sample reviewer",stars:5,text:"Sample review: example text only, not a real customer.",demo:1}],
ads:[] /* future paid ads: [{title,text,link}] – shown in the ad slot when filled */};
/* ===== storage (browser-only until a backend is connected) ===== */
const K="bmh_v1";let S={biz:[],lst:[],rev:[],rep:[],ov:{}},storeErr="";
try{S=Object.assign(S,JSON.parse(localStorage.getItem(K)||"{}"))}catch(e){storeErr="Saved data could not be read on this device."}
function save(){try{localStorage.setItem(K,JSON.stringify(S));return 1}catch(e){alert("Could not save (storage full or blocked). Try fewer or smaller photos.");return 0}}
const ap=a=>a.map(x=>Object.assign({},x,S.ov[x.id]||{})).filter(x=>!x.del);
const B=()=>ap([...SEED.biz,...S.biz]),L=()=>ap([...SEED.lst,...S.lst]),R=()=>[...SEED.rev,...S.rev];
const pub=a=>a.filter(x=>x.status==="approved");
const $=s=>document.querySelector(s),esc=s=>String(s??"").replace(/[&<>"']/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]));
const naira=n=>"₦"+Number(n).toLocaleString("en-NG"),icon=c=>(CATS.find(x=>x[0]===c)||[0,"🛍️"])[1];
const waNum=n=>{let d=String(n||"").replace(/\D/g,"");if(/^0\d{10}$/.test(d))d="234"+d.slice(1);return/^\d{10,15}$/.test(d)?d:""};
const waLink=(n,t)=>"https://wa.me/"+waNum(n)+"?text="+encodeURIComponent(t);
const bizOf=id=>B().find(b=>b.id===id);
/* ===== routing ===== */
let F={q:"",cat:"",type:"",loc:"",min:"",max:""},cur="home";
function go(r){cur=r;try{location.hash=r}catch(e){}draw()}
addEventListener("hashchange",()=>{const h=location.hash.slice(1);if(h&&h!==cur){cur=h;draw()}});
document.addEventListener("click",e=>{const a=e.target.closest("[data-r]");if(a){e.preventDefault();go(a.dataset.r)}const c=e.target.closest("[data-cat]");if(c){F={q:"",cat:c.dataset.cat,type:"",loc:"",min:"",max:""};go("browse")}});
/* ===== components ===== */
const wa=(b,what)=>{const n=waNum(b&&b.wa);return n?`<a class="btn wa" target="_blank" rel="noopener" href="${waLink(b.wa,"Hello "+b.name+", I found "+what+" on BIDA MARKET HUB and I'm interested. Is it available?")}">💬 Contact on WhatsApp</a>`:`<span class="btn wa dis" role="note">💬 WhatsApp not supplied</span>`};
const tags=x=>(x.demo?'<span class="tag">DEMO EXAMPLE</span> ':'')+(x.featured&&x.status==="approved"?'<span class="tag f">★ Featured</span> ':'')+(x.status==="pending"?'<span class="tag">Pending review</span>':'');
const stars=n=>`<span class="stars" aria-label="${n} of 5 stars">${"★".repeat(Math.round(n))}${"☆".repeat(5-Math.round(n))}</span>`;
const avg=id=>{const r=R().filter(x=>x.biz===id);return r.length?r.reduce((a,x)=>a+x.stars,0)/r.length:0};
const img=(x,c)=>`<div class="ph">${x.photos&&x.photos[0]?`<img loading="lazy" decoding="async" alt="${esc(x.title||x.name)}" src="${x.photos[0]}">`:icon(c||x.cat)}</div>`;
function lcard(l){const b=bizOf(l.biz);return`<article class="card">${img(l)}<div class="b">${tags(l)}<h3 style="margin:0;font-size:1.05rem">${esc(l.title)}</h3><div class="price">${naira(l.price)}</div><div class="mu">${esc(l.type)} · ${esc(l.cat)} · ${esc(l.avail)}</div><div class="mu">${esc(l.seller)} · ${esc(l.loc)}</div><div style="flex:1"></div><div class="row">${b?`<button class="btn out sm" data-r="biz-${b.id}">View business</button>`:""}<button class="btn out sm" onclick="report('${l.id}')">Report</button></div>${wa(b,l.title)}</div></article>`}
function bcard(b){const a=avg(b.id);return`<article class="card">${img(b,b.cat)}<div class="b">${tags(b)}<h3 style="margin:0;font-size:1.05rem">${esc(b.name)}</h3><div class="mu">${esc(b.cat)} · ${esc(b.area)}</div>${a?`<div>${stars(a)}</div>`:'<div class="mu">No reviews yet</div>'}<div style="flex:1"></div><button class="btn sm" data-r="biz-${b.id}">View profile</button></div></article>`}
const grid=(arr,fn,msg)=>arr.length?`<div class="grid">${arr.map(fn).join("")}</div>`:`<div class="empty">${msg}</div>`;
const sortF=a=>[...a].sort((x,y)=>(y.featured?1:0)-(x.featured?1:0));
const adSlot=()=>SEED.ads.length?`<div class="ad">Sponsored: <a href="${esc(SEED.ads[0].link)}">${esc(SEED.ads[0].title)}</a></div>`:"";
/* ===== pages ===== */
const P={
home(){const ls=sortF(pub(L())),bs=sortF(pub(B()));
return`<div class="hero" style="margin:0 -16px;padding-left:16px;padding-right:16px"><div class="w" style="padding:0"><h1>Discover Bida. Shop Local.</h1><p>Browse products, services and shops from traders, farmers, designers and service providers around Bida. No account needed to look around — message sellers directly on WhatsApp.</p>
<form class="sb" role="search" onsubmit="event.preventDefault();F.q=this.q.value;go('browse')"><input name="q" aria-label="Search" placeholder="Search products, services, businesses, locations"><button class="btn gold">Search</button></form></div></div>
${storeErr?`<div class="err">${esc(storeErr)}</div>`:""}
<div class="notice">Items marked <b>DEMO EXAMPLE</b> are samples to show how the site works. They are not real businesses.</div>
<section><h2>Popular categories</h2><div class="cats">${CATS.map(c=>`<button class="cat" data-cat="${c[0]}"><i>${c[1]}</i>${c[0]}</button>`).join("")}</div></section>
<section><h2>Products &amp; services</h2>${grid(ls.slice(0,6),lcard,"No listings yet.")}<p><button class="btn out" data-r="browse">See all listings</button></p></section>
${adSlot()}
<section><h2>Nearby businesses</h2>${grid(bs.slice(0,3),bcard,"No businesses yet.")}<p><button class="btn out" data-r="nearby">Find nearby shops</button></p></section>
<section class="band" style="margin:0 -16px;padding:26px 16px"><h2>🌾 Local farmers</h2><p class="mu">Fresh produce straight from farms around Bida.</p>${grid(ls.filter(l=>l.cat==="Farm produce").slice(0,3),lcard,"No farm listings yet. Are you a farmer? <a href='#register' data-r='register'>Register your business</a>.")}</section>
<section><h2>🧵 Fashion designers</h2><p class="mu">Tailors, fabric sellers and designers.</p>${grid(ls.filter(l=>l.cat==="Fashion").slice(0,3),lcard,"No fashion listings yet.")}</section>
<section class="band" style="margin:0 -16px;padding:26px 16px"><h2>How it works</h2><div class="steps"><div><h3>For buyers</h3><ol><li>Search or browse by category.</li><li>Open a listing or business profile.</li><li>Tap “Contact on WhatsApp” to ask or order.</li><li>Leave a review afterwards.</li></ol></div><div><h3>For sellers</h3><ol><li>Register your business.</li><li>Add products or services with photos and ₦ prices.</li><li>We may review it before it appears.</li><li>Customers message you on WhatsApp.</li></ol></div></div></section>`},
browse(){return`<section><h2>Browse products &amp; services</h2>
<form class="filters" onsubmit="event.preventDefault()" oninput="upF(this)"><div><label for="fq">Search</label><input id="fq" name="q" value="${esc(F.q)}" placeholder="e.g. yam, tailor"></div>
<div><label for="fc">Category</label><select id="fc" name="cat"><option value="">All</option>${CATS.map(c=>`<option ${F.cat===c[0]?"selected":""}>${c[0]}</option>`).join("")}</select></div>
<div><label for="ft">Type</label><select id="ft" name="type"><option value="">All</option>${["Product","Service"].map(t=>`<option ${F.type===t?"selected":""}>${t}</option>`).join("")}</select></div>
<div><label for="fl">Location</label><input id="fl" name="loc" value="${esc(F.loc)}" placeholder="Area or community"></div>
<div><label for="fm">Min ₦</label><input id="fm" name="min" type="number" min="0" inputmode="numeric" value="${esc(F.min)}"></div>
<div><label for="fx">Max ₦</label><input id="fx" name="max" type="number" min="0" inputmode="numeric" value="${esc(F.max)}"></div>
<div style="align-self:end"><button type="button" class="btn out" onclick="F={q:'',cat:'',type:'',loc:'',min:'',max:''};draw()">Clear</button></div></form>
<div id="res" aria-live="polite"></div></section>`},
cat(){const c=CATS[+cur.slice(4)];if(!c)return P.nf();F={q:"",cat:c[0],type:"",loc:"",min:"",max:""};return`<section><h2>${c[1]} ${c[0]}</h2><div id="res" aria-live="polite"></div><p><button class="btn out" data-r="browse">More filters</button></p></section>`},
nearby(){return`<section><h2>Nearby shops</h2><p class="mu">Shops are grouped by the area each seller supplied. We don't show precise map pins unless a seller provides one.</p><label for="na">Choose an area</label><select id="na" onchange="nb(this.value)"><option value="">All areas</option>${[...new Set(pub(B()).map(b=>b.area))].map(a=>`<option>${esc(a)}</option>`).join("")}</select><div id="nbr" style="margin-top:16px"></div></section>`},
biz(){const b=bizOf(cur.slice(4));if(!b||b.status!=="approved"&&!S.biz.find(x=>x.id===b.id))return P.nf();const ls=L().filter(l=>l.biz===b.id&&(l.status==="approved"||S.lst.find(x=>x.id===l.id))),rv=R().filter(r=>r.biz===b.id);
return`<section><p><a href="#browse" data-r="browse">← Back</a></p>${tags(b)}<h2>${esc(b.name)}</h2><div class="grid" style="grid-template-columns:repeat(auto-fit,minmax(280px,1fr))"><div>${(b.photos&&b.photos.length?b.photos.map(p=>`<img loading="lazy" alt="${esc(b.name)}" src="${p}" style="width:100%;border-radius:12px;margin-bottom:8px">`).join(""):`<div class="ph" style="border-radius:12px;height:180px">${icon(b.cat)}</div>`)}</div>
<div><p>${esc(b.desc)}</p><p><b>Category:</b> ${esc(b.cat)}<br><b>Area:</b> ${esc(b.area)}<br><b>Opening hours:</b> ${esc(b.hours||"Not supplied")}<br><b>Phone:</b> ${b.phone?`<a href="tel:${esc(b.phone)}">${esc(b.phone)}</a>`:"Not supplied"}</p>${wa(b,"your business")}</div></div></section>
<section><h2>Listings</h2>${grid(ls,lcard,"This business has no listings yet.")}</section>
<section><h2>Reviews ${avg(b.id)?stars(avg(b.id)):""}</h2>${rv.length?rv.map(r=>`<div class="card" style="margin-bottom:10px"><div class="b">${stars(r.stars)} <b>${esc(r.name)}</b> ${r.demo?'<span class="tag">SAMPLE REVIEW</span>':""}<div>${esc(r.text)}</div></div></div>`).join(""):'<div class="empty">No reviews yet. Be the first.</div>'}
<form onsubmit="rev(event,'${b.id}')" novalidate><h3>Leave a review</h3><label>Rating</label><div class="sr" role="radiogroup" aria-label="Rating">${[1,2,3,4,5].map(i=>`<label title="${i} stars"><input type="radio" name="s" value="${i}"><span aria-hidden="true" onclick="this.closest('.sr').querySelectorAll('span').forEach((s,j)=>s.style.color=j<${i}?'var(--gold)':'var(--bd)')">★</span><span class="mu" style="font-size:.7rem">${i}</span></label>`).join("")}</div><div class="fe" id="e-s"></div>
<label for="rn">Your name</label><input id="rn" name="n" maxlength="60"><div class="fe" id="e-n"></div><label for="rt">Your review</label><textarea id="rt" name="t" maxlength="600"></textarea><div class="fe" id="e-t"></div><button class="btn">Submit review</button></form></section>`},
register(){return`<section><h2>Register your business</h2><div class="notice">Submissions may need review before they appear on the site. <b>Public:</b> business name, description, category, area, phone, WhatsApp, hours and photos. Nothing else is collected.</div>
<form id="fr" onsubmit="regB(event)" novalidate>${fld("name","Business name *")}${sel("cat","Category *",CATS.map(c=>c[0]))}<label for="desc">Description *</label><textarea id="desc" name="desc" maxlength="500"></textarea><div class="fe" id="e-desc"></div>${fld("area","Address or area *","e.g. street, community")}${fld("phone","Phone number","e.g. 0803…")}${fld("wa","WhatsApp number *","Customers will message this number. Use digits, e.g. 0803… ")}${fld("hours","Opening hours","e.g. Mon–Sat 8am–6pm")}<label for="ph">Photos (up to 3)</label><input id="ph" type="file" accept="image/*" multiple><div class="hint">Photos are shrunk automatically to save data.</div><div class="fe" id="e-ph"></div>
<label style="display:flex;gap:8px;font-weight:400"><input type="checkbox" name="ok" style="width:24px;min-height:24px"> I agree the details above may be shown publicly and accept the <a href="#legal" data-r="legal">terms</a>. *</label><div class="fe" id="e-ok"></div><button class="btn">Submit for review</button></form></section>`},
add(){const mine=S.biz;if(!mine.length)return`<section><h2>Add a listing</h2><div class="empty">Register your business first, then add listings.<p><button class="btn" data-r="register">Register your business</button></p></div></section>`;
return`<section><h2>Add a product or service</h2><div class="notice">Submissions may need review before they appear. <b>Public:</b> title, description, category, price, photos, availability, seller name and location.</div>
<form onsubmit="addL(event)" novalidate><label for="biz">Your business *</label><select id="biz" name="biz">${mine.map(b=>`<option value="${b.id}">${esc(b.name)}</option>`).join("")}</select>${fld("title","Title *")}<label for="desc">Description *</label><textarea id="desc" name="desc" maxlength="500"></textarea><div class="fe" id="e-desc"></div>${sel("cat","Category *",CATS.map(c=>c[0]))}${sel("type","Listing type *",["Product","Service"])}${fld("price","Price in ₦ *","Numbers only","number")}${sel("avail","Availability *",["In stock","Limited","Takes orders","Available","Out of stock"])}${fld("seller","Seller name *")}${fld("loc","Seller location or community *")}<label for="ph">Photos (up to 3)</label><input id="ph" type="file" accept="image/*" multiple><div class="fe" id="e-ph"></div><button class="btn">Submit listing</button></form></section>`},
about(){return`<section><h2>About BIDA MARKET HUB</h2><p>BIDA MARKET HUB is a simple digital marketplace for Bida, Niger State, Nigeria and nearby communities. It helps people find local traders, farmers, fashion designers, shops and service providers, and helps those sellers reach more customers.</p><p>We don't process payments. Buyers and sellers agree prices and delivery directly on WhatsApp. Please meet safely and check goods before paying.</p></section>`},
help(){return`<section><h2>Help &amp; contact</h2><h3>Common questions</h3><p><b>Do I need an account?</b> No, not to browse or message sellers.</p><p><b>Why isn't my listing showing?</b> New submissions may need review first.</p><p><b>Something wrong with a listing?</b> Use the “Report” button on the listing.</p><p><b>Contact the BIDA MARKET HUB team:</b> contact details will be added by the site administrator.</p></section>`},
legal(){return`<section><h2>Privacy policy &amp; terms</h2><div class="notice">Draft for review: have this checked and completed before launch.</div><h3>Privacy</h3><p>We only collect what you submit in forms: business details, listing details, reviews and reports. Business and listing details you submit are shown publicly. Your WhatsApp message goes to the seller through WhatsApp, under WhatsApp's own privacy rules.</p><h3>Terms</h3><p>Sellers must supply accurate details and only list items they may lawfully sell. Reviews must be honest and respectful. We may remove content. BIDA MARKET HUB does not take payments or guarantee any transaction; deal directly and safely with sellers.</p></section>`},
admin(){const all=[...S.biz,...S.lst].map(x=>Object.assign({},x,S.ov[x.id]||{})),seedAll=[...SEED.biz,...SEED.lst].map(x=>Object.assign({},x,S.ov[x.id]||{}));
const row=x=>`<tr><td>${esc(x.title||x.name)} ${x.demo?"(demo)":""}</td><td>${x.status}${x.del?" (deleted)":""}</td><td>${x.featured?"★":""}</td><td class="row"><button class="btn sm" onclick="ov('${x.id}',{status:'approved'})">Approve</button><button class="btn sm out" onclick="ov('${x.id}',{status:'rejected'})">Reject</button><button class="btn sm out" onclick="ov('${x.id}',{featured:${x.featured?0:1}})">${x.featured?"Unfeature":"Feature"}</button><button class="btn sm out" onclick="ov('${x.id}',{del:1})">Delete</button></td></tr>`;
return`<section><h2>Admin</h2><div class="notice">Prototype admin: data lives in this browser only and this page has no login. Before launch, connect a database and protect this page so only administrators can approve, feature or delete listings.</div><div class="ov"><table><tr><th>Item</th><th>Status</th><th>Featured</th><th>Actions</th></tr>${[...all,...seedAll].map(row).join("")}</table></div><h3>Reports (${S.rep.length})</h3>${S.rep.length?S.rep.map(r=>`<p>• ${esc(r.title)} — ${esc(r.reason)}: ${esc(r.note)}</p>`).join(""):'<div class="empty">No reports.</div>'}</section>`},
nf(){return`<div class="empty"><h2>Page not found</h2><p>That page or business isn't available.</p><button class="btn" data-r="home">Go home</button></div>`}};
const fld=(n,l,h,t)=>`<label for="${n}">${l}</label><input id="${n}" name="${n}" type="${t||"text"}" ${t==="number"?'min="0" inputmode="numeric"':""}>${h?`<div class="hint">${h}</div>`:""}<div class="fe" id="e-${n}"></div>`;
const sel=(n,l,o)=>`<label for="${n}">${l}</label><select id="${n}" name="${n}">${o.map(x=>`<option>${x}</option>`).join("")}</select>`;
/* ===== behaviour ===== */
function draw(){const app=$("#app");let k=cur.split("-")[0];if(!P[k])k="nf";try{app.innerHTML=P[k]();}catch(e){app.innerHTML='<div class="err" style="display:block">Something went wrong loading this page. <button class="btn sm" onclick="draw()">Try again</button></div>'}
document.querySelectorAll("nav a").forEach(a=>a.classList.toggle("on",a.dataset.r===cur));scrollTo(0,0);if($("#res"))filt();if($("#nbr"))nb("")}
function upF(f){F={q:f.q.value,cat:f.cat.value,type:f.type.value,loc:f.loc.value,min:f.min.value,max:f.max.value};filt()}
function filt(){const r=$("#res");r.innerHTML='<div class="grid"><div class="sk"></div><div class="sk"></div></div>';setTimeout(()=>{try{const q=F.q.toLowerCase().trim();const a=sortF(pub(L())).filter(l=>{const b=bizOf(l.biz)||{};const hay=(l.title+" "+l.desc+" "+l.cat+" "+l.seller+" "+l.loc+" "+(b.name||"")).toLowerCase();return(!q||hay.includes(q))&&(!F.cat||l.cat===F.cat)&&(!F.type||l.type===F.type)&&(!F.loc||l.loc.toLowerCase().includes(F.loc.toLowerCase()))&&(F.min===""||l.price>=+F.min)&&(F.max===""||l.price<=+F.max)});
const bs=q?pub(B()).filter(b=>(b.name+" "+b.desc+" "+b.area).toLowerCase().includes(q)&&(!F.cat||b.cat===F.cat)):[];
r.innerHTML=`<p class="mu">${a.length} listing${a.length==1?"":"s"} found</p>`+grid(a,lcard,"No listings match. Try fewer filters or a different word.")+(bs.length?`<h3 style="margin-top:20px">Matching businesses</h3>${grid(bs,bcard,"")}`:"")}catch(e){r.innerHTML='<div class="err" style="display:block">Couldn\'t load listings. <button class="btn sm" onclick="filt()">Retry</button></div>'}},250)}
function nb(a){$("#nbr").innerHTML=grid(sortF(pub(B())).filter(b=>!a||b.area===a),bcard,"No shops listed for this area yet.")}
function ov(id,o){S.ov[id]=Object.assign(S.ov[id]||{},o);save();draw()}
function pics(inp){return Promise.all([...inp.files].slice(0,3).map(f=>new Promise(res=>{const r=new FileReader();r.onload=()=>{const i=new Image();i.onload=()=>{const m=800,s=Math.min(1,m/Math.max(i.width,i.height)),c=document.createElement("canvas");c.width=i.width*s;c.height=i.height*s;c.getContext("2d").drawImage(i,0,0,c.width,c.height);res(c.toDataURL("image/jpeg",.6))};i.onerror=()=>res(null);i.src=r.result};r.onerror=()=>res(null);r.readAsDataURL(f)}))).then(a=>a.filter(Boolean))}
function chk(f,rules){let ok=1;document.querySelectorAll(".fe").forEach(e=>e.textContent="");for(const[n,m,t]of rules){const el=f.elements[n],v=el.type==="checkbox"?el.checked:String(el.value).trim();if(!v||t&&!t(v)){const e=$("#e-"+n);if(e)e.textContent=m;if(ok)el.focus();ok=0}}return ok}
async function regB(e){e.preventDefault();const f=e.target;if(!chk(f,[["name","Enter your business name."],["desc","Add a short description."],["area","Enter your address or area."],["wa","Enter a valid WhatsApp number.",v=>waNum(v)],["ok","Please agree to continue."]]))return;
const o={id:"u"+Date.now(),name:f.name.value.trim(),cat:f.cat.value,desc:f.desc.value.trim(),area:f.area.value.trim(),phone:f.phone.value.trim(),wa:waNum(f.wa.value),hours:f.hours.value.trim(),photos:await pics($("#ph")),status:"pending",featured:0};S.biz.push(o);if(!save()){S.biz.pop();return}
$("#app").innerHTML=`<div class="empty"><h2>Thank you!</h2><p>“${esc(o.name)}” was submitted and may need review before it appears publicly.</p><button class="btn" data-r="add">Add a listing</button></div>`}
async function addL(e){e.preventDefault();const f=e.target;if(!chk(f,[["title","Enter a title."],["desc","Add a description."],["price","Enter a price in ₦ (0 or more).",v=>+v>=0],["seller","Enter the seller name."],["loc","Enter the seller location or community."]]))return;
const o={id:"x"+Date.now(),biz:f.biz.value,title:f.title.value.trim(),desc:f.desc.value.trim(),cat:f.cat.value,type:f.type.value,price:+f.price.value,avail:f.avail.value,seller:f.seller.value.trim(),loc:f.loc.value.trim(),photos:await pics($("#ph")),status:"pending",featured:0};S.lst.push(o);if(!save()){S.lst.pop();return}
$("#app").innerHTML=`<div class="empty"><h2>Listing submitted</h2><p>It may need review before it appears publicly.</p><button class="btn" data-r="add">Add another</button></div>`}
function rev(e,id){e.preventDefault();const f=e.target;if(!chk(f,[["s","Choose a star rating.",()=>f.querySelector("[name=s]:checked")&&1],["n","Enter your name."],["t","Write a short review."]]))return;
S.rev.push({id:"v"+Date.now(),biz:id,name:f.n.value.trim(),stars:+f.s.value,text:f.t.value.trim()});if(save())draw()}
function report(id){const l=L().find(x=>x.id===id),d=$("#dlg");d.innerHTML=`<form method="dialog" onsubmit="event.preventDefault();doRep('${id}',this)"><h3>Report listing</h3><p class="mu">${esc(l.title)}</p><label for="rr">Reason</label><select id="rr" name="r"><option>Scam or fraud</option><option>Wrong or misleading information</option><option>Prohibited item</option><option>Other</option></select><label for="rn2">Details</label><textarea id="rn2" name="n"></textarea><div class="row" style="margin-top:12px"><button class="btn">Send report</button><button type="button" class="btn out" onclick="$('#dlg').close()">Cancel</button></div></form>`;d.showModal()}
function doRep(id,f){const l=L().find(x=>x.id===id);S.rep.push({id,title:l.title,reason:f.r.value,note:f.n.value.trim()||"—"});save();$("#dlg").innerHTML='<h3>Thank you</h3><p>Your report was recorded for review.</p><button class="btn" onclick="$(\'#dlg\').close()">Close</button>'}
cur=(location.hash.slice(1))||"home";draw();
</script></body></html>
