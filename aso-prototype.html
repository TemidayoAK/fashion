<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Aṣọ — find the hands that will make it</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,400;0,9..144,600;1,9..144,500&family=Work+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --indigo:#1B2A4A; --gold:#C89B3C; --coral:#D9603B;
    --paper:#F6F1E7; --ink:#211A14; --line:#D8CFBE;
    --card:#FFFFFF;
    box-sizing:border-box;
    padding-top: env(safe-area-inset-top, 0px);
    padding-bottom: env(safe-area-inset-bottom, 0px);
  }
  *{box-sizing:inherit;}
  html{scroll-padding-top: env(safe-area-inset-top, 0px);}
  html,body{height:100%;}
  body{
    margin:0; background:var(--paper); color:var(--ink);
    font-family:'Work Sans', system-ui, sans-serif;
    -webkit-font-smoothing:antialiased;
  }
  h1,h2,h3{font-family:'Fraunces', Georgia, serif; margin:0; font-weight:600;}
  a{color:inherit;}
  .weave{
    position:fixed; inset:0; pointer-events:none; opacity:.05; z-index:0;
    background-image: repeating-linear-gradient(45deg, var(--ink) 0 2px, transparent 2px 18px),
                       repeating-linear-gradient(-45deg, var(--ink) 0 2px, transparent 2px 18px);
  }
  header{
    position:sticky; top:0; z-index:10;
    display:flex; align-items:center; justify-content:space-between;
    padding: max(18px, env(safe-area-inset-top)) 24px 18px;
    background:var(--paper); border-bottom:1px solid var(--line);
  }
  .logo{font-family:'Fraunces',serif; font-size:22px; font-weight:600; letter-spacing:.01em;}
  .logo em{font-style:italic; color:var(--coral);}
  nav button{
    background:none; border:1px solid var(--ink); color:var(--ink);
    font-family:'Work Sans'; font-size:13px; padding:8px 14px; border-radius:999px;
    cursor:pointer;
  }
  main{max-width:880px; margin:0 auto; padding:0 24px 80px; position:relative; z-index:1;}
  .view{display:none; animation:fade .35s ease;}
  .view.active{display:block;}
  @keyframes fade{from{opacity:0; transform:translateY(6px);} to{opacity:1; transform:none;}}

  /* Landing */
  .hero{padding:64px 0 40px; max-width:640px;}
  .hero h1{font-size:44px; line-height:1.08; font-weight:600;}
  .hero h1 i{font-style:italic; color:var(--coral);}
  .hero p{font-size:17px; line-height:1.55; color:#4a4038; max-width:480px; margin-top:16px;}
  .paths{display:grid; grid-template-columns:1fr 1fr; gap:16px; margin-top:36px;}
  @media (max-width:560px){.paths{grid-template-columns:1fr;}}
  .path-card{
    border:1px solid var(--ink); border-radius:2px; padding:22px;
    cursor:pointer; background:var(--card); transition:transform .15s ease, box-shadow .15s ease;
  }
  .path-card:hover{transform:translateY(-2px); box-shadow:4px 4px 0 var(--ink);}
  .path-card .tag{font-size:12px; color:var(--gold); font-weight:600;}
  .path-card h3{font-size:20px; margin-top:8px;}
  .path-card p{font-size:14px; color:#5a5048; margin-top:8px; line-height:1.5;}

  /* Shared */
  .crumb{font-size:13px; color:#7a6f62; cursor:pointer; margin:28px 0 4px; display:inline-block;}
  .crumb:hover{color:var(--ink);}
  .section-title{font-size:28px; margin:6px 0 6px;}
  .section-sub{font-size:14px; color:#5a5048; margin-bottom:28px; max-width:480px;}

  /* Form */
  .field{margin-bottom:18px;}
  label{display:block; font-size:13px; font-weight:600; margin-bottom:6px; color:#3a322b;}
  input,select,textarea{
    width:100%; border:1px solid var(--line); background:var(--card); border-radius:2px;
    padding:11px 12px; font-family:'Work Sans'; font-size:14px; color:var(--ink);
  }
  input:focus,select:focus,textarea:focus{outline:2px solid var(--indigo); outline-offset:1px;}
  textarea{resize:vertical; min-height:70px;}
  .row2{display:grid; grid-template-columns:1fr 1fr; gap:16px;}
  @media (max-width:560px){.row2{grid-template-columns:1fr;}}
  .btn{
    border:none; border-radius:999px; padding:13px 26px; font-family:'Work Sans'; font-weight:600;
    font-size:14px; cursor:pointer; background:var(--indigo); color:#fff;
  }
  .btn:focus-visible{outline:2px solid var(--coral); outline-offset:2px;}
  .btn.secondary{background:none; border:1px solid var(--ink); color:var(--ink);}
  .btn.block{width:100%; margin-top:8px;}

  /* Matches */
  .match-list{display:flex; flex-direction:column; gap:14px; margin-top:20px;}
  .match{
    display:flex; gap:16px; align-items:center; background:var(--card);
    border:1px solid var(--line); border-radius:2px; padding:16px;
    cursor:pointer;
  }
  .match:hover{border-color:var(--ink);}
  .swatch{width:56px; height:56px; border-radius:50%; flex:none;}
  .match-info{flex:1; min-width:0;}
  .match-info h4{font-family:'Fraunces'; font-size:17px; font-weight:600; margin:0;}
  .match-meta{font-size:13px; color:#6a5f54; margin-top:3px;}
  .match-price{font-size:13px; font-weight:600; color:var(--indigo); white-space:nowrap;}

  /* Profile */
  .profile-head{display:flex; gap:20px; align-items:flex-start; margin-top:20px;}
  .avatar{width:72px; height:72px; border-radius:50%; flex:none;}
  .stars{color:var(--gold); font-size:14px; margin-top:4px;}
  .portfolio-grid{display:grid; grid-template-columns:repeat(3,1fr); gap:10px; margin-top:24px;}
  .swatch-tile{aspect-ratio:1; border-radius:2px;}
  .bio{font-size:14px; line-height:1.6; color:#4a4038; margin-top:18px; max-width:520px;}

  /* Request modal-ish inline */
  .panel{background:var(--card); border:1px solid var(--line); border-radius:2px; padding:22px; margin-top:24px; max-width:440px;}

  /* Confirmation */
  .confirm{text-align:left; padding:60px 0;}
  .confirm .mark{width:44px; height:44px; border-radius:50%; background:var(--coral); display:flex; align-items:center; justify-content:center; color:#fff; font-size:20px; margin-bottom:20px;}

  /* Designer dashboard */
  .req-list{display:flex; flex-direction:column; gap:12px; margin-top:20px;}
  .req-item{background:var(--card); border:1px solid var(--line); border-radius:2px; padding:16px; display:flex; justify-content:space-between; gap:16px; align-items:center;}
  .req-item .meta{font-size:13px; color:#6a5f54; margin-top:4px;}
  .badge{font-size:11px; font-weight:600; padding:3px 9px; border-radius:999px; background:#EFE6D3; color:#8a6a1f;}

  /* Order status */
  .steps{margin-top:28px; max-width:440px;}
  .step{display:flex; gap:14px; padding-bottom:26px; position:relative;}
  .step:last-child{padding-bottom:0;}
  .step::before{
    content:''; position:absolute; left:9px; top:22px; bottom:0; width:1px; background:var(--line);
  }
  .step:last-child::before{display:none;}
  .step .dot{
    width:20px; height:20px; border-radius:50%; flex:none; border:1px solid var(--line);
    background:var(--card); display:flex; align-items:center; justify-content:center; font-size:11px; z-index:1;
  }
  .step.done .dot{background:var(--indigo); border-color:var(--indigo); color:#fff;}
  .step.current .dot{background:var(--coral); border-color:var(--coral); color:#fff;}
  .step h4{font-family:'Fraunces'; font-size:15px; font-weight:600; margin:0;}
  .step p{font-size:13px; color:#6a5f54; margin:3px 0 0;}
  .step.pending h4, .step.pending p{color:#a89d8f;}
</style>
</head>
<body>
<div class="weave"></div>
<header>
  <div class="logo">Aṣ<em>ọ</em></div>
  <nav>
    <button onclick="go('landing')" id="resetBtn">Start over</button>
  </nav>
</header>

<main>

  <!-- LANDING -->
  <section class="view active" id="landing">
    <div class="hero">
      <h1>Find the hands<br>that will <i>make it</i>.</h1>
      <p>Describe the dress you want, or the work you do — Aṣọ puts Lagos designers and clients in the same room, without the endless WhatsApp back-and-forth.</p>
    </div>
    <div class="paths">
      <div class="path-card" onclick="go('clientSignup')">
        <div class="tag">FOR CLIENTS</div>
        <h3>I need something made</h3>
        <p>Post what you want sewn, and hear back from designers who actually take that kind of work.</p>
      </div>
      <div class="path-card" onclick="go('designerSignup')">
        <div class="tag">FOR DESIGNERS</div>
        <h3>I make things</h3>
        <p>Build a portfolio, get matched to real requests, and quote on your own terms.</p>
      </div>
    </div>
  </section>

  <!-- CLIENT SIGNUP -->
  <section class="view" id="clientSignup">
    <span class="crumb" onclick="go('landing')">← back</span>
    <h2 class="section-title">Create your account</h2>
    <p class="section-sub">Just enough to post a request and keep track of replies.</p>
    <div class="row2">
      <div class="field">
        <label>Full name</label>
        <input type="text" id="cSName">
      </div>
      <div class="field">
        <label>Phone / WhatsApp</label>
        <input type="tel" id="cSPhone" placeholder="080...">
      </div>
    </div>
    <div class="field">
      <label>Email</label>
      <input type="email" id="cSEmail" placeholder="you@example.com">
    </div>
    <div class="field">
      <label>Set a password</label>
      <input type="password" id="cSPassword" placeholder="At least 8 characters">
    </div>
    <button class="btn" onclick="createClientAccount()">Create account →</button>
    <p id="cSError" style="font-size:13px; color:var(--coral); margin-top:10px; display:none;"></p>
  </section>

  <!-- CLIENT: REQUEST FORM -->
  <section class="view" id="clientForm">
    <span class="crumb" onclick="go('landing')">← back</span>
    <h2 class="section-title">What are we making?</h2>
    <p class="section-sub">A few details help designers know if it's a fit before they quote.</p>
    <div class="field">
      <label>Occasion</label>
      <select id="occasion">
        <option>Owambe / party</option>
        <option>Wedding — bride</option>
        <option>Wedding — guest / aso-ebi</option>
        <option>Everyday wear</option>
        <option>Corporate</option>
      </select>
    </div>
    <div class="row2">
      <div class="field">
        <label>Fabric</label>
        <select id="fabric">
          <option>Ankara</option>
          <option>Lace</option>
          <option>Aso-oke</option>
          <option>Plain cotton / linen</option>
          <option>Not sure yet</option>
        </select>
      </div>
      <div class="field">
        <label>Budget (₦)</label>
        <select id="budget">
          <option>15,000 – 30,000</option>
          <option>30,000 – 60,000</option>
          <option>60,000 – 120,000</option>
          <option>120,000+</option>
        </select>
      </div>
    </div>
    <div class="row2">
      <div class="field">
        <label>Needed by</label>
        <input type="date" id="deadline">
      </div>
      <div class="field">
        <label>Area</label>
        <input type="text" id="area" placeholder="e.g. Lekki, Yaba, Surulere">
      </div>
    </div>
    <div class="field">
      <label>Anything else</label>
      <textarea id="notes" placeholder="Style, reference, measurements you already have..."></textarea>
    </div>
    <button class="btn" onclick="go('matches')">Find designers →</button>
  </section>

  <!-- CLIENT: MATCHES -->
  <section class="view" id="matches">
    <span class="crumb" onclick="go('clientForm')">← edit request</span>
    <h2 class="section-title">3 designers near you take this kind of work</h2>
    <p class="section-sub">Ranked by fit to your fabric, budget and deadline.</p>
    <div class="match-list" id="matchList"></div>
  </section>

  <!-- DESIGNER PROFILE -->
  <section class="view" id="profile">
    <span class="crumb" onclick="go('matches')">← back to matches</span>
    <div class="profile-head">
      <div class="avatar" id="pAvatar"></div>
      <div>
        <h2 id="pName" style="font-size:22px;"></h2>
        <div class="match-meta" id="pMeta"></div>
        <div class="stars" id="pStars"></div>
      </div>
    </div>
    <p class="bio" id="pBio"></p>
    <div class="portfolio-grid" id="pGrid"></div>
    <div class="panel">
      <h3 style="font-size:16px;">Send this request</h3>
      <p style="font-size:13px; color:#6a5f54; margin-top:6px;">Your details from the previous step go with it — add a note if you like.</p>
      <div class="field" style="margin-top:14px;">
        <textarea placeholder="Optional note to the designer..."></textarea>
      </div>
      <button class="btn block" onclick="sendRequest()">Send request</button>
    </div>
  </section>

  <!-- CONFIRMATION -->
  <section class="view" id="confirm">
    <div class="confirm">
      <div class="mark">✓</div>
      <h2 class="section-title">Request sent to <span id="cName"></span></h2>
      <p class="section-sub">They usually reply within a day with a quote and a few questions. You'll get a message here when they do.</p>
      <button class="btn secondary" onclick="go('matches')">See other designers</button>
      &nbsp;
      <button class="btn" onclick="go('orderStatus')">Track order →</button>
    </div>
  </section>

  <!-- ORDER STATUS -->
  <section class="view" id="orderStatus">
    <span class="crumb" onclick="go('landing')">← back</span>
    <h2 class="section-title">Order with <span id="osName"></span></h2>
    <p class="section-sub">This updates as your designer moves through the work.</p>
    <div class="steps" id="stepList"></div>
  </section>

  <!-- DESIGNER SIGNUP -->
  <section class="view" id="designerSignup">
    <span class="crumb" onclick="go('landing')">← back</span>
    <h2 class="section-title">Create your designer profile</h2>
    <p class="section-sub">This is what clients see when your profile turns up in their matches.</p>
    <div class="row2">
      <div class="field">
        <label>Full name / brand</label>
        <input type="text" id="dName" placeholder="e.g. Tunde Fits">
      </div>
      <div class="field">
        <label>Area</label>
        <input type="text" id="dArea" placeholder="e.g. Surulere">
      </div>
    </div>
    <div class="row2">
      <div class="field">
        <label>Email</label>
        <input type="email" id="dEmail" placeholder="you@example.com">
      </div>
      <div class="field">
        <label>Phone / WhatsApp</label>
        <input type="tel" id="dPhone" placeholder="080...">
      </div>
    </div>
    <div class="row2">
      <div class="field">
        <label>Specialty</label>
        <select id="dSpecialty">
          <option>Owambe & aso-ebi</option>
          <option>Bridal & lace</option>
          <option>Everyday & corporate</option>
          <option>Aso-oke & traditional</option>
        </select>
      </div>
      <div class="field">
        <label>Typical price range (₦)</label>
        <select id="dPrice">
          <option>15,000 – 40,000</option>
          <option>40,000 – 80,000</option>
          <option>80,000 – 200,000</option>
          <option>200,000+</option>
        </select>
      </div>
    </div>
    <div class="field">
      <label>Set a password</label>
      <input type="password" id="dPassword" placeholder="At least 8 characters">
    </div>
    <div class="field">
      <label>Short bio</label>
      <textarea id="dBio" placeholder="What you make, how you work, what you're known for..."></textarea>
    </div>
    <button class="btn" onclick="createDesignerAccount()">Create account →</button>
    <p id="dError" style="font-size:13px; color:var(--coral); margin-top:10px; display:none;"></p>
  </section>

  <!-- DESIGNER DASHBOARD -->
  <section class="view" id="designerDash">
    <span class="crumb" onclick="go('landing')">← sign out</span>
    <h2 class="section-title">Welcome, <span id="ddName">Designer</span></h2>
    <p class="section-sub" id="ddSub">Set to: Ankara, lace · Lagos mainland · owambe &amp; weddings</p>
    <div class="req-list">
      <div class="req-item">
        <div>
          <h4 style="font-family:'Fraunces'; font-weight:600; margin:0;">Owambe gown, Ankara</h4>
          <div class="meta">Yaba · ₦30,000–60,000 · needed in 9 days</div>
        </div>
        <button class="btn secondary" onclick="quoteSent(this)">Send quote</button>
      </div>
      <div class="req-item">
        <div>
          <h4 style="font-family:'Fraunces'; font-weight:600; margin:0;">Aso-ebi set for 3</h4>
          <div class="meta">Ikeja · ₦120,000+ · needed in 3 weeks</div>
        </div>
        <button class="btn secondary" onclick="quoteSent(this)">Send quote</button>
      </div>
      <div class="req-item">
        <div>
          <h4 style="font-family:'Fraunces'; font-weight:600; margin:0;">Simple lace top</h4>
          <div class="meta">Surulere · ₦15,000–30,000 · needed in 5 days</div>
        </div>
        <button class="btn secondary" onclick="quoteSent(this)">Send quote</button>
      </div>
    </div>
  </section>

</main>

<script>
const designers = [
  {name:"Yemisi Alade Couture", specialty:"Owambe & aso-ebi", area:"Yaba", price:"₦35,000–70,000", turnaround:"7–10 days", rating:"★★★★★ 4.9 (61)",
   bio:"Twelve years cutting for Lagos parties. Known for structured Ankara gowns with clean necklines — send a reference photo and I'll tell you honestly if it'll work on your fabric.", hue:"#C89B3C"},
  {name:"Studio Adaeze", specialty:"Bridal & lace", area:"Ikeja", price:"₦80,000–200,000", turnaround:"3–4 weeks", rating:"★★★★★ 5.0 (34)",
   bio:"Bridal-focused, small client list by design. Two fittings included on every commission, plus a muslin mock-up before we touch your real fabric.", hue:"#1B2A4A"},
  {name:"Tunde Fits", specialty:"Everyday & corporate", area:"Surulere", price:"₦15,000–40,000", turnaround:"4–6 days", rating:"★★★★☆ 4.6 (89)",
   bio:"Fast turnaround for everyday pieces — corporate wear, simple tops, alterations. Not the place for elaborate bridal work, but reliable for the rest.", hue:"#D9603B"}
];
let chosen = null;

function go(id){
  document.querySelectorAll('.view').forEach(v=>v.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  if(id==='matches') renderMatches();
  window.scrollTo({top:0, behavior:'instant'});
}

function renderMatches(){
  const list = document.getElementById('matchList');
  list.innerHTML = '';
  designers.forEach((d,i)=>{
    const el = document.createElement('div');
    el.className = 'match';
    el.onclick = ()=>openProfile(i);
    el.innerHTML = `
      <div class="swatch" style="background:${d.hue}"></div>
      <div class="match-info">
        <h4>${d.name}</h4>
        <div class="match-meta">${d.specialty} · ${d.area} · ${d.turnaround}</div>
      </div>
      <div class="match-price">${d.price}</div>`;
    list.appendChild(el);
  });
}

function openProfile(i){
  chosen = designers[i];
  document.getElementById('pAvatar').style.background = chosen.hue;
  document.getElementById('pName').textContent = chosen.name;
  document.getElementById('pMeta').textContent = `${chosen.specialty} · ${chosen.area} · ${chosen.price}`;
  document.getElementById('pStars').textContent = chosen.rating;
  document.getElementById('pBio').textContent = chosen.bio;
  const grid = document.getElementById('pGrid');
  grid.innerHTML = '';
  const hues = [chosen.hue, '#EFE6D3', '#D8CFBE', chosen.hue, '#EFE6D3', '#D8CFBE'];
  hues.forEach(h=>{
    const t = document.createElement('div');
    t.className = 'swatch-tile';
    t.style.background = h;
    grid.appendChild(t);
  });
  go('profile');
}

function sendRequest(){
  document.getElementById('cName').textContent = chosen.name;
  document.getElementById('osName').textContent = chosen.name;
  renderSteps();
  go('confirm');
}

const orderSteps = [
  {title:"Request sent", desc:"Your request went to " + "the designer.", state:"done"},
  {title:"Quote received", desc:"They've reviewed it and sent a price.", state:"current"},
  {title:"Fabric sourced", desc:"Material confirmed and ready to cut.", state:"pending"},
  {title:"Cutting & sewing", desc:"Work is underway.", state:"pending"},
  {title:"Fitting", desc:"You'll be contacted to try it on.", state:"pending"},
  {title:"Ready for pickup", desc:"Final piece is done.", state:"pending"}
];

function renderSteps(){
  const list = document.getElementById('stepList');
  list.innerHTML = '';
  orderSteps.forEach(s=>{
    const el = document.createElement('div');
    el.className = 'step ' + s.state;
    el.innerHTML = `
      <div class="dot">${s.state==='done' ? '✓' : ''}</div>
      <div>
        <h4>${s.title}</h4>
        <p>${s.desc}</p>
      </div>`;
    list.appendChild(el);
  });
}

function createClientAccount(){
  const name = document.getElementById('cSName').value.trim();
  const email = document.getElementById('cSEmail').value.trim();
  const password = document.getElementById('cSPassword').value;
  const errEl = document.getElementById('cSError');

  if(!name || !email || !password){
    errEl.textContent = 'Name, email and password are required.';
    errEl.style.display = 'block';
    return;
  }
  if(password.length < 8){
    errEl.textContent = 'Password needs to be at least 8 characters.';
    errEl.style.display = 'block';
    return;
  }
  errEl.style.display = 'none';
  go('clientForm');
}

function createDesignerAccount(){
  const name = document.getElementById('dName').value.trim();
  const email = document.getElementById('dEmail').value.trim();
  const password = document.getElementById('dPassword').value;
  const area = document.getElementById('dArea').value.trim();
  const errEl = document.getElementById('dError');

  if(!name || !email || !password){
    errEl.textContent = 'Name, email and password are required.';
    errEl.style.display = 'block';
    return;
  }
  if(password.length < 8){
    errEl.textContent = 'Password needs to be at least 8 characters.';
    errEl.style.display = 'block';
    return;
  }
  errEl.style.display = 'none';

  document.getElementById('ddName').textContent = name;
  document.getElementById('ddSub').textContent =
    `Set to: ${document.getElementById('dSpecialty').value} · ${area || 'Lagos'} · ${document.getElementById('dPrice').value}`;

  go('designerDash');
}

function quoteSent(btn){
  btn.textContent = 'Quote sent ✓';
  btn.disabled = true;
  btn.style.opacity = '.6';
}
</script>
</body>
</html>
