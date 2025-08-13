<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PUDGECAT</title>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        color: white;
        background: #0a0a0a;
        overflow-x: hidden;
    }
    header {
        text-align: center;
        padding: 20px;
        background: rgba(0,0,0,0.8);
        position: sticky;
        top: 0;
        z-index: 10;
    }
    header img {
        max-height: 80px;
        animation: fadeIn 2s ease-in-out;
    }
    h1, h2, p {
        animation: fadeIn 2s ease-in-out;
    }
    .section {
        padding: 50px 20px;
        text-align: center;
        position: relative;
        z-index: 2;
    }
    .buttons a {
        display: inline-block;
        margin: 10px;
        padding: 12px 24px;
        background: #1e90ff;
        color: white;
        text-decoration: none;
        border-radius: 25px;
        transition: background 0.3s ease;
    }
    .buttons a:hover {
        background: #0d6efd;
    }
    footer {
        text-align: center;
        padding: 20px;
        background: rgba(0,0,0,0.8);
        position: relative;
        z-index: 2;
    }
    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }
    .coin {
        position: fixed;
        top: -50px;
        width: 30px;
        height: 30px;
        background: url('https://cryptologos.cc/logos/base-base-logo.png') no-repeat center/contain;
        animation: fall linear infinite;
        opacity: 0.8;
        z-index: 1;
    }
    @keyframes fall {
        0% { transform: translateY(-50px) rotate(0deg); }
        100% { transform: translateY(110vh) rotate(360deg); }
    }
</style>
</head>
<body>

<header>
    <img src="logo.png" alt="PUDGECAT Logo">
</header>

<div class="section">
    <h1>Welcome to PUDGE Coin – where fun meets crypto!</h1>
    <p>PUDGE is not just a coin, it’s a movement. Together, we conquer the charts, spread laughter, and make history!</p>
    <img src="pudgecat_main.png" alt="Pudgecat" style="max-width:300px; animation: fadeIn 3s;">
</div>

<div class="section">
    <h2>Tokenomics</h2>
    <p>
        <b>Token Name:</b> PUDGECAT<br>
        <b>Symbol:</b> $PUDGE<br>
        <b>Network:</b> BASE<br>
        <b>Total Supply:</b> 1,000,000,000<br>
        <b>Buy/Sell Tax:</b> 0%<br>
        <b>Liquidity:</b> Locked forever<br>
        <b>Ownership:</b> Renounced
    </p>
</div>

<div class="section buttons">
    <a href="https://x.com/PudgeIsCat" target="_blank">Twitter</a>
    <a href="https://t.me/pudgecat" target="_blank">Telegram</a>
    <a href="https://dexscreener.com/base/0xc9758686e669F10cA7E87920745cd4cB84fBfCce" target="_blank">Dexscreener</a>
</div>

<footer>
    Contract Address: 0x333ae9D8BAb1605D7a8E19e327731a5D908a2aCd
</footer>

<script>
    for (let i = 0; i < 20; i++) {
        let coin = document.createElement('div');
        coin.className = 'coin';
        coin.style.left = Math.random() * 100 + 'vw';
        coin.style.animationDuration = (5 + Math.random() * 5) + 's';
        coin.style.width = coin.style.height = (20 + Math.random() * 30) + 'px';
        document.body.appendChild(coin);
    }
</script>

</body>
</html>
