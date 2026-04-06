<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GameScope | Yeni Oyunlar 2026</title>

<meta name="description" content="En yeni oyunlar, GTA 6, FC 25, Call of Duty ve daha fazlası. GameScope ile oyun dünyasını keşfet.">

<style>
body {
    margin:0;
    font-family:Arial;
    background: linear-gradient(to right, #0f172a, #1e293b);
    color:white;
}

header {
    text-align:center;
    padding:20px;
    font-size:28px;
    color:#38bdf8;
}

.container {
    display:grid;
    grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
    gap:15px;
    padding:20px;
}

.game {
    background:#1e293b;
    padding:15px;
    border-radius:10px;
    transition:0.3s;
}

.game:hover {
    transform:scale(1.05);
}

button {
    margin-top:10px;
    padding:10px;
    border:none;
    background:#38bdf8;
    cursor:pointer;
    border-radius:5px;
}
</style>
</head>

<body>

<header>🎮 GameScope | En Yeni Oyunlar</header>

<div class="container">

<script>
let games = [
"GTA 6","FC 25","Call of Duty","Minecraft","Fortnite","Roblox",
"Valorant","CS2","PUBG","Brawl Stars","Clash Royale",
"Red Dead Redemption 2","Cyberpunk 2077","Spider-Man 2",
"God of War","The Last of Us","Resident Evil 4","FIFA 23",
"Battlefield 2042","Apex Legends","Hogwarts Legacy",
"Assassin's Creed","Far Cry 6","Dying Light 2","Rust",
"Ark Survival","Among Us","Fall Guys","Rocket League",
"Need for Speed","Forza Horizon 5","Genshin Impact",
"League of Legends","Dota 2","Overwatch 2","Warzone",
"Hitman 3","Dead by Daylight","Subnautica","Terraria",
"Elden Ring","Dark Souls","Sekiro","Bloodborne",
"Watch Dogs","The Crew","Outlast","Phasmophobia",
"Stardew Valley","The Forest"
];

games.forEach(game=>{
document.write(`
<div class="game">
<h3>${game}</h3>
<p>Bu oyun hakkında detaylı bilgiler yakında eklenecek.</p>
<button onclick="alert('${game} yakında eklenecek')">İncele</button>
</div>
`);
});
</script>

</div>

</body>
</html>
