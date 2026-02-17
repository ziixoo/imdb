# imdb<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<title>Топ Фильмы и Сериалы</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #111;
  color: #eee;
}

header {
  background: #000;
  padding: 20px;
  text-align: center;
  font-size: 28px;
  font-weight: bold;
}

nav {
  background: #1c1c1c;
  padding: 10px;
  text-align: center;
}

nav button {
  margin: 5px;
  padding: 10px 18px;
  background: #333;
  border: none;
  color: white;
  cursor: pointer;
  border-radius: 6px;
}

nav button:hover {
  background: #555;
}

.section {
  display: none;
  padding: 25px;
}

.active {
  display: block;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
  gap: 15px;
}

.card {
  background: #1f1f1f;
  padding: 15px;
  border-radius: 10px;
  transition: 0.2s;
}

.card:hover {
  transform: scale(1.04);
  background: #2a2a2a;
}

.badge {
  font-size: 12px;
  background: #444;
  padding: 4px 8px;
  border-radius: 5px;
  display: inline-block;
  margin-bottom: 8px;
}

h3 {
  margin: 6px 0;
}

footer {
  background: #000;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
  font-size: 14px;
}
</style>

<script>
function showSection(id) {
  document.querySelectorAll(".section").forEach(s => s.classList.remove("active"));
  document.getElementById(id).classList.add("active");
}
</script>

</head>
<body>

<header>
🎬 Топ Фильмы и Сериалы
</header>

<nav>
<button onclick="showSection('movies')">Фильмы</button>
<button onclick="showSection('series')">Сериалы</button>
<button onclick="showSection('about')">О сайте</button>
</nav>

<!-- ================= MOVIES ================= -->

<div id="movies" class="section active">
<h2>Топ фильмов по версии IMDb</h2>

<div class="grid">

<!-- IMDb Top 15 -->
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1599028/0b76b2a2-d1c7-4f04-a284-80ff7bb709a4/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>1. Побег из Шоушенка</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/12808873/2a00000198a2c9d5eeda074ef3c44a1720e0/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>2. Крёстный отец</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1599028/0fa5bf50-d5ad-446f-a599-b26d070c8b99/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>3. Тёмный рыцарь</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1599028/3560b757-9b95-45ec-af8c-623972370f9d/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>4. Форрест Гамп</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1600647/430042eb-ee69-4818-aed0-a312400a26bf/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>5. Интерстеллар</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/4716873/1cea92d1-c13f-4b31-af0f-3e23f6b6e132/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>6. Крестный отец 2</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/9784475/081f9649-0bbd-4232-b4d7-1312c64e567c/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>7. 12 разгневанных мужчин</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/6201401/1e1ac6d9-c658-4f5f-937e-d080bca0d893/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>8. Список Шиндлера</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/6201401/a2d5bcae-a1a9-442f-8195-f5373a5ba77f/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>9. Властелин колец</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/4716873/0a07a903-9025-4aff-bf7c-46bbb175888c/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>10. Криминальное чтиво</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1773646/8b9d4616-9426-4c74-a63c-296189f28213/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>11. Хороший, плохой,злой</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/1672343/2a0000019a2f25469292045d741a2afdddd3/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>12. Бойцовский клуб</h3>
</div>
</div>


<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1629390/8ab9a119-dd74-44f0-baec-0629797483d7/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>13. Начало</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/1652588/2a000001867933df86991a0a7ae0ed78ee98/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>14. Матрица</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/9784475/58e981ae-27fb-4b67-a1f3-e44a2b30be6b/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>15. Семь самураев</h3>
</div>
</div>

<!-- Letterboxd Top 15 -->
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/4303601/aae3a928-6465-4bed-9af4-16929a44fd79/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>1. Паразиты</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/9784475/58e981ae-27fb-4b67-a1f3-e44a2b30be6b/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>2. Семь самураев</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/6201401/49ba5c05-249b-4387-8418-833aa54bb376/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>3. Сияние</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1599028/a2735b42-6807-46ba-8a15-e0ba94db8a65/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>4. 2001: Космическая одиссея</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/2385704/2a0000019855237d1ede634ec1d008517753/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>5. Таксист</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/9784475/0b9191b6-319e-423b-8548-d745ef68232a/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>6. Аппокалипсис сегодня</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/1534341/2a0000019853a42db7123dea59c07fc1ffeb/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>7. Город Бога</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/13074011/2a00000198e599109a91f21a2fee46373ad6/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>8. Сталкер</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/6201401/16af46be-bcfe-461e-af54-ff17b905b82e/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>9. Одержимость</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1900788/d4fa3478-cc0a-432f-9821-7a6bda84ccba/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>10. Лабиринт фавна</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/223007/2a0000019852173ec91d90e4d536838e6e8c/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>11. Славные парни</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/1672343/2a00000198529858713ecfd5e851118b562b/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>12. Олдбой</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1946459/6d71694e-3796-4e1c-96aa-0e982c2bc03d/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>13. Пианист</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1898899/6acfd359-9d95-4287-9fe8-63e911be0dcb/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>14. Зеркало</h3>
</div>
</div>

</div>
</div>

<!-- ================= SERIES ================= -->

<div id="series" class="section">
<h2>Топ сериалов</h2>

<div class="grid">

<!-- IMDb Top 15 -->
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1900788/fb35416f-3b0d-4b96-bc65-cf6923f9e329/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>1. Во все тяжкие</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/13051577/2a0000019aeee1de64365e22bceabf644cc6/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>2. Чернобыль</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1600647/3bf6510a-a1de-467c-bf40-9362ba27f1ec/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>3. Планета Земля</h3>
</div>
</div>

<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/223007/2a0000019ac4dd89faa11e6aaad153449ef8/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>4. Братья по  оружию</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/2385704/2a0000019aeedf372aef158a841222270160/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>5. Игра престолов</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/12808873/2a0000019aeede7feabb88c64c5dad4e22e2/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>6. Прослушка</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/2439731/2a0000019aeee26a079a99af8cc7de139146/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>7. Рик и Морти</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1629390/f28c1ea2-47b0-49d5-b11c-9608744f0233/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>8. Шерлок</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/2385704/2a0000019aeee395436194162e8876082969/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>9. Настоящий детектив</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1600647/6d3dc38e-5912-4f4b-b4bd-2f67b0e50176/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>10. Фарго</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1898899/57ad896e-6eeb-4242-af4a-bd47c3ad24d1/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>11. Мандалорец</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1599028/7bbd225f-e6db-4326-b600-1ac294cf9d99/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>12. Офис</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/212840/2a0000019850cac2ea6b4c5fa3c5a8b25402/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>13. Друзья</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/10703859/1e653cad-c84f-4617-b61e-949b3228ef36/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>14. Очень странные дела</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1599028/270df10e-2e72-4d8e-a49b-f84c751162a7/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">IMDb</div>
<h3>15. Доктор Хаус</h3>
</div>
</div>

<!-- Letterboxd-style favorites -->
<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/13051577/2a0000019851440254324825802687853be8/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>1. Твин Пикс</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/212840/2a0000019aeee0a3cfce260d762b1f3414f1/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>2. Наследники </h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1600647/10c5f480-c2ca-481f-a343-1faf5225614e/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>3. Атланта</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1773646/64500638-f5f3-4e9d-b672-ddbdf74d95e6/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>4. Дрянь</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/4486362/7ab69af7-bdad-4f81-aedb-33eddad97baa/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>5. Медведь </h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/6201401/a3083748-bfab-410f-a223-8d355f4b0c95/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>6. Тьма</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1898899/f3b08a0e-9f75-4e2f-8879-0a914cb54d05/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>7. Мистер Робот</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1946459/87298984-6286-425f-ab61-9afbf2c78afb/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>8. Лучше звоните Соулу</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/2385704/2a0000019aeee395436194162e8876082969/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>9. Настоящий детектив</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1898899/36737195-6026-4310-be80-5545d7d22447/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>10. Чёрное зеркало </h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/9784475/4db7b6c7-3948-48ae-8fc2-30a68e3a915b/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>11. Оставленные</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/236744/2a0000019851163735ff9f844e1cc3406c89/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>12. Декстер</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/1777765/c657ae89-e600-42a9-983f-6f4ee685b5b3/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>13. Ход королевы</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-ott/223007/2a000001827d34aee9db5d3d7f0f0ffa54a9/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>14. Эйфория</h3>
</div>
</div>
<div class="card">
<img src="https://avatars.mds.yandex.net/get-kinopoisk-image/4774061/d906e201-8f29-42ab-8a56-9d7e882856a2/80x120?text=Film" class="poster">
<div class="card-content">
<div class="badge">Letterboxd</div>
<h3>15. Аркейн</h3>
</div>
</div>


</div>
</div>

<!-- ================= ABOUT ================= -->

<div id="about" class="section">
<h2>О сайте</h2>

<p>
Этот сайт создан как каталог лучших фильмов и сериалов по пользовательским рейтингам.
Здесь собраны самые высоко оцениваемые проекты по версиям IMDb и Letterboxd.
</p>

<h3>Связь с создателем</h3>
<p>
Создатель: Aiya Shaidilda<br>
Email: aiyaperson@gmail.com<br>
</p>

<h3>FAQ</h3>

<p><b>Откуда рейтинги?</b><br>
Списки составлены на основе пользовательских топов IMDb и Letterboxd.</p>

<p><b>Будет ли обновление?</b><br>
Да, список можно расширять и обновлять.</p>

</div>

<footer>
© 2026 Топ Фильмы и Сериалы
</footer>

</body>
</html>

