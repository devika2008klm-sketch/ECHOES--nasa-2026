.# ECHOES--nasa-2026<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ECHOES - Abandoned but not Forgotten</title>
<link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@600;700&family=Space+Grotesk:wght@400;700&display=swap" rel="stylesheet">
<style>*{margin:0;padding:0;box-sizing:border-box}body{font-family:'Space Grotesk',sans-serif;background:#0a0e27;color:white}
.hero{min-height:85vh;background:radial-gradient(ellipse at 20% 20%,#1a1f4d 0%,#0a0e27 50%,#000 100%);display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:40px 20px}
.hero h1{font-family:'Fredoka',sans-serif;font-size:80px;background:linear-gradient(135deg,#00ffff,#a78bfa,#f472b6);-webkit-background-clip:text;-webkit-text-fill-color:transparent;letter-spacing:4px}
.sub{font-size:22px;color:#a78bfa;font-weight:600;margin:10px 0}.tag{max-width:700px;color:#cbd5e1;line-height:1.6;margin:15px 0}
.btn{padding:14px 28px;border-radius:30px;font-weight:700;font-size:16px;border:none;text-decoration:none;display:inline-block;margin:5px}
.p{background:linear-gradient(135deg,#00ffff,#a78bfa);color:#0a0e27}.g{background:transparent;border:2px solid #a78bfa;color:#a78bfa}
.section{padding:50px 20px;max-width:1200px;margin:0 auto}.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:20px}
.card{background:linear-gradient(135deg,#1a1f3d,#141830);border-radius:24px;padding:22px;cursor:pointer;transition:0.3s;border:2px solid transparent}
.card:hover{transform:translateY(-6px);border-color:#a78bfa;box-shadow:0 20px 40px rgba(167,139,250,0.2)}
.emoji{font-size:60px;display:block;text-align:center;margin-bottom:12px}.quote{font-style:italic;color:#fbbf24;font-size:12px;background:rgba(251,191,36,0.1);padding:6px 10px;border-radius:12px;display:inline-block;margin:8px 0}
.story{color:#cbd5e1;font-size:14px;line-height:1.5}.sci{background:linear-gradient(135deg,rgba(0,255,255,0.15),rgba(167,139,250,0.15));border-radius:10px;padding:8px;font-size:11px;color:#a78bfa;margin-top:8px}
.modal{display:none;position:fixed;inset:0;background:rgba(0,0,0,0.85);z-index:100;align-items:center;justify-content:center;padding:20px}
.modal.active{display:flex}.box{background:#141830;border:2px solid #a78bfa;border-radius:24px;max-width:600px;width:100%;padding:28px;position:relative}
.close{position:absolute;top:12px;right:18px;font-size:28px;cursor:pointer;color:#94a3b8}
.footer{text-align:center;padding:30px;color:#64748b;border-top:1px solid #1a1f3d;margin-top:30px}
</style></head><body>
<div class="hero"><h1>ECHOES</h1><div class="sub">Abandoned but not Forgotten</div>
<p class="tag">An interactive storybook where NASA's discarded Moon & Mars hardware become cute Pixar-like characters teaching science to school kids.</p>
<div><a href="#heroes" class="btn p">🚀 Meet Heroes</a><a href="https://github.com" class="btn g">GitHub Code</a></div>
<p style="margin-top:18px;color:#64748b;font-size:12px">Team Innovative Minds | Bangalore | NASA Space Apps 2026</p></div>
<div class="section" id="heroes"><h2 style="font-family:Fredoka;text-align:center;font-size:36px;margin-bottom:10px">🌟 Meet 8 Forgotten Heroes</h2>
<div class="grid">
<div class="card" onclick="openM('oppy')"><span class="emoji">🔴</span><h3>Oppy - Opportunity Rover</h3><div class="quote">"My battery is low and it's getting dark"</div><div class="story">I lived on Mars for 15 years but was only planned for 90 days. I traveled 45km finding proof Mars had water!</div><div class="sci">🔬 Science: Hematite = water + Hot springs = life potential</div></div>
<div class="card" onclick="openM('mirror')"><span class="emoji">🪞</span><h3>Apollo 11 Mirror</h3><div class="quote">"I'm still doing science after 57 years!"</div><div class="story">Astronauts left me on Moon in 1969. Scientists shoot lasers at me daily to measure Moon distance!</div><div class="sci">🔬 Science: Moon moving 3.8cm/year away - Still working!</div></div>
<div class="card" onclick="openM('golf')"><span class="emoji">⛳️</span><h3>Apollo 14 Golf Balls</h3><div class="quote">"Miles and miles and miles!"</div><div class="story">Alan Shepard smuggled golf club to Moon and hit 2 balls for miles! In low gravity, everything flies far.</div><div class="sci">🔬 Science: Moon gravity 1/6th Earth - Fun physics demo</div></div>
<div class="card" onclick="openM('ingenuity')"><span class="emoji">🚁</span><h3>Ingenuity Helicopter</h3><div class="quote">"Planned 5 flights, flew 72!"</div><div class="story">First aircraft to fly on another planet! NASA thought I'd fly 5 times, I flew 72 times on Mars thin air.</div><div class="sci">🔬 Science: Mars air 1% of Earth - Future air taxis</div></div>
<div class="card" onclick="openM('rover')"><span class="emoji">🚙</span><h3>Apollo 17 Lunar Rover</h3><div class="quote">"35km odometer on Moon!"</div><div class="story">I drove astronauts 35km on Moon, found orange soil which is volcanic glass - Moon was once volcano!</div><div class="sci">🔬 Science: Orange soil = fire fountain volcano</div></div>
<div class="card" onclick="openM('voyager')"><span class="emoji">📡</span><h3>Voyager 1 Golden Record</h3><div class="quote">"I am 24 BILLION km away"</div><div class="story">Farthest human object! I carry Golden Record with music and greetings for aliens - Now in interstellar space.</div><div class="sci">🔬 Science: Interstellar space = beyond Solar System</div></div>
<div class="card" onclick="openM('trash')"><span class="emoji">💩</span><h3>96 Bags of Trash</h3><div class="quote">"We left poop to bring Moon rocks!"</div><div class="story">Astronauts left 96 bags of trash including poop to make room for 382kg Moon rocks. Future biology experiment!</div><div class="sci">🔬 Science: Tradeoff - Rocks > Trash + Bacteria survive?</div></div>
<div class="card" onclick="openM('spirit')"><span class="emoji">🌬️</span><h3>Spirit Rover</h3><div class="quote">"Stuck but never gave up"</div><div class="story">Got stuck in Martian sand trap but kept doing science for 6 years as stationary lab - Found hot springs!</div><div class="sci">🔬 Science: Hot springs = life could have existed</div></div>
</div></div>
<div class="footer"><h3 style="color:white;margin-bottom:8px">They are abandoned, but with ECHOES, they are NOT forgotten.</h3><p>Team Innovative Minds - Bangalore - NASA Space Apps 2026</p></div>
<div id="modal" class="modal" onclick="closeM()"><div class="box" onclick="event.stopPropagation()"><span class="close" onclick="closeM()">×</span><div id="modalContent"></div></div></div>
<script>
const d={oppy:`<h2>🔴 Oppy</h2><p>Hi, I'm Oppy! I landed on Mars in 2004 for 90 days, but lived 15 YEARS! Found proof Mars had water. Last message: My battery is low and it's getting dark.</p>`,mirror:`<h2>🪞 Mirror</h2><p>Astronauts left me 1969. 100 small mirrors bounce laser light back to Earth. We know Moon moving 3.8cm away each year. Still works!</p>`,golf:`<h2>⛳️ Golf Balls</h2><p>I'm golf ball on Moon! Alan hit us. On Earth golf goes 300m, on Moon MILES because gravity 1/6th and no air! Still near Fra Mauro.</p>`,ingenuity:`<h2>🚁 Ingenuity</h2><p>First aircraft on another planet! Mars air 1% Earth but I flew 72 flights over 3 years. Now resting forever.</p>`,rover:`<h2>🚙 Lunar Rover</h2><p>Moon buggy Apollo 17 1972. Drove 35km, found orange soil which is volcanic glass - Moon was volcanic! Broken fender fixed with duct tape!</p>`,voyager:`<h2>📡 Voyager 1</h2><p>Farthest human object - 24B km! Carry Golden Record with baby crying, whale songs, Hindi greeting. Now beyond Solar System!</p>`,trash:`<h2>💩 96 Bags Trash</h2><p>Most famous! Apollo left 96 bags trash including poop to bring 382kg Moon rocks. Like leaving old books to bring new! After 50 years, does bacteria still alive?</p>`,spirit:`<h2>🌬️ Spirit</h2><p>Hi, Spirit! 2009 stuck in sand trap - like car in mud! Became stationary lab 6 years, found proof of hot springs - Mars could have had life!</p>`};
function openM(id){document.getElementById('modalContent').innerHTML=d[id];document.getElementById('modal').classList.add('active')}
function closeM(){document.getElementById('modal').classList.remove('active')}
</script></body></html>
