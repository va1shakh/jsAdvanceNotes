<div align="center">

<h1>⚡ JS Advanced Notes for Dummies</h1>

<p>a modern, minimal, beginner-friendly guide to mastering advanced JavaScript concepts with clarity and simplicity.</p>
<a href="https://va1shakh.github.io/jsAdvanceNotes/"
   class="gold-btn">
   🚀 Live Demo
</a>

<style>
body {
  background:#0b0b0f;
  display:flex;
  justify-content:center;
  align-items:center;
  height:100vh;
}

/* BUTTON */
.gold-btn {
  position:relative;
  display:inline-block;
  padding:14px 28px;
  color:#f5d36a;
  font-weight:600;
  text-decoration:none;
  border-radius:12px;
  background:rgba(255,255,255,0.05);
  border:1px solid rgba(245,211,106,0.3);
  backdrop-filter:blur(10px);
  overflow:hidden;
  transition:0.3s;
  font-family:Arial;
}

.gold-btn:hover {
  transform:scale(1.05);
  box-shadow:0 0 25px rgba(245,211,106,0.3);
}

/* GOLD PARTICLES */
.gold-btn::before,
.gold-btn::after {
  content:"";
  position:absolute;
  width:200%;
  height:200%;
  top:-50%;
  left:-50%;
  background:
    radial-gradient(circle, rgba(245,211,106,0.8) 2px, transparent 3px),
    radial-gradient(circle, rgba(245,211,106,0.4) 1px, transparent 2px);
  background-size:40px 40px, 60px 60px;
  animation: sparkle 6s linear infinite;
  opacity:0.25;
}

.gold-btn::after {
  animation-direction:reverse;
  opacity:0.15;
}

@keyframes sparkle {
  0% { transform:translate(0,0); }
  100% { transform:translate(40px,40px); }
}
</style>

</div>
