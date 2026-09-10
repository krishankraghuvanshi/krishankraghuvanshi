<header> <h1 align="center"><img src="https://readme-typing-svg.demolab.com?font=Monaspace+Krypton&size=15&duration=3500&color=9370DB&center=true&vCenter=true&lines=Hi+I+am+Krishank;My+interests+are+in....;Software+Development+%f0%9f%92%bb;Data+Structures+and+Algorithms+%f0%9f%93%b0;Competitive+Programming+%f0%9f%93%b0;and+Machine+Learning+%f0%9f%92%a0+" /></h1> </header>

## Languages & Technology :computer:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)  ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)  ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)  ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)  ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)  ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)    ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)  ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)  ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)  ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)  ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)   ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![LangChain](https://img.shields.io/badge/langchain-%231C3C3C.svg?style=for-the-badge&logo=langchain&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) 

![](./profile-3d-contrib/profile-night-green.svg)

## Leetcode Statistics :chart_with_upwards_trend:

![Leetcode Stats](https://leetcard.jacoblin.cool/kri5H4nkr49Hu1c?theme=light)

## Contact Me 📲

<p align="left">
    <a href="https://www.linkedin.com/in/krishankraghuvanshi/" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40"/></a>
</p>

![](https://krishankraghuvanshi.vercel.app/)


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Walking Human Simulation</title>
<style>
  :root{
    --bg1:#0f1b2d;
    --bg2:#1c3050;
    --figure:#e8eef7;
    --joint:#7fd1ff;
    --accent:#ff8a5b;
  }
  html,body{
    margin:0; height:100%;
    background: linear-gradient(180deg, var(--bg1), var(--bg2));
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    color:#dfe8f5;
    overflow:hidden;
  }
  #ui{
    position:fixed; top:16px; left:16px; z-index:10;
    background:rgba(10,16,28,0.55);
    backdrop-filter: blur(6px);
    padding:14px 16px; border-radius:12px;
    border:1px solid rgba(255,255,255,0.08);
    max-width: 260px;
  }
  #ui h1{ font-size:15px; margin:0 0 8px; letter-spacing:0.3px; }
  #ui label{ display:block; font-size:12px; margin-top:10px; opacity:0.85; }
  #ui input[type=range]{ width:100%; }
  #ui .row{ display:flex; gap:8px; margin-top:10px; }
  #ui button{
    flex:1; background:var(--accent); border:none; color:#20120a;
    font-weight:600; padding:7px 0; border-radius:8px; cursor:pointer;
    font-size:12px;
  }
  #ui button.secondary{ background:transparent; color:#dfe8f5; border:1px solid rgba(255,255,255,0.25); }
  #stage{ width:100vw; height:100vh; display:block; }
  #footer{
    position:fixed; bottom:10px; right:14px; font-size:11px; opacity:0.4;
  }
</style>
</head>
<body>

<div id="ui">
  <h1>🚶 Walking Human Simulation</h1>
  <label>Speed (steps/sec): <span id="speedVal">1.0</span></label>
  <input id="speed" type="range" min="0.2" max="3" step="0.1" value="1.0">

  <label>Stride length: <span id="strideVal">1.0</span></label>
  <input id="stride" type="range" min="0.5" max="1.6" step="0.05" value="1.0">

  <label>Height (px): <span id="heightVal">220</span></label>
  <input id="height" type="range" min="120" max="320" step="5" value="220">

  <div class="row">
    <button id="pauseBtn">Pause</button>
    <button id="resetBtn" class="secondary">Reset</button>
  </div>
</div>

<canvas id="stage"></canvas>
<div id="footer">procedural walk-cycle · foot swing + lift, character moves across screen</div>

<script>
const canvas = document.getElementById('stage');
const ctx = canvas.getContext('2d');
function resize(){ canvas.width = innerWidth; canvas.height = innerHeight; }
resize();
window.addEventListener('resize', resize);

// ---- controls ----
const speedInput  = document.getElementById('speed');
const strideInput = document.getElementById('stride');
const heightInput = document.getElementById('height');
const speedVal  = document.getElementById('speedVal');
const strideVal = document.getElementById('strideVal');
const heightVal = document.getElementById('heightVal');
let paused = false;

speedInput.oninput  = () => speedVal.textContent  = (+speedInput.value).toFixed(1);
strideInput.oninput = () => strideVal.textContent = (+strideInput.value).toFixed(2);
heightInput.oninput = () => heightVal.textContent = heightInput.value;

document.getElementById('pauseBtn').onclick = (e) => {
  paused = !paused;
  e.target.textContent = paused ? 'Resume' : 'Pause';
};
document.getElementById('resetBtn').onclick = () => {
  speedInput.value = 1.0; strideInput.value = 1.0; heightInput.value = 220;
  speedInput.oninput(); strideInput.oninput(); heightInput.oninput();
  charX = -100;
  t = 0;
};

// ---- state ----
let t = 0;          // gait phase accumulator (radians)
let charX = -100;   // character's horizontal position, walks left -> right across screen

function joint(x,y,r,color){
  ctx.save();
  ctx.fillStyle = color || '#7fd1ff';
  ctx.beginPath();
  ctx.arc(x,y,r,0,Math.PI*2);
  ctx.fill();
  ctx.restore();
}

function segment(x1,y1,x2,y2,width,color){
  ctx.save();
  ctx.strokeStyle = color;
  ctx.lineWidth = width;
  ctx.lineCap = 'round';
  ctx.beginPath();
  ctx.moveTo(x1,y1);
  ctx.lineTo(x2,y2);
  ctx.stroke();
  ctx.restore();
}

