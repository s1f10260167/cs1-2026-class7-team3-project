<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>おすすめ紹介サイト</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family: sans-serif;
    background:#f5f5f5;
}

header{
    height:180px;
    border-bottom:2px solid #555;
    display:flex;
    justify-content:center;
    align-items:center;
    font-size:40px;
    font-weight:bold;
}

.catch-copy{
    width:70%;
    margin:50px auto 20px;
    border:2px solid #555;
    padding:25px;
    font-size:40px;
}

.genre-title{
    width:300px;
    height:180px;
    border:2px solid #555;
    margin:0 auto 30px;
    display:flex;
    justify-content:center;
    align-items:center;
    font-size:40px;
}

.genre-container{
    width:90%;
    margin:0 auto 50px;
    display:flex;
    justify-content:space-between;
    gap:30px;
}

.genre-card{
    flex:1;
    height:450px;
    border:2px solid #555;
    background:white;

    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;

    text-decoration:none;
    color:black;

    font-size:40px;
    transition:0.3s;
}

.genre-card:hover{
    transform:scale(1.03);
    background:#eaeaea;
}

@media(max-width:900px){

    .genre-container{
        flex-direction:column;
        align-items:center;
    }

    .genre-card{
        width:80%;
    }

    .catch-copy{
        width:90%;
        font-size:30px;
    }

    .genre-title{
        width:80%;
    }
}
</style>

</head>
<body>

<header>
    おすすめ紹介サイト
</header>

<div class="catch-copy">
    人気作品をランキング順におすすめ！
</div>

<div class="genre-title">
    ジャンルを選ぶ
</div>

<div class="genre-container">

    <a href="anime.html" class="genre-card">
        アニメ<br>
        （画像）<br>
        クリックでページ移動
    </a>

    <a href="drama.html" class="genre-card">
        ドラマ
    </a>

    <a href="movie.html" class="genre-card">
        映画
    </a>

</div>

</body>
</html>