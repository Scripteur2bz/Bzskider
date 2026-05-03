<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SCRIPTEUR2BZskider</title>

<style>
/* ====== GLOBAL ====== */
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body{
    background: radial-gradient(circle at top, #0d0f1a, #05060a);
    color:white;
    min-height:100vh;
    display:flex;
    flex-direction:column;
    align-items:center;
    overflow-x:hidden;
}

/* ====== HEADER ====== */
header{
    text-align:center;
    margin-top:20px;
    position:relative;
}

.title-main{
    font-size:48px;
    font-weight:900;
    background: linear-gradient(90deg,#00b7ff,#0066ff,#00e1ff);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
    animation: shine 3s infinite linear;
}

.title-sub{
    font-size:22px;
    color:#ff2d2d;
    margin-top:-10px;
    letter-spacing:2px;
}

/* light shine */
@keyframes shine{
    0%{filter:brightness(1);}
    50%{filter:brightness(2);}
    100%{filter:brightness(1);}
}

/* ====== CONTAINER ====== */
.container{
    width:90%;
    max-width:1000px;
    margin-top:30px;
    background: rgba(255,255,255,0.05);
    border:1px solid rgba(255,255,255,0.1);
    border-radius:15px;
    padding:20px;
    backdrop-filter: blur(10px);
    position:relative;
    overflow:hidden;
}

/* light reflection */
.container::before{
    content:"";
    position:absolute;
    top:-50%;
    left:-50%;
    width:200%;
    height:200%;
    background: linear-gradient(120deg,transparent,rgba(0,255,255,0.1),transparent);
    transform:rotate(25deg);
    animation: moveLight 6s infinite linear;
}

@keyframes moveLight{
    0%{transform:translateX(-100%) rotate(25deg);}
    100%{transform:translateX(100%) rotate(25deg);}
}

/* ====== INPUTS ====== */
textarea, input{
    width:100%;
    margin-top:10px;
    padding:10px;
    border-radius:8px;
    border:none;
    outline:none;
    background:#0b0f1a;
    color:white;
}

textarea{
    height:150px;
    resize:none;
}

label{
    margin-top:10px;
    display:block;
    font-size:14px;
    opacity:0.8;
}

/* ====== BUTTONS ====== */
button{
    margin-top:15px;
    padding:10px 15px;
    border:none;
    border-radius:8px;
    cursor:pointer;
    font-weight:bold;
    transition:0.3s;
}

button:hover{
    transform:scale(1.05);
}

.primary{
    background:#00aaff;
    color:white;
}

.copy{
    background:#00ff88;
}

/* ====== PREVIEW ====== */
.preview{
    margin-top:15px;
    padding:10px;
    background:#05070f;
    border-radius:10px;
    min-height:100px;
    white-space:pre-wrap;
}

.highlight{
    background:red;
    color:white;
    padding:2px;
}

/* ====== LOADING ====== */
.loading-box{
    display:none;
    margin-top:15px;
}

.bar{
    width:100%;
    height:10px;
    background:#222;
    border-radius:5px;
    overflow:hidden;
}

.progress{
    height:100%;
    width:0%;
    background:linear-gradient(90deg,#00b7ff,#00ffcc);
    transition:width 0.2s;
}

/* ====== ERROR ====== */
.error{
    color:#ff3b3b;
    margin-top:10px;
    font-weight:bold;
}

/* ====== FOOTER ====== */
footer{
    margin-top:40px;
    padding:20px;
    text-align:center;
    font-size:14px;
    opacity:0.7;
    max-width:900px;
}

/* ====== CREDIT BUTTON ====== */
.credit{
    margin-top:10px;
    background:#ff0000;
    color:white;
    padding:10px 15px;
    border-radius:8px;
    display:inline-flex;
    align-items:center;
    gap:8px;
    cursor:pointer;
}
.credit:hover{
    background:#cc0000;
}

</style>
</head>

<body>

<header>
    <div class="title-main">SCRIPTEUR2BZ</div>
    <div class="title-sub">skider</div>
</header>

<div class="container">

    <label>Script original</label>
    <textarea id="script"></textarea>

    <label>Mot à chercher</label>
    <input id="search" type="text">

    <label>Nouveau mot</label>
    <input id="replace" type="text">

    <button class="primary" onclick="preview()">Prévisualiser</button>
    <button class="primary" onclick="startProcess()">Remplacer</button>

    <div class="error" id="error"></div>

    <div class="preview" id="preview"></div>

    <div class="loading-box" id="loadingBox">
        <div>Loading...</div>
        <div class="bar">
            <div class="progress" id="progress"></div>
        </div>
    </div>

    <button class="copy" onclick="copyResult()">Copier le résultat</button>

</div>

<footer>
Ce site est créé pour aider les petits créateurs de script qui n’ont pas d’inspiration, cela les aide simplement à modifier plus rapidement les scripts et changer les noms.
<br>

<div class="credit" onclick="window.open('https://youtube.com/@scripteur2bz?si=FwLg8DBPWS1UFEtj')">
▶ YouTube - Scripteur2bz
</div>
</footer>

<script>

function preview(){
    let script = document.getElementById("script").value;
    let word = document.getElementById("search").value;
    let preview = document.getElementById("preview");
    let error = document.getElementById("error");

    error.textContent = "";

    if(!word){
        preview.textContent = script;
        return;
    }

    let regex = new RegExp(word, "gi");

    if(!script.match(regex)){
        error.textContent = "ERROR : mot introuvable dans le script";
        preview.textContent = script;
        return;
    }

    preview.innerHTML = script.replace(regex, match => `<span class="highlight">${match}</span>`);
}

function startProcess(){
    let script = document.getElementById("script").value;
    let word = document.getElementById("search").value;
    let replace = document.getElementById("replace").value;
    let error = document.getElementById("error");

    let regex = new RegExp(word, "gi");

    if(!script.match(regex)){
        error.textContent = "ERROR : mot introuvable dans le script";
        return;
    }

    error.textContent = "";
    document.getElementById("loadingBox").style.display = "block";

    let progress = document.getElementById("progress");
    let percent = 0;

    let interval = setInterval(() => {
        percent += 5;
        progress.style.width = percent + "%";

        if(percent >= 100){
            clearInterval(interval);
            document.getElementById("loadingBox").style.display = "none";

            let result = script.replace(regex, replace);
            document.getElementById("preview").textContent = result;
        }
    }, 80);
}

function copyResult(){
    let text = document.getElementById("preview").innerText;
    navigator.clipboard.writeText(text);
    alert("Copié !");
}

</script>

</body>
</html>