function drawGround(groundY){
  ctx.save();
  ctx.fillStyle = '#22314a';
  ctx.fillRect(0, groundY, canvas.width, canvas.height - groundY);
  ctx.strokeStyle = 'rgba(255,255,255,0.10)';
  ctx.lineWidth = 2;
  ctx.beginPath();
  ctx.moveTo(0, groundY);
  ctx.lineTo(canvas.width, groundY);
  ctx.stroke();
  // tick marks for a sense of scale (static ground, character moves over it)
  ctx.strokeStyle = 'rgba(255,255,255,0.06)';
  ctx.lineWidth = 1;
  for(let x = 0; x < canvas.width; x += 50){
    ctx.beginPath();
    ctx.moveTo(x, groundY);
    ctx.lineTo(x, groundY + 10);
    ctx.stroke();
  }
  ctx.restore();
}

// One leg's foot trajectory over a full 2*PI gait cycle:
//  - swing phase  (0 .. PI): foot lifts off ground, arcs forward. offset goes -stride -> +stride, lift is a hump (max mid-swing).
//  - stance phase (PI .. 2PI): foot is planted, body moves forward over it, offset eases back from +stride -> -stride, lift = 0.
function footOffset(phase, strideRange){
  return -Math.cos(phase) * strideRange;
}
function footLift(phase, liftMax){
  const s = Math.sin(phase);
  return s > 0 ? s * liftMax : 0; // only lifts during the 0..PI half (swing)
}

function drawLeg(hipX, hipY, phase, scale, strideAmt){
  const thighLen = 46 * scale;
  const shinLen  = 44 * scale;
  const legLen = thighLen + shinLen;
  const strideRange = 34 * scale * strideAmt;
  const liftMax = 22 * scale;

  const offset = footOffset(phase, strideRange);
  const lift   = footLift(phase, liftMax);

  const footX = hipX + offset;
  const footY = hipY + legLen - lift;

  // knee: roughly midway horizontally, bends upward (less far down) proportional to lift,
  // and forward proportional to half the offset -- gives a natural bent-knee arc during swing.
  const kneeX = hipX + offset * 0.5;
  const kneeY = hipY + thighLen - lift * 0.55;

  segment(hipX, hipY, kneeX, kneeY, 10*scale, '#e8eef7');
  segment(kneeX, kneeY, footX, footY, 8*scale, '#e8eef7');
  joint(hipX, hipY, 5.5*scale, '#7fd1ff');
  joint(kneeX, kneeY, 5*scale, '#7fd1ff');

  // foot
  segment(footX, footY, footX + Math.sign(offset||1)*10*scale, footY + 2*scale, 7*scale, '#ff8a5b');

  return { footY, kneeY };
}

function drawArm(shX, shY, phase, scale, strideAmt){
  const upperLen = 36 * scale;
  const foreLen  = 34 * scale;
  const swingRange = 26 * scale * strideAmt;
  const swing = Math.sin(phase) * swingRange;

  const elbowX = shX + swing * 0.6;
  const elbowY = shY + upperLen;
  const handX  = shX + swing;
  const handY  = shY + upperLen + foreLen;

  segment(shX, shY, elbowX, elbowY, 8*scale, '#cfe0f5');
  segment(elbowX, elbowY, handX, handY, 6.5*scale, '#cfe0f5');
  joint(shX, shY, 4.5*scale, '#7fd1ff');
  joint(elbowX, elbowY, 4*scale, '#7fd1ff');
}

function drawHuman(cx, hipY, scale, phase, strideAmt){
  const torsoLen = 70 * scale;
  const headR = 15 * scale;

  const rightPhase = phase;
  const leftPhase  = phase + Math.PI;

  // slight body bob: two small bounces per full stride cycle (down when weight-bearing)
  const bob = Math.abs(Math.sin(phase)) * 5 * scale;
  const hipYb = hipY - bob;
  const shoulderY = hipYb - torsoLen;

  // simple depth ordering: whichever leg is currently planted/back draws first
  const backSide = Math.sin(phase) > 0 ? 'L' : 'R';

  const legs = [
    { side:'L', hipX: cx - 8*scale, shX: cx - 15*scale, phase: leftPhase },
    { side:'R', hipX: cx + 8*scale, shX: cx + 15*scale, phase: rightPhase },
  ];
  const ordered = backSide === 'L' ? legs : [legs[1], legs[0]];

  drawLeg(ordered[0].hipX, hipYb, ordered[0].phase, scale, strideAmt);
  drawArm(ordered[0].shX, shoulderY, ordered[0].phase + Math.PI, scale, strideAmt);

  // torso + head
  segment(cx, hipYb, cx, shoulderY, 15*scale, '#f2f6fc');
  ctx.save();
  ctx.fillStyle = '#f2f6fc';
  ctx.beginPath();
  ctx.arc(cx, shoulderY - headR - 3*scale, headR, 0, Math.PI*2);
  ctx.fill();
  ctx.restore();

  drawLeg(ordered[1].hipX, hipYb, ordered[1].phase, scale, strideAmt);
  drawArm(ordered[1].shX, shoulderY, ordered[1].phase + Math.PI, scale, strideAmt);
}

function frame(){
  const speed = +speedInput.value;
  const strideAmt = +strideInput.value;
  const scale = (+heightInput.value) / 220;

  if(!paused){
    t += 0.06 * speed;                      // gait phase speed
    charX += 1.7 * speed * strideAmt * scale; // walking speed across screen
    if(charX > canvas.width + 60) charX = -60;
  }

  ctx.clearRect(0,0,canvas.width, canvas.height);
  const groundY = canvas.height * 0.72;
  drawGround(groundY);

  const hipY = groundY - 92*scale;
  drawHuman(charX, hipY, scale, t, strideAmt);

  requestAnimationFrame(frame);
}
frame();
</script>
</body>
</html>



