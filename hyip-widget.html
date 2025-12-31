<!-- HYIP NETWORK | LIVE MONITOR WIDGET FINAL RESPONSIVE WITH AUTO STOP/RESUME TIMER -->
<div id="hyip-widget" class="hyip-widget notranslate" translate="no" data-url="https://hyipnetwork-info.blogspot.com/2024/12/selwix-crypto-hasilkan-kripto-setiap.html"></div>

<style>
/* ========================= STYLES ========================= */
#hyip-widget{ position:sticky; top:20px; z-index:999; }
.hyip-widget{ width:100%; max-width:300px; min-height:455px; margin:auto; padding:18px 16px; border-radius:16px;
  box-sizing:border-box; color:#fff; font-family:Arial,Helvetica,sans-serif; position:relative;
  background:linear-gradient(160deg,#1d2233,#0a0d16);
  box-shadow:0 22px 40px rgba(0,0,0,.65), inset 0 1px 0 rgba(255,255,255,.06); overflow:hidden; }
.hyip-widget:before{ content:''; position:absolute; top:0; left:0; width:100%; height:38%;
  background:linear-gradient(to bottom,rgba(255,255,255,.14),transparent); pointer-events:none; }
.hyip-title{ font-size:17px; font-weight:bold; margin-bottom:14px; text-align:center; }
.hyip-status{ display:flex; align-items:center; justify-content:center; margin:0 auto 14px; padding:12px 0;
  width:80%; border-radius:28px; font-size:15px; font-weight:900; letter-spacing:1px; }
.paying{ background:linear-gradient(145deg,#27ae60,#1f7f4c); box-shadow: inset 0 2px 3px rgba(255,255,255,.22),
  inset 0 -5px 8px rgba(0,0,0,.5), 0 6px 14px rgba(0,0,0,.45); }
.pending{ background:linear-gradient(145deg,#f1c40f,#d4ac0d); color:#000; }
.notpaying{ background:linear-gradient(145deg,#e74c3c,#b03a2e); }
.hyip-info{ margin-top:10px; padding:10px 12px; border-radius:10px; font-size:12px; line-height:1.6;
  color:#d5d9ee; background:linear-gradient(145deg, rgba(255,255,255,.08), rgba(255,255,255,.02));
  box-shadow: inset 0 1px 2px rgba(255,255,255,.18), inset 0 -2px 4px rgba(0,0,0,.45), 0 6px 14px rgba(0,0,0,.35); }
.runtime{ position:absolute; bottom:92px; right:18px; text-align:right; font-size:11.5px; color:#9aa0b4; }
.runtime span{ display:block; margin-top:4px; font-size:14px; font-weight:bold; color:#ffffff; }
.monitor-by{ position:absolute; bottom:18px; left:50%; transform:translateX(-50%);
  width:100%; text-align:center; font-size:11px; color:#8f96ad; letter-spacing:1.3px; pointer-events:none; }
.monitor-name{ display:inline-block; margin-top:8px; font-size:22px; font-weight:900; letter-spacing:2.4px;
  padding:2px 14px; background:linear-gradient(90deg,#f7fbff,#9fd3ff,#f7fbff);
  -webkit-background-clip:text; -webkit-text-fill-color:transparent;
  text-shadow:0 0 6px rgba(159,211,255,.28),0 0 14px rgba(159,211,255,.18),0 0 26px rgba(159,211,255,.08); }
.hyip-widget a{ color:inherit; text-decoration:none; }

@media (max-width:480px){
  .hyip-widget{ min-height:430px; padding:16px 14px; }
  .hyip-title{ font-size:15px; }
  .hyip-status{ width:90%; font-size:14px; }
  .monitor-name{ font-size:18px; }
}
@media (max-width:360px){ .monitor-name{ font-size:16px; letter-spacing:2px; } }
</style>

<script>
(function(){
  const container = document.getElementById('hyip-widget');
  const manualURL = container.dataset.url;
  const manualTitle = "AtlantaBankers Modern Solution";
  const blogDomain = manualURL.split("/")[2];
  const feedURL = `https://${blogDomain}/feeds/posts/default?alt=json&max-results=100`;

  let startDate, timerInterval, stopDate = null;
  let currentStatus = '';

  function updateTimer(){
    if(!startDate) return;
    const now = new Date();
    let diff = Math.floor((now - startDate)/1000);
    const d = Math.floor(diff/86400); diff %= 86400;
    const h = Math.floor(diff/3600); diff %= 3600;
    const m = Math.floor(diff/60);
    const s = diff%60;
    document.getElementById('hyip-timer').textContent = d+'d '+h+'h '+m+'m '+s+'s';
  }

  function fetchPostAndUpdate(){
    fetch(feedURL)
      .then(r => r.json())
      .then(data => {
        const entries = data.feed.entry || [];
        const post = entries.find(e => e.link.find(l=>l.rel==='alternate').href === manualURL);
        if(!post) return;

        const labels = post.category ? post.category.map(c=>c.term.toLowerCase()) : [];
        let statusText = 'PENDING';
        let statusClass = 'pending';
        if(labels.includes('paying')){ statusText='PAYING'; statusClass='paying'; }
        else if(labels.includes('not paying')){ statusText='NOT PAYING'; statusClass='notpaying'; }

        const contentHTML = post.content.$t;
        const match = contentHTML.match(/<td>\s*This project started since\s*<\/td>\s*<td>\s*([^<]+)\s*<\/td>/i);
        if(!match) return;
        startDate = new Date(match[1] + " GMT+0700");

        // Render initial banner if kosong
        if(!container.innerHTML.trim()){
          container.innerHTML = `
            <a href="${manualURL}" target="_blank">
              <div class="hyip-title">${manualTitle}</div>
              <div class="hyip-status ${statusClass}">${statusText}</div>
              <div class="hyip-info">
                This project started since ${startDate.toLocaleDateString('en-US',{year:'numeric',month:'short',day:'numeric'})}<br>
                Source: HyipNetwork<br>
                Auto update enabled
              </div>
              <div class="runtime">
                RUNNING TIME
                <span id="hyip-timer">--</span>
              </div>
              <div class="monitor-by">
                MONITORED BY
                <span class="monitor-name">HYIP NETWORK</span>
              </div>
            </a>
          `;
        }

        // Jika status berubah
        if(statusClass !== currentStatus){
          currentStatus = statusClass;
          const statusDiv = container.querySelector('.hyip-status');
          statusDiv.className = `hyip-status ${statusClass}`;
          statusDiv.textContent = statusText;

          // Kontrol timer
          if(statusClass === 'notpaying'){
            stopDate = new Date();
            if(timerInterval) clearInterval(timerInterval);
            document.getElementById('hyip-timer').textContent =
              `This project has stopped paying since ${stopDate.toLocaleDateString('en-US',{year:'numeric',month:'short',day:'numeric'})}`;
          } else {
            if(timerInterval) clearInterval(timerInterval);
            updateTimer();
            timerInterval = setInterval(updateTimer, 1000);
          }
        }
      });
  }

  // Initial fetch
  fetchPostAndUpdate();
  // Update status every 30 detik
  setInterval(fetchPostAndUpdate, 30000);
})();
</script>
