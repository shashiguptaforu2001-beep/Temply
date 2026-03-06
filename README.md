# Temply
49 psychology hook line to start conversation 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>49 Psychology Hook Lines</title>
<style>
body{font-family:Arial;margin:0;background:#f5f5f5;color:#222;-webkit-font-smoothing:antialiased}
header{background:#111;color:#fff;padding:28px 16px;text-align:center;position:relative}
h1{font-size:26px;line-height:1.25;margin:10px 0}
.sub{font-size:15px;opacity:.9;margin-bottom:10px}
.price{font-size:24px;margin:12px 0;font-weight:bold}

.badge{position:absolute;top:10px;right:10px;background:#ff3b3b;color:#fff;padding:6px 10px;border-radius:6px;font-size:12px;font-weight:bold;animation:pulse 1.5s infinite}

.btn{background:#ff3b3b;color:#fff;padding:16px 20px;text-decoration:none;border-radius:10px;font-size:17px;display:block;max-width:320px;margin:14px auto;font-weight:bold;text-align:center;animation:pulse 1.5s infinite}

@keyframes pulse{0%{transform:scale(1)}50%{transform:scale(1.05)}100%{transform:scale(1)}}

.section{padding:20px 14px;max-width:820px;margin:auto}
.card{background:#fff;padding:18px;margin:14px 0;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,.08)}
.card h2{font-size:20px;margin-top:0}

.sticky{position:fixed;bottom:0;left:0;width:100%;background:#111;padding:10px;z-index:999}
.sticky a{display:block;background:#ff3b3b;color:#fff;padding:16px;border-radius:8px;font-size:17px;font-weight:bold;text-align:center;max-width:420px;margin:auto}

.counter{font-weight:bold;color:#ff3b3b}
.blur{filter:blur(6px)}
.timer{font-size:22px;color:#ff3b3b;font-weight:bold;text-align:center}

/* cover image */
.mockup{width:100%;max-width:260px;margin:18px auto 10px auto;display:block;border-radius:14px;box-shadow:0 12px 30px rgba(0,0,0,.35)}

/* mobile stats */
header p{font-size:14px;margin:6px 0}

.progressBox{background:#ddd;border-radius:10px;overflow:hidden;margin-top:10px}
.progress{height:12px;background:#ff3b3b;width:82%}

.chat{background:#f1f1f1;border-radius:10px;padding:12px;max-width:320px;margin:auto}
.msg{padding:7px 10px;border-radius:15px;margin:6px 0;display:inline-block;font-size:14px}
.me{background:#d1ffd6}
.her{background:#fff}

#purchaseBox{position:fixed;bottom:90px;left:10px;background:#fff;padding:8px 12px;border-radius:8px;box-shadow:0 6px 14px rgba(0,0,0,.2);font-size:13px;display:none;z-index:999}

.footer{background:#111;color:#fff;padding:30px 18px;margin-top:30px}
.footer h3{margin-top:0;font-size:18px}
.footer p,.footer li{font-size:13px;line-height:1.6}

/* desktop improvement */
@media (min-width:768px){
h1{font-size:34px}
.sub{font-size:18px}
.price{font-size:28px}
.mockup{max-width:340px}
.section{padding:40px 20px}
.card{padding:24px}
}

</style>

<script>

// countdown timer
let time=600
function countdown(){
 let m=Math.floor(time/60)
 let s=time%60
 document.getElementById("timer").innerHTML=m+":"+(s<10?"0":"")+s
 time--
 if(time>=0){setTimeout(countdown,1000)}
}

// visitors counter
function visitors(){
 let v=Math.floor(Math.random()*40)+10
 document.getElementById("visitors").innerText=v
}
setInterval(visitors,3000)

// unlocked counter
let unlocked=143
function increaseUnlocked(){
 unlocked+=Math.floor(Math.random()*3)
 document.getElementById("unlocked").innerText=unlocked
}
setInterval(increaseUnlocked,5000)

// downloads
let downloads=321
function increaseDownloads(){
 downloads+=Math.floor(Math.random()*2)
 document.getElementById("downloads").innerText=downloads
}
setInterval(increaseDownloads,4000)

// stock counter
let stock=87
function reduceStock(){
 stock--
 if(stock<12){stock=12}
 document.getElementById("stock").innerText=stock
}
setInterval(reduceStock,8000)

// testimonials
const testimonials=[
"⭐⭐⭐⭐⭐ First message bheja aur reply aaya – Rohit",
"⭐⭐⭐⭐⭐ Instagram DM kaafi easy ho gaya – Aman",
"⭐⭐⭐⭐⭐ Girls actually reply kar rahi hain – Karan",
"⭐⭐⭐⭐⭐ Simple but powerful hooks – Vikram"
]
let tIndex=0
function rotateTestimonials(){
 document.getElementById("testimonialBox").innerText=testimonials[tIndex]
 tIndex++
 if(tIndex>=testimonials.length){tIndex=0}
}
setInterval(rotateTestimonials,4000)

// exit popup
function showExit(){document.getElementById("exitPopup").style.display="flex"}
function closeExit(){document.getElementById("exitPopup").style.display="none"}
document.addEventListener("mouseout",function(e){if(e.clientY<5){showExit()}})

// live purchase popup
function livePurchase(){
 const names=["Rahul","Aman","Karan","Vikram","Arjun","Rohit"]
 const cities=["Delhi","Mumbai","Pune","Jaipur","Lucknow"]
 let name=names[Math.floor(Math.random()*names.length)]
 let city=cities[Math.floor(Math.random()*cities.length)]
 let box=document.getElementById("purchaseBox")
 box.innerHTML="🔥 "+name+" from "+city+" just purchased"
 box.style.display="block"
 setTimeout(()=>{box.style.display="none"},4000)
}
setInterval(livePurchase,9000)

// last 24h purchases counter
let purchases24=57
function increasePurchases(){
 purchases24+=Math.floor(Math.random()*2)
 document.getElementById("purchases24").innerText=purchases24
}
setInterval(increasePurchases,7000)

window.onload=function(){countdown();}


</script>
</head>

<body>

<header>
<div class="badge">🔥 80% OFF</div>

<h1>49 Psychology Hook Lines That Make Girls Reply</h1>
<p class="sub">Copy‑paste conversation starters that spark curiosity instantly</p>

<img class="mockup" src="https://i.postimg.cc/SY487m9Q/49-hooks-1-2025-08-11-05-33-22-2025-12-11-06-56-3.webp" alt="49 Hooks Cover">

<div class="price">Today Only ₹99</div>
<a class="btn" href="#buy">Download Now</a>

<p>👁 <span id="visitors" class="counter">23</span> people viewing</p>
<p>📈 <span id="unlocked" class="counter">143</span> unlocked today</p>
<p>⬇ <span id="downloads" class="counter">321</span> downloads today</p>
<p>⚠ Only <span id="stock" class="counter">87</span> copies left</p>

<div class="progressBox"><div class="progress"></div></div>
<p>82% Stock Sold</p>
<p>🔥 <span id="purchases24" class="counter">57</span> people bought this in the last 24 hours</p>

<div style="margin-top:20px;font-size:13px;opacity:.8">⬇ Scroll to see how it works</div>
<div style="font-size:28px;animation:pulse 1.5s infinite">⬇</div>

</header>

<div class="section">

<div class="card">
<h2>📱 Real DM Conversation Example</h2>
<div class="chat">
<div class="msg me">Ek random question puchu… sach sach answer dena 😄</div>
<div class="msg her">Haha okay pucho</div>
<div class="msg me">Tum introvert ho ya selective?</div>
<div class="msg her">Selective actually 😂</div>
<div class="msg me">Mujhe laga tha tum thodi mysterious ho</div>
<div class="msg her">Haha maybe thodi 😅</div>
</div>
<p style="text-align:center;font-size:13px;margin-top:10px;opacity:.8">These psychology hooks trigger curiosity so girls naturally reply.</p>
</div>
</div>

<div class="card">
<h2>🔒 Locked: 49 Psychology Hook Lines</h2>
<p class="blur">1. Tumhari vibe thodi different lagti hai…</p>
<p class="blur">2. Ek guess karu tumhare personality ke bare me?</p>
<p class="blur">3. Tum introvert ho ya selective with people?</p>
<p class="blur">4. Tumhari profile dekh ke ek question mind me aaya.</p>
<p class="blur">5. Mujhe lagta hai tum thodi unpredictable ho.</p>

<p><b>Unlock all 49 hooks instantly for just ₹99</b></p>
<a class="btn" href="#buy">Unlock Now</a>
</div>

<div class="card">
<h2>🧠 What You Will Learn</h2>
<ul>
<li>Psychology based openers that trigger curiosity</li>
<li>How to avoid being ignored in DMs</li>
<li>How to make girls continue the conversation</li>
<li>Hooks that work on Instagram, Snapchat & WhatsApp</li>
<li>Copy‑paste lines you can send instantly</li>
</ul>
</div>

<div class="card">
<h2>🔥 Why These Hooks Work</h2>
<ul>
<li>They create curiosity in the first message</li>
<li>They avoid boring "hi / hello" openers</li>
<li>They make the girl want to respond</li>
<li>They feel natural, not cringe</li>
</ul>
</div>

<div class="card">
<h2>🎁 Free Bonuses</h2>
<ul>
<li>10 Instagram DM Starters</li>
<li>5 Psychological Attraction Tricks</li>
<li>Conversation Confidence Tips</li>
</ul>
</div>

<div class="card">
<h2>Real User Reviews</h2>
<p id="testimonialBox">⭐⭐⭐⭐⭐ First message bheja aur reply aaya – Rohit</p>
</div>

<div class="card">
<h2>Offer Ending In</h2>
<p class="timer" id="timer"></p>
</div>

<div class="card" id="buy">
<h2>Get Instant Access</h2>
<p>Normal Price <s>₹499</s></p>
<h2>Today Only ₹99</h2>
<a class="btn" href="https://guptakale402.systeme.io/orderfrom">Buy Now (UPI / Razorpay)</a>
<p style="font-size:14px;margin-top:10px">Instant download after successful payment.</p>
</div>

</div>

<div id="purchaseBox">Someone purchased</div>

<div class="sticky">
<a href="https://guptakale402.systeme.io/orderfrom">🔥 Get 49 Hook Lines – ₹99</a>
</div>

<!-- exit popup -->
<div id="exitPopup" style="position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,.7);display:none;align-items:center;justify-content:center;z-index:9999">
<div style="background:#fff;padding:30px;border-radius:10px;text-align:center;max-width:350px">
<h2>Wait! Special Offer</h2>
<p>Get it for just <b>₹49</b> before leaving</p>
<a href="https://guptakale402.systeme.io/orderfrom" class="btn">Get ₹49 Deal</a><br><br>
<button onclick="closeExit()" style="border:none;background:#ccc;padding:8px 14px;border-radius:6px">No Thanks</button>
</div>
</div>

<!-- footer legal -->
<div class="footer">

<h3>Contact Us</h3>
<p>Email: shashiguptaforu2001@gmail.com</p>

<h3>Terms & Conditions</h3>
<p>This website sells a digital product. By purchasing, you agree that the product is delivered digitally and accessible immediately after payment. Redistribution, resale, or sharing of this product without permission is strictly prohibited.</p>

<h3>Refund Policy</h3>
<p>Due to the nature of digital products, all sales are final. Once the product is delivered, refunds cannot be issued.</p>

<h3>Privacy Policy</h3>
<p>We respect your privacy. Your personal information will never be sold or shared with third parties. Payment processing is handled securely by trusted payment providers.</p>

<p style="margin-top:30px;font-size:13px">© 2026 All Rights Reserved</p>

</div>

</body>
</html>
