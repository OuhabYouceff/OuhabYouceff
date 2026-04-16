
<style>
*{box-sizing:border-box;margin:0;padding:0;}
.wrap{max-width:900px;padding:2rem 0;font-family:var(--font-mono);}
.hero{display:flex;align-items:flex-start;gap:1.5rem;margin-bottom:2rem;flex-wrap:wrap;}
.avatar{width:64px;height:64px;border-radius:50%;background:var(--color-background-info);display:flex;align-items:center;justify-content:center;font-size:18px;font-weight:500;color:var(--color-text-info);flex-shrink:0;border:1.5px solid var(--color-border-secondary);}
.name{font-size:28px;font-weight:500;color:var(--color-text-primary);font-family:var(--font-sans);}
.cursor{display:inline-block;width:3px;height:24px;background:var(--color-text-info);vertical-align:middle;margin-left:3px;animation:blink 1s step-end infinite;}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
.sub{font-size:13px;color:var(--color-text-secondary);margin-top:5px;}
.badges{display:flex;flex-wrap:wrap;gap:6px;margin-top:10px;}
.badge{font-size:11px;padding:3px 9px;border-radius:4px;font-weight:500;}
.b-ai{background:#EEEDFE;color:#3C3489;}.b-startup{background:#E1F5EE;color:#085041;}.b-open{background:#FAEEDA;color:#633806;}

.layout{display:grid;grid-template-columns:1fr 220px;gap:2rem;align-items:start;}
@media(max-width:650px){.layout{grid-template-columns:1fr;}}

.sh{font-size:11px;letter-spacing:.1em;text-transform:uppercase;color:var(--color-text-tertiary);display:flex;align-items:center;gap:8px;margin-bottom:.75rem;}
.sh::after{content:'';flex:1;height:.5px;background:var(--color-border-tertiary);}
.section{margin-bottom:1.5rem;}
.about-p{font-size:13px;color:var(--color-text-secondary);line-height:1.8;border-left:2px solid var(--color-border-info);padding-left:12px;}

.sk-group{margin-bottom:10px;}
.sk-group-label{font-size:10px;letter-spacing:.08em;text-transform:uppercase;color:var(--color-text-tertiary);margin-bottom:5px;}
.skills{display:flex;flex-wrap:wrap;gap:5px;}
.sk{font-size:11px;padding:3px 9px;border-radius:4px;background:var(--color-background-secondary);color:var(--color-text-secondary);border:.5px solid var(--color-border-tertiary);}
.sk.ai{border-color:#AFA9EC;color:#3C3489;background:#EEEDFE;}
.sk.web{border-color:#9FE1CB;color:#085041;background:#E1F5EE;}
.sk.lang{border-color:#B5D4F4;color:#0C447C;background:#E6F1FB;}
.sk.tool{border-color:#D3D1C7;color:#444441;}

.focus-grid{display:grid;grid-template-columns:1fr 1fr;gap:7px;}
.fc{background:var(--color-background-primary);border:.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-md);padding:8px 10px;}
.fc-title{font-size:12px;font-weight:500;color:var(--color-text-primary);margin-bottom:2px;font-family:var(--font-sans);}
.fc-desc{font-size:11px;color:var(--color-text-secondary);line-height:1.5;}

.links{display:flex;flex-wrap:wrap;gap:6px;}
.lnk{font-size:12px;padding:5px 12px;border-radius:6px;border:.5px solid var(--color-border-secondary);color:var(--color-text-secondary);background:var(--color-background-primary);text-decoration:none;cursor:pointer;}
.lnk:hover{background:var(--color-background-secondary);}

.game-col{}
.game-label{font-size:10px;letter-spacing:.15em;text-transform:uppercase;color:var(--color-text-tertiary);text-align:center;margin-bottom:6px;}
.game-wrap{background:var(--color-background-secondary);border:.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);padding:10px;display:flex;flex-direction:column;align-items:center;gap:8px;}
.score-row{display:flex;gap:16px;}
.sbox{text-align:center;}
.sval{font-size:16px;font-weight:500;color:var(--color-text-primary);}
.slbl{font-size:10px;color:var(--color-text-tertiary);}
#gc{border:.5px solid var(--color-border-secondary);border-radius:3px;background:#0a0a0a;display:block;}
.game-mode-row{display:flex;gap:6px;}
.gbtn{font-size:11px;padding:4px 12px;border-radius:4px;border:.5px solid var(--color-border-secondary);color:var(--color-text-secondary);background:var(--color-background-primary);cursor:pointer;}
.gbtn:hover{background:var(--color-background-secondary);}
.gbtn.active{border-color:#7F77DD;color:#3C3489;}
.game-hint{font-size:10px;color:var(--color-text-tertiary);text-align:center;line-height:1.7;}
.ai-badge{font-size:10px;padding:2px 8px;background:#EEEDFE;color:#3C3489;border-radius:4px;border:.5px solid #AFA9EC;}
</style>

<div class="wrap">
  <div class="hero">
    <div class="avatar">YO</div>
    <div>
      <div class="name">Youcef Ouhab<span class="cursor"></span></div>
      <div class="sub">CS &amp; AI Engineering · Startup Founder · Tunis, TN</div>
      <div class="badges">
        <span class="badge b-ai">Generative AI</span>
        <span class="badge b-startup">Startup founder</span>
        <span class="badge b-open">Open to collab</span>
      </div>
    </div>
  </div>

  <div class="layout">
    <div>
      <div class="section">
        <div class="sh">about</div>
        <p class="about-p">Final-year CS &amp; AI student at ESPRIT. I build things at the intersection of generative AI, predictive analytics, and real-world product engineering. Currently founding a startup. Passionate about multimodal AI and sustainable tech — not just as research, but as things worth shipping.</p>
      </div>

      <div class="section">
        <div class="sh">tech stack</div>
        <div class="sk-group">
          <div class="sk-group-label">AI / ML</div>
          <div class="skills">
            <span class="sk ai">Python</span>
            <span class="sk ai">Machine learning</span>
            <span class="sk ai">Deep learning</span>
            <span class="sk ai">NLP</span>
            <span class="sk ai">LLMs</span>
            <span class="sk ai">RAG</span>
            <span class="sk ai">AI Agents</span>
            <span class="sk ai">LangChain</span>
            <span class="sk ai">LangGraph</span>
            <span class="sk ai">MCP</span>
            <span class="sk ai">OpenAI API</span>
            <span class="sk ai">HuggingFace</span>
          </div>
        </div>
        <div class="sk-group">
          <div class="sk-group-label">Frontend</div>
          <div class="skills">
            <span class="sk web">React</span>
            <span class="sk web">JavaScript</span>
            <span class="sk web">HTML / CSS</span>
            <span class="sk web">Bootstrap</span>
          </div>
        </div>
        <div class="sk-group">
          <div class="sk-group-label">Languages &amp; data</div>
          <div class="skills">
            <span class="sk lang">C / C++</span>
            <span class="sk lang">PHP</span>
            <span class="sk lang">MySQL</span>
          </div>
        </div>
        <div class="sk-group">
          <div class="sk-group-label">Tools</div>
          <div class="skills">
            <span class="sk tool">Git</span>
            <span class="sk tool">Photoshop</span>
            <span class="sk tool">Illustrator</span>
            <span class="sk tool">Premiere Pro</span>
          </div>
        </div>
      </div>

      <div class="section">
        <div class="sh">focus</div>
        <div class="focus-grid">
          <div class="fc"><div class="fc-title">Generative AI</div><div class="fc-desc">LLMs, agents, prompt engineering</div></div>
          <div class="fc"><div class="fc-title">Predictive analytics</div><div class="fc-desc">ML pipelines for real decisions</div></div>
          <div class="fc"><div class="fc-title">Multimodal AI</div><div class="fc-desc">Vision + language architectures</div></div>
          <div class="fc"><div class="fc-title">Sustainable tech</div><div class="fc-desc">AI for climate &amp; energy</div></div>
        </div>
      </div>

      <div class="section">
        <div class="sh">connect</div>
        <div class="links">
          <a class="lnk" href="https://www.linkedin.com/in/youcef-ouhab/" target="_blank">LinkedIn</a>
          <a class="lnk" href="https://www.github.com/OuhabYouceff" target="_blank">GitHub</a>
          <a class="lnk" href="https://www.youcef-ouhab.com" target="_blank">Portfolio</a>
          <a class="lnk" href="mailto:ouhab.youceff@gmail.com">Email</a>
          <a class="lnk" href="http://www.instagram.com/youcef_ouhab/" target="_blank">Instagram</a>
        </div>
      </div>
    </div>

    <div class="game-col">
      <div class="game-label">— beat my score —</div>
      <div class="game-wrap">
        <div class="score-row">
          <div class="sbox"><div class="sval" id="sc">0</div><div class="slbl">score</div></div>
          <div class="sbox"><div class="sval" id="ln">0</div><div class="slbl">lines</div></div>
          <div class="sbox"><div class="sval" id="lv">1</div><div class="slbl">level</div></div>
        </div>
        <canvas id="gc" width="160" height="320"></canvas>
        <div class="game-mode-row">
          <button class="gbtn active" id="autoBtn">AI demo</button>
          <button class="gbtn" id="playBtn">play</button>
        </div>
        <div class="game-hint" id="ghint"><span class="ai-badge">AI playing</span> &nbsp;watch or click "play"</div>
      </div>
    </div>
  </div>
</div>

<script>
const cv=document.getElementById('gc'),cx=cv.getContext('2d');
const C=10,R=20,S=16;
const PAL=['#7F77DD','#1D9E75','#D85A30','#378ADD','#D4537E','#EF9F27','#E24B4A'];
const SHP=[[[1,1,1,1]],[[1,1],[1,1]],[[0,1,0],[1,1,1]],[[1,0,0],[1,1,1]],[[0,0,1],[1,1,1]],[[0,1,1],[1,1,0]],[[1,1,0],[0,1,1]]];
let board,piece,score,lines,level,raf,lastT,dropC,dropI,mode='ai',paused=false,gameOver=false,aiTimer=0;

function nb(){return Array.from({length:R},()=>Array(C).fill(0));}
function rp(){const i=Math.floor(Math.random()*SHP.length);const sh=SHP[i].map(r=>[...r]);return{sh,col:PAL[i],x:Math.floor(C/2)-Math.floor(sh[0].length/2),y:0};}
function coll(p,dx=0,dy=0,sh=null){const s=sh||p.sh;for(let r=0;r<s.length;r++)for(let c=0;c<s[r].length;c++){if(!s[r][c])continue;const nx=p.x+c+dx,ny=p.y+r+dy;if(nx<0||nx>=C||ny>=R)return true;if(ny>=0&&board[ny][nx])return true;}return false;}
function rot(sh){const nr=sh[0].length,nc=sh.length,o=Array.from({length:nr},()=>Array(nc).fill(0));for(let r=0;r<nc;r++)for(let c=0;c<nr;c++)o[c][nc-1-r]=sh[r][c];return o;}
function lock(){piece.sh.forEach((row,r)=>row.forEach((v,c)=>{if(v&&piece.y+r>=0)board[piece.y+r][piece.x+c]=piece.col;}));let cl=0;for(let r=R-1;r>=0;){if(board[r].every(c=>c)){board.splice(r,1);board.unshift(Array(C).fill(0));cl++;}else r--;}if(cl){score+=([0,100,300,500,800][cl])*level;lines+=cl;level=Math.floor(lines/10)+1;dropI=Math.max(80,1000-level*90);}document.getElementById('sc').textContent=score;document.getElementById('ln').textContent=lines;document.getElementById('lv').textContent=level;piece=rp();if(coll(piece)){if(mode==='ai'){board=nb();score=0;lines=0;level=1;dropI=400;piece=rp();}else{gameOver=true;cancelAnimationFrame(raf);drawGO();}}}
function drawCell(col,x,y,a=1){cx.globalAlpha=a;cx.fillStyle=col;cx.fillRect(x*S+1,y*S+1,S-2,S-2);cx.fillStyle='rgba(255,255,255,0.15)';cx.fillRect(x*S+1,y*S+1,S-2,3);cx.globalAlpha=1;}
function draw(){cx.fillStyle='#0a0a0a';cx.fillRect(0,0,cv.width,cv.height);cx.strokeStyle='rgba(255,255,255,0.03)';for(let r=0;r<R;r++)for(let c=0;c<C;c++){cx.strokeRect(c*S,r*S,S,S);if(board[r][c])drawCell(board[r][c],c,r);}if(!piece)return;let g={...piece,y:piece.y};while(!coll(g,0,1))g.y++;piece.sh.forEach((row,r)=>row.forEach((v,c)=>{if(v){drawCell(piece.col,piece.x+c,g.y+r,0.15);drawCell(piece.col,piece.x+c,piece.y+r);}}));}
function drawGO(){cx.fillStyle='rgba(0,0,0,0.75)';cx.fillRect(0,cv.height/2-28,cv.width,56);cx.fillStyle='#fff';cx.font='500 13px monospace';cx.textAlign='center';cx.fillText('game over',cv.width/2,cv.height/2-8);cx.font='11px monospace';cx.fillStyle='rgba(255,255,255,0.5)';cx.fillText('score: '+score,cv.width/2,cv.height/2+14);}

function aiMove(){
  if(!piece)return;
  let best=null,bestScore=-Infinity;
  const rotations=[piece.sh,rot(piece.sh),rot(rot(piece.sh)),rot(rot(rot(piece.sh)))];
  const seen=new Set();
  for(let ri=0;ri<rotations.length;ri++){
    const sh=rotations[ri];const key=JSON.stringify(sh);if(seen.has(key))continue;seen.add(key);
    for(let x=0;x<=C-sh[0].length;x++){
      const tp={...piece,sh,x};if(coll(tp,0,0,sh))continue;
      let y=piece.y;while(!coll({...tp,y:y+1},0,0,sh))y++;
      const tb=board.map(r=>[...r]);
      sh.forEach((row,r)=>row.forEach((v,c)=>{if(v&&y+r>=0&&y+r<R)tb[y+r][x+c]=piece.col;}));
      let cleared=0,holes=0,bump=0,height=0,agg=0;
      const cols=Array(C).fill(0);
      for(let c=0;c<C;c++){for(let r=0;r<R;r++){if(tb[r][c]){cols[c]=R-r;break;}}}
      agg=cols.reduce((a,b)=>a+b,0);
      for(let r=0;r<R;r++){if(tb[r].every(c=>c))cleared++;}
      for(let c=0;c<C;c++){let found=false;for(let r=0;r<R;r++){if(tb[r][c])found=true;else if(found)holes++;}}
      for(let c=0;c<C-1;c++)bump+=Math.abs(cols[c]-cols[c+1]);
      height=Math.max(...cols);
      const s=cleared*15-holes*8-bump*0.6-agg*0.4-height*0.7;
      if(s>bestScore){bestScore=s;best={sh,x,y,ri};}
    }
  }
  if(best){
    for(let i=0;i<best.ri;i++){const r=rot(piece.sh);if(!coll(piece,0,0,r))piece.sh=r;}
    piece.x=best.x;piece.y=best.y;lock();
  }
}

function loop(ts){
  if(gameOver||paused)return;
  const dt=ts-lastT;lastT=ts;dropC+=dt;
  if(mode==='ai'){
    aiTimer+=dt;
    if(aiTimer>320){aiTimer=0;aiMove();}
  } else {
    if(dropC>=dropI){dropC=0;if(!coll(piece,0,1))piece.y++;else lock();}
  }
  draw();raf=requestAnimationFrame(loop);
}

function start(m){
  mode=m;board=nb();score=0;lines=0;level=1;gameOver=false;paused=false;
  dropI=m==='ai'?400:1000;dropC=0;lastT=0;aiTimer=0;
  document.getElementById('sc').textContent=0;document.getElementById('ln').textContent=0;document.getElementById('lv').textContent=1;
  document.getElementById('autoBtn').className='gbtn'+(m==='ai'?' active':'');
  document.getElementById('playBtn').className='gbtn'+(m==='play'?' active':'');
  document.getElementById('ghint').innerHTML=m==='ai'?'<span class="ai-badge">AI playing</span> &nbsp;watch or click "play"':'← → move &nbsp;·&nbsp; ↑ rotate &nbsp;·&nbsp; ↓ drop';
  piece=rp();cancelAnimationFrame(raf);raf=requestAnimationFrame(ts=>{lastT=ts;loop(ts);});
}

document.getElementById('autoBtn').onclick=()=>start('ai');
document.getElementById('playBtn').onclick=()=>start('play');

document.addEventListener('keydown',e=>{
  if(mode!=='play'||gameOver||paused||!piece)return;
  if(e.key==='ArrowLeft'&&!coll(piece,-1,0))piece.x--;
  else if(e.key==='ArrowRight'&&!coll(piece,1,0))piece.x++;
  else if(e.key==='ArrowDown'){if(!coll(piece,0,1))piece.y++;else lock();}
  else if(e.key==='ArrowUp'){const r=rot(piece.sh);if(!coll(piece,0,0,r))piece.sh=r;}
  else if(e.key===' '){while(!coll(piece,0,1))piece.y++;lock();}
  if(['ArrowLeft','ArrowRight','ArrowDown','ArrowUp',' '].includes(e.key))e.preventDefault();
  draw();
});

start('ai');
</script>
