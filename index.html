<!DOCTYPE html><html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1">
<title>MTB FAST - Hint 10/5</title>
<style>
body{margin:0;font-family:system-ui;background:linear-gradient(135deg,#667eea,#764ba2,#f093fb);background-size:300% 300%;animation:bg 6s ease infinite;color:#fff;min-height:100vh}
@keyframes bg{0%{background-position:0% 50%}50%{background-position:100% 50%}100%{background-position:0% 50%}}
.h{position:sticky;top:0;background:rgba(0,0,0,.25);backdrop-filter:blur(12px);padding:12px;z-index:10;border-bottom:2px solid rgba(255,255,255,.2)}
.tabs{display:flex;gap:6px;overflow:auto;margin-top:8px}
.tab{padding:7px 15px;border-radius:20px;background:rgba(255,255,255,.25);font-weight:800;cursor:pointer;white-space:nowrap;font-size:12px;transition:.2s}
.tab.on{background:#fff;color:#764ba2;transform:scale(1.05)}
.stats{display:flex;gap:6px;margin-top:10px}
.s{flex:1;background:#fff;color:#222;border-radius:14px;padding:7px;text-align:center;box-shadow:0 4px 12px rgba(0,0,0,.15)}
.s b{display:block;font-size:19px}
.bar{height:12px;background:rgba(255,255,255,.3);border-radius:20px;margin-top:8px;overflow:hidden}
#fill{height:100%;width:100%;background:linear-gradient(90deg,#00ff9d,#00f2fe);transition:width 10s linear}
.card{margin:12px;background:rgba(255,255,255,.96);color:#222;border-radius:20px;padding:16px;box-shadow:0 8px 25px rgba(0,0,0,.2)}
.opt{padding:13px;border:2.5px solid #eee;border-radius:14px;margin:8px 0;cursor:pointer;font-weight:700;display:flex;gap:10px;align-items:center;transition:.2s;background:#fff}
.opt.ok{border-color:#00b894;background:linear-gradient(135deg,#d4ffe8,#a8ffce);color:#006b3f}
.opt.bad{border-color:#ff4757;background:linear-gradient(135deg,#ffdde0,#ffa8a8)}
.opt.dim{opacity:.35;pointer-events:none}
.badge{background:linear-gradient(135deg,#667eea,#764ba2);color:#fff;padding:5px 12px;border-radius:20px;font-size:11px;font-weight:800}
.hintBox{background:linear-gradient(135deg,#ffeaa7,#fdcb6e);border:2px dashed #e17055;border-radius:12px;padding:10px;margin:10px 0;display:none;color:#6c3000;font-weight:700;font-size:13px}
#pop{position:fixed;left:50%;top:50%;transform:translate(-50%,-50%) scale(0);padding:16px 32px;border-radius:30px;font-size:34px;font-weight:900;transition:.4s;z-index:99;color:#fff;text-align:center}
#pop.show{transform:translate(-50%,-50%) scale(1)}
.btn{flex:1;padding:12px;border-radius:14px;border:none;font-weight:800;cursor:pointer;font-size:13px}
.btn.n{background:linear-gradient(135deg,#667eea,#764ba2);color:#fff}
.btn.p{background:#fff;border:2px solid #ddd;color:#333}
.btn.hint{background:linear-gradient(135deg,#fdcb6e,#e17055);color:#fff}
</style></head><body>
<div class="h">
<div style="font-weight:900;font-size:18px">🎨 MTB SPECIALIST • HINT MODE • 10 SEC ⏱️</div>
<div style="font-size:11px;opacity:.9">M=Maths | P=Physics | B=Biology • +10 no hint / +5 with hint</div>
<div class="tabs" id="tabs"></div>
<div class="stats">
<div class="s"><b id="sc">0</b><span style="font-size:9px">SCORE</span></div>
<div class="s"><b id="co">0</b><span style="font-size:9px">CORRECT</span></div>
<div class="s"><b id="qt">1/50</b><span style="font-size:9px">Q</span></div>
<div class="s"><b id="tm">10.0</b><span style="font-size:9px">SEC</span></div>
</div>
<div class="bar"><div id="fill"></div></div>
</div>
<div style="max-width:720px;margin:auto">
<div class="card" id="qc">
<div style="display:flex;justify-content:space-between"><span class="badge" id="qn">Q 1</span><span id="sn" style="font-size:11px;font-weight:800;color:#764ba2"></span></div>
<div id="qt2" style="font-weight:800;margin:12px 0;font-size:17px"></div>
<div class="hintBox" id="hintBox"></div>
<div id="opts"></div>
<div style="display:flex;gap:6px;margin-top:12px">
<button class="btn p" id="prev">← Prev</button>
<button class="btn hint" id="hintBtn">💡 Hint (-5)</button>
<button class="btn n" id="next">Skip →</button>
</div>
<div style="font-size:10px;color:#888;margin-top:8px;text-align:center">💡 Hint = removes 2 wrong + shows clue • +5 pts | No hint = +10 pts</div>
</div>
<div class="card" id="res" style="display:none;text-align:center">
<h2>🎉 Set Complete!</h2>
<h1 id="fs" style="font-size:44px;background:linear-gradient(135deg,#667eea,#764ba2);-webkit-background-clip:text;-webkit-text-fill-color:transparent;margin:10px 0"></h1>
<p id="rs" style="font-size:13px;color:#555"></p>
<div style="display:flex;gap:8px;margin-top:12px"><button class="btn n" style="width:100%" onclick="restart()">🔄 Restart</button><button class="btn p" style="width:100%" onclick="nextSet()">➡️ Next Set</button></div>
</div>
</div>
<div id="pop"></div>
<script>
const DATA={M:[{q:"Which is irrational?",o:["1/2","0.25","√2","4"],a:2,h:"Root of non-perfect square is irrational"},{q:"Decimal of rational?",o:["Non-term non-recur","Terminating","Term or non-term recur","Non-recur"],a:2,h:"Rational decimals terminate or repeat"},{q:"Rational?",o:["√3","√5","√7","√9"],a:3,h:"√9=3 rational"},{q:"√144?",o:["10","11","12","14"],a:2,h:"12×12=144"},{q:"Between 2 and 3?",o:["√5","√2","√10","√16"],a:0,h:"√4=2, √9=3, so √5 between"},{q:"2^3×2^2?",o:["16","32","64","8"],a:1,h:"a^m×a^n=a^(m+n) =>2^5=32"},{q:"5^0?",o:["0","1","5","10"],a:1,h:"Any non-zero power 0=1"},{q:"2^-2?",o:["-4","4","1/4","-1/4"],a:2,h:"a^-n=1/a^n"},{q:"Terminating?",o:["1/3","2/7","3/8","5/6"],a:2,h:"Denom 2^n×5^m => terminating"},{q:"1/√5 rationalised?",o:["√5","5√5","√5/5","1/5"],a:2,h:"Multiply by √5"},{q:"Simplify √49+√16",o:["9","11","12","13"],a:1,h:"7+4=11"},{q:"Which irrational?",o:["√25","√36","√11","3/4"],a:2,h:"Perfect squares rational"},{q:"3^2×3^3?",o:["81","243","729","27"],a:1,h:"3^5=243"},{q:"2^5/2^2?",o:["4","6","8","16"],a:2,h:"2^(5-2)=8"},{q:"(√3)^2?",o:["3","6","9","√6"],a:0,h:"(√a)^2=a"},{q:"p(2) if p=2x²+3x-1",o:["9","11","13","15"],a:2,h:"2*4+6-1=13"},{q:"Degree 7x^4-3x^2+x-8",o:["2","3","4","7"],a:2,h:"Highest power degree"},{q:"Factorise x²-16",o:["(x-4)(x+4)","(x-8)(x+2)","(x-4)²","(x+16)(x-1)"],a:0,h:"a²-b²=(a-b)(a+b)"},{q:"Expand (x+2)²",o:["x²+4","x²+2x+4","x²+4x+4","x²-4x+4"],a:2,h:"(a+b)²=a²+2ab+b²"},{q:"If x=3, x²+2x+1",o:["10","12","16","18"],a:2,h:"9+6+1=16"},{q:"Solve x+7=15",o:["7","8","9","22"],a:1,h:"15-7=8"},{q:"Solve 3x=21",o:["6","7","8","9"],a:1,h:"21/3=7"},{q:"If x+y=10 x=4 y=",o:["4","5","6","14"],a:2,h:"10-4=6"},{q:"Point on y=2x?",o:["(2,4)","(2,3)","(1,3)","(3,5)"],a:0,h:"y double x"},{q:"Graph y=3 is",o:["Parallel X","Parallel Y","Through origin","Sloping"],a:0,h:"y=constant parallel X"},{q:"Point (0,5) lies on",o:["X-axis","Y-axis","I Quad","IV Quad"],a:1,h:"x=0 => Y-axis"},{q:"Third quad coords",o:["Both +","x+ y-","Both -","x- y+"],a:2,h:"III both negative"},{q:"Abscissa (-6,4)",o:["4","-6","6","-4"],a:1,h:"Abscissa=x"},{q:"Ordinate (3,-8)",o:["3","8","-3","-8"],a:3,h:"Ordinate=y"},{q:"Linear pair 125°, other?",o:["45","55","65","125"],a:1,h:"180-125=55"},{q:"Comple ratio 2:1 smaller?",o:["20","30","40","60"],a:1,h:"2x+x=90 =>30"},{q:"Exterior angle equals",o:["Sum 2 opp interior","Diff all","90","Sum all"],a:0,h:"Exterior=sum opposite interiors"},{q:"Triangle 35° 85° third?",o:["50","60","70","80"],a:1,h:"180-35-85=60"},{q:"5,12,13 triangle?",o:["Right","Equilateral","Obtuse","Equal sides"],a:0,h:"5²+12²=13²"},{q:"NOT congruence?",o:["SSS","SAS","ASA","AAA"],a:3,h:"AAA similarity only"},{q:"Parallelogram 70°, adjacent?",o:["70","90","110","180"],a:2,h:"Adjacent 180-70=110"},{q:"Rhombus diagonals at?",o:["30","45","60","90"],a:3,h:"Perpendicular"},{q:"Pentagon sum?",o:["360","450","540","720"],a:2,h:"(5-2)*180=540"},{q:"Equal chords subtend at",o:["Centre","Tangent","Diameter end","Everywhere"],a:0,h:"Equal chords equal angles at centre"},{q:"Diameter angle?",o:["45","60","90","180"],a:2,h:"Angle in semicircle 90°"},{q:"Semi-peri 8,10,12?",o:["12","15","20","30"],a:1,h:"(8+10+12)/2=15"},{q:"Area base12 height5?",o:["17","30","60","120"],a:1,h:"1/2*b*h=30"},{q:"Square side9 area?",o:["18","36","81","729"],a:2,h:"9²=81"},{q:"Rect 12x5 perimeter?",o:["17","34","60","120"],a:1,h:"2(l+b)=34"},{q:"Circle r7 area?",o:["44","88","154","308"],a:2,h:"22/7*49=154"},{q:"Cube side4 volume?",o:["16","32","48","64"],a:3,h:"4³=64"},{q:"Cuboid 5x4x3 vol?",o:["12","20","60","120"],a:2,h:"5*4*3=60"},{q:"CSA cylinder?",o:["π²h","2πrh","2πr²","πr²"],a:1,h:"2πrh"},{q:"Cone vol 1/3 cylinder?",o:["True","False","Only r=1","Only h=1"],a:0,h:"Cone=1/3 cylinder"},{q:"Mean 5,10,15,20,25?",o:["10","15","20","25"],a:1,h:"75/5=15"}],P:[{q:"SI unit distance?",o:["Kg","Metre","Sec","Newton"],a:1,h:"Metres"},{q:"Scalar?",o:["Displacement","Velocity","Speed","Acceleration"],a:2,h:"Scalar only magnitude - speed"},{q:"Vector?",o:["Distance","Speed","Time","Displacement"],a:3,h:"Vector has direction"},{q:"SI speed?",o:["m/s","km","m/s²","kg"],a:0,h:"Distance/time=m/s"},{q:"Speed formula?",o:["T/D","D/T","D×T","D+T"],a:1,h:"Speed=Distance/Time"},{q:"100m in 20s speed?",o:["2","5","10","20"],a:1,h:"100/20=5"},{q:"Displacement?",o:["Total path","Dist/sec","Change pos direction","Total time"],a:2,h:"Shortest path with direction"},{q:"Never negative?",o:["Displ","Vel","Distance","Acc"],a:2,h:"Distance always +"},{q:"SI acceleration?",o:["m/s","m/s²","km/h","Newton"],a:1,h:"m/s²"},{q:"Uniform motion?",o:["Equal dist equal time","Unequal","No dir","Only circle"],a:0,h:"Equal distances equal intervals"},{q:"120m in 10s?",o:["10","12","20","1200"],a:1,h:"120/10=12"},{q:"Vector?",o:["Distance","Speed","Displacement","Time"],a:2,h:"Displacement needs direction"},{q:"Slope vel-time?",o:["Dist","Speed","Acceleration","Displ"],a:2,h:"Slope v-t=acceleration"},{q:"0 to 20 in 4s a?",o:["4","5","10","80"],a:1,h:"(20-0)/4=5"},{q:"Constant vel a?",o:["Zero","One","Inc","Infinite"],a:0,h:"No change=>0"},{q:"SI force?",o:["Joule","Watt","Newton","Pascal"],a:2,h:"Newton"},{q:"Newton laws?",o:["Einstein","Newton","Galileo","Watt"],a:1,h:"Newton"},{q:"First law also?",o:["Acc","Inertia","Grav","Momentum"],a:1,h:"First=Inertia"},{q:"Inertia?",o:["Resist change motion","Light","Pull Earth","Rate vel"],a:0,h:"Resists change"},{q:"Inertia depends?",o:["Colour","Shape","Mass","Temp"],a:2,h:"More mass more inertia"},{q:"F=ma is?",o:["First","Second","Third","Grav"],a:1,h:"Second law"},{q:"Momentum?",o:["Mass×Vel","Mass/Vel","Force×Dist","Mass×Acc"],a:0,h:"p=mv"},{q:"SI momentum?",o:["kg m/s","kg/m","m/s²","N/m"],a:0,h:"kg*m/s"},{q:"Mass doubles momentum?",o:["Half","Doubles","Zero","Same"],a:1,h:"p∝m"},{q:"Action reaction?",o:["First","Second","Third","Conserv"],a:2,h:"Third law"},{q:"Bus stops forward?",o:["Inertia motion","Magnet","Gravity","Air"],a:0,h:"Inertia of motion"},{q:"Gun recoil?",o:["First","Third","Reflect","Grav"],a:1,h:"Third law"},{q:"10N on 2kg a?",o:["2","5","10","20"],a:1,h:"a=F/m=5"},{q:"SI mass?",o:["Newton","Kg","Joule","Watt"],a:1,h:"kg"},{q:"Weight?",o:["Kg","Metre","Newton","Sec"],a:2,h:"Weight=force=>Newton"},{q:"W=mg?",o:["W=m/g","W=mg","W=m+g","W=m-g"],a:1,h:"W=mg"},{q:"g value?",o:["4.9","8.9","9.8","98"],a:2,h:"9.8"},{q:"Weight Moon?",o:["1/6","Double","Same","6x"],a:0,h:"Moon 1/6 Earth"},{q:"Pressure?",o:["Force×Area","Force/Area","Area/Force","Mass×Vel"],a:1,h:"P=F/A"},{q:"SI pressure?",o:["Newton","Joule","Pascal","Watt"],a:2,h:"Pascal"},{q:"Work SI?",o:["Newton","Joule","Watt","Pascal"],a:1,h:"Joule"},{q:"Work= ?",o:["Force×Displ","Mass×Vel","Force/Time","Mass×Acc"],a:0,h:"W=F×s"},{q:"10N 5m work?",o:["2J","15J","50J","5J"],a:2,h:"50J"},{q:"No move work?",o:["10J","Zero","Neg","Infinite"],a:1,h:"No displacement 0 work"},{q:"Power unit?",o:["Joule","Newton","Watt","Metre"],a:2,h:"Watt"},{q:"100J 10s power?",o:["10W","100W","1000W","0.1W"],a:0,h:"100/10=10W"},{q:"KE formula?",o:["mv","mgh","1/2 mv²","ma"],a:2,h:"½mv²"},{q:"Speed doubles KE?",o:["2x","3x","4x","Half"],a:2,h:"v²=>4x"},{q:"PE mgh?",o:["mgh","mv","ma","F/t"],a:0,h:"mgh"},{q:"Sound produced by?",o:["Vibrating","Stationary","Light","Shadows"],a:0,h:"Vibrations"},{q:"Sound needs?",o:["Medium","Vacuum","Sunlight","Dark"],a:0,h:"Needs medium"},{q:"Cannot travel?",o:["Air","Water","Steel","Vacuum"],a:3,h:"Cannot in vacuum"},{q:"Sound in air?",o:["Transverse","Longitudinal","Light","Radio"],a:1,h:"Longitudinal"},{q:"SI frequency?",o:["Metre","Hertz","Joule","Watt"],a:1,h:"Hertz"},{q:"Audible?",o:["2-200","20-20k","200-200k","Above 200k"],a:1,h:"20Hz-20kHz"}],B:[{q:"Basic unit of life?",o:["Cell","Tissue","Organ","System"],a:0,h:"Cell is basic"},{q:"Cell discovered 1665?",o:["Hooke","Darwin","Mendel","Newton"],a:0,h:"Hooke"},{q:"Powerhouse?",o:["Nucleus","Mitochondria","Chloroplast","Ribosome"],a:1,h:"Mitochondria energy"},{q:"Photosynthesis in?",o:["Mito","Chloroplast","Nucleus","Ribosome"],a:1,h:"Chloroplast"},{q:"Cell wall in?",o:["Animal only","Plant","Both","None"],a:1,h:"Plant has wall"},{q:"Largest organelle?",o:["Mito","Nucleus","Ribosome","Chloro"],a:1,h:"Nucleus controls"},{q:"Ribosome function?",o:["Protein","Photo","Resp","Storage"],a:0,h:"Makes protein"},{q:"DNA in?",o:["Nucleus only","Mito+Nucleus","Ribosome","Wall"],a:1,h:"Nucleus & mitochondria"},{q:"Prokaryotic?",o:["Bacteria","Human","Plant","Animal"],a:0,h:"Bacteria no true nucleus"},{q:"Membrane is?",o:["Permeable","Semi-perm","Imperm","None"],a:1,h:"Selectively permeable"},{q:"Tissue?",o:["Group similar cells","Single cell","Organ","System"],a:0,h:"Group similar cells"},{q:"Meristematic in?",o:["Animals","Plants growing","Brain","Heart"],a:1,h:"Growing tips"},{q:"Xylem transports?",o:["Food","Water","Both","None"],a:1,h:"Water upwards"},{q:"Phloem transports?",o:["Water","Food","Air","Blood"],a:1,h:"Food"},{q:"Blood is?",o:["Connective","Epithelial","Muscular","Nervous"],a:0,h:"Connective"},{q:"Neuron unit?",o:["Muscular","Nervous","Digestive","Resp"],a:1,h:"Nervous system"},{q:"Cardiac muscle?",o:["Voluntary","Involuntary striated","Non-stri","None"],a:1,h:"Involuntary striated"},{q:"Epithelial covers?",o:["Body surfaces","Bones","Blood","None"],a:0,h:"Covers surfaces"},{q:"Malaria cause?",o:["Plasmodium","Bacteria","Virus","Fungus"],a:0,h:"Plasmodium"},{q:"TB cause?",o:["Mycobacterium","Virus","Fungus","Protozoa"],a:0,h:"Mycobacterium"},{q:"AIDS cause?",o:["HIV","Bacteria","Fungus","Protozoa"],a:0,h:"HIV"},{q:"Viral disease?",o:["Common cold","TB","Cholera","Typhoid"],a:0,h:"Cold viral"},{q:"Cholera cause?",o:["Vibrio","Virus","Fungus","Worm"],a:0,h:"Vibrio cholerae"},{q:"Vit C deficiency?",o:["Scurvy","Rickets","Night blind","Beriberi"],a:0,h:"C=>Scurvy"},{q:"Vit D deficiency?",o:["Rickets","Scurvy","Beriberi","Anemia"],a:0,h:"D=>Rickets"},{q:"Iron deficiency?",o:["Anemia","Scurvy","Rickets","Goitre"],a:0,h:"Iron=>hemoglobin"},{q:"Goitre due to?",o:["Iodine","Iron","Calcium","Vit C"],a:0,h:"Iodine thyroid"},{q:"Largest gland?",o:["Liver","Pancreas","Thyroid","Adrenal"],a:0,h:"Liver"},{q:"Insulin from?",o:["Pancreas","Liver","Kidney","Heart"],a:0,h:"Pancreas"},{q:"Respiration in?",o:["Mito","Chloro","Nucleus","Wall"],a:0,h:"Mitochondria"},{q:"ATP?",o:["Adenosine Triphosphate","Adenine","Both","None"],a:0,h:"Energy currency"},{q:"Chromosome human?",o:["46","23","44","48"],a:0,h:"46 (23 pairs)"},{q:"DNA full form?",o:["Deoxyribonucleic acid","Diri","Both","None"],a:0,h:"Deoxyribonucleic acid"},{q:"Mitosis?",o:["2 identical","4 cells","1 cell","3 cells"],a:0,h:"2 identical"},{q:"Heart chambers?",o:["2","3","4","1"],a:2,h:"4 chambers"},{q:"Kidney function?",o:["Filtration","Digestion","Resp","Circulation"],a:0,h:"Filters blood"},{q:"Largest organ?",o:["Heart","Skin","Brain","Liver"],a:1,h:"Skin"},{q:"Bones adult?",o:["206","300","150","100"],a:0,h:"206"},{q:"Universal donor?",o:["O","AB","A","B"],a:0,h:"O gives all"},{q:"Universal recipient?",o:["O","AB","A","B"],a:1,h:"AB receives all"},{q:"Vector malaria?",o:["Female Anopheles","Male","Housefly","Cockroach"],a:0,h:"Female Anopheles"},{q:"Decomposer?",o:["Bacteria fungi","Lion","Cow","Goat"],a:0,h:"Bacteria & fungi"},{q:"Ozone protects from?",o:["UV","Visible","IR","Radio"],a:0,h:"UV rays"},{q:"Greenhouse gas?",o:["CO2","O2","N2","H2"],a:0,h:"CO2 traps heat"},{q:"Biodegradable?",o:["Paper","Plastic","Glass","Metal"],a:0,h:"Paper decomposes"},{q:"Blood slightly?",o:["Alkaline","Acidic","Neutral","None"],a:0,h:"pH 7.4 alkaline"},{q:"RBC life?",o:["120 days","10 days","1 year","1 day"],a:0,h:"120 days"},{q:"Hemoglobin in?",o:["RBC","WBC","Platelet","Plasma"],a:0,h:"RBC"},{q:"Normal BP?",o:["120/80","200/100","80/120","150/90"],a:0,h:"120/80"},{q:"ECG for?",o:["Heart","Brain","Kidney","Liver"],a:0,h:"Heart electrical"}]};
let sub='M', set=0, cur=0, score=0, correct=0, ans=[], Q=[], tmr=null, left=10, hintUsed=false;
function init(){
 const tb=document.getElementById('tabs'); tb.innerHTML='';
 [['M','🔢 MATHS'],['P','⚙️ PHYSICS'],['B','🧬 BIOLOGY']].forEach(([k,label])=>{
  const d=document.createElement('div'); d.className='tab'+(k===sub?' on':''); d.textContent=label;
  d.onclick=()=>{sub=k; set=0; load();};
  tb.appendChild(d);
 });
}
function load(){
 Q=DATA[sub].slice(set*50,(set+1)*50); if(Q.length===0) Q=DATA[sub];
 cur=0; ans=Array(Q.length).fill(null);
 document.getElementById('res').style.display='none';
 document.getElementById('qc').style.display='block';
 render();
}
function pop(txt,col){
 const p=document.getElementById('pop'); p.textContent=txt; p.style.background=col||'#000'; p.classList.add('show');
 setTimeout(()=>p.classList.remove('show'),800);
}
function startTimer(){
 clearInterval(tmr); left=10;
 const f=document.getElementById('fill'); f.style.transition='none'; f.style.width='100%'; f.style.background='linear-gradient(90deg,#00ff9d,#00f2fe)';
 void f.offsetWidth; f.style.transition='width 10s linear'; f.style.width='0%';
 document.getElementById('tm').textContent='10.0';
 tmr=setInterval(()=>{
  left-=0.1; document.getElementById('tm').textContent=left.toFixed(1);
  if(left<=3) f.style.background='linear-gradient(90deg,#ff4757,#ff6b81)';
  else if(left<=6) f.style.background='linear-gradient(90deg,#fdcb6e,#e17055)';
  if(left<=0){clearInterval(tmr); if(ans[cur]===null){pop('⏰ Time! 0','#ff4757');} nextQ();}
 },100);
}
function render(){
 const q=Q[cur]; hintUsed=false;
 document.getElementById('qn').textContent='Q '+(set*50+cur+1);
 document.getElementById('sn').textContent=sub+' • Set '+(set+1)+(hintUsed?' • Hint':' • No Hint');
 document.getElementById('qt2').textContent=q.q;
 document.getElementById('hintBox').style.display='none';
 document.getElementById('opts').innerHTML='';
 q.o.forEach((o,i)=>{
  const d=document.createElement('div'); d.className='opt'; d.id='opt'+i;
  if(ans[cur]!==null){ if(i===q.a) d.classList.add('ok'); else if(i===ans[cur]) d.classList.add('bad'); }
  d.innerHTML='<div style="width:28px;height:28px;border-radius:50%;background:#764ba2;color:#fff;display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:800">'+String.fromCharCode(65+i)+'</div><div>'+o+'</div>';
  d.onclick=()=>{
   if(ans[cur]!==null) return;
   ans[cur]=i; clearInterval(tmr);
   if(i===q.a){
     if(hintUsed){score+=5; pop('+5 💡','#fdcb6e');}
     else {score+=10; pop('+10 🎉','#00b894');}
     correct++;
   } else {pop('0 😢','#ff4757');}
   update(); 
   q.o.forEach((_,j)=>{const el=document.getElementById('opt'+j); if(el){if(j===q.a) el.classList.add('ok'); else if(j===i) el.classList.add('bad');}});
   setTimeout(nextQ,900);
  };
  document.getElementById('opts').appendChild(d);
 });
 update(); startTimer();
}
function update(){
 document.getElementById('sc').textContent=score;
 document.getElementById('co').textContent=correct;
 document.getElementById('qt').textContent=(cur+1)+'/'+Q.length;
}
function nextQ(){ if(cur<Q.length-1){cur++; render();} else showRes(); }
document.getElementById('prev').onclick=()=>{if(cur>0){clearInterval(tmr); cur--; render();}};
document.getElementById('next').onclick=()=>{clearInterval(tmr); if(ans[cur]===null) pop('Skip 0','#636e72'); nextQ();};
document.getElementById('hintBtn').onclick=()=>{
 if(ans[cur]!==null || hintUsed) return;
 hintUsed=true;
 const q=Q[cur];
 document.getElementById('hintBox').style.display='block';
 document.getElementById('hintBox').textContent='💡 Hint: '+q.h;
 document.getElementById('sn').textContent=sub+' • Set '+(set+1)+' • Hint Used (5 pts max)';
 pop('💡 Hint! Now +5 max','#fdcb6e');
 let removed=0;
 q.o.forEach((_,i)=>{
  const d=document.getElementById('opt'+i);
  if(i!==q.a && removed<2){ d.classList.add('dim'); removed++; }
 });
};
function showRes(){
 clearInterval(tmr);
 document.getElementById('qc').style.display='none';
 document.getElementById('res').style.display='block';
 document.getElementById('fs').textContent=score+' pts';
 document.getElementById('rs').textContent='Correct '+correct+'/'+Q.length+' | Max '+(Q.length*10)+' pts | +10 no hint / +5 with hint | No negative!';
}
function restart(){load();}
function nextSet(){ if(set<2){set++;} else {set=0; sub=sub==='M'?'P':sub==='P'?'B':'M';} load(); init(); }
init(); load();
</script></body></html>
