<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Taj Mahal - Aesthetic Page</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;700&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(to right, #dfe9f3, #ffffff);
}

/* BIG AESTHETIC HEADING */
h1 {
    text-align: center;
    font-size: 75px;
    margin: 20px;
    color: #2c3e50;
    letter-spacing: 3px;
    animation: glow 2s infinite alternate;
}

@keyframes glow {
    from { text-shadow: 0 0 10px #aaa; }
    to { text-shadow: 0 0 25px #3498db, 0 0 40px #3498db; }
}

/* SLIDER */
.slider {
    width: 80%;
    margin: auto;
    overflow: hidden;
    border-radius: 15px;
}

.slides {
    display: flex;
    width: 300%;
    animation: slide 9s infinite;
}

.slides img {
    width: 100%;
}

@keyframes slide {
    0% {margin-left: 0;}
    33% {margin-left: -100%;}
    66% {margin-left: -200%;}
}

/* CONTENT */
.container {
    width: 85%;
    margin: auto;
    background: white;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 0 10px rgba(0,0,0,0.2);
}

/* IMAGE + TEXT SIDE */
.row {
    display: flex;
    gap: 20px;
    margin-bottom: 20px;
    align-items: center;
}

.row img {
    width: 40%;
    border-radius: 10px;
}

.row p {
    width: 60%;
    font-size: 18px;
    line-height: 1.6;
}

/* HEADINGS */
h2 {
    color: #2980b9;
    border-bottom: 2px solid #2980b9;
}

/* LIST */
ul {
    font-size: 18px;
}

/* FOOTER */
footer {
    text-align: center;
    background: #2c3e50;
    color: white;
    padding: 15px;
    margin-top: 20px;
}
</style>
</head>

<body>

<h1>✨ TAJ MAHAL ✨</h1>

<!-- 3 IMAGE SLIDER -->
<div class="slider">
    <div class="slides">
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/Taj-Mahal.jpg">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Taj_Mahal_in_March_2004.jpg">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6d/Taj_Mahal_at_sunrise.jpg">
    </div>
</div>

<div class="container">

<h2>About Taj Mahal</h2>

<!-- Paragraph 1 with image -->
<div class="row">
    <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/Taj-Mahal.jpg">
    <p>
        The Taj Mahal is one of the most famous historical monuments in the world. 
        It is a beautiful white marble mausoleum built by Mughal Emperor Shah Jahan 
        in memory of his wife Mumtaz Mahal. The monument is admired for its stunning 
        design and perfect symmetry.
    </p>
</div>

<!-- Paragraph 2 -->
<div class="row">
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Taj_Mahal_in_March_2004.jpg">
    <p>
        It is located in Agra, Uttar Pradesh, India, near the Yamuna River. 
        Construction began in 1632 and was completed in 1653. Thousands of 
        workers and artists contributed to creating this masterpiece.
    </p>
</div>

<!-- Paragraph 3 -->
<div class="row">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6d/Taj_Mahal_at_sunrise.jpg">
    <p>
        The Taj Mahal is historically important because it symbolizes eternal love. 
        It is also a UNESCO World Heritage Site and one of the Seven Wonders of the World.
    </p>
</div>

<!-- Paragraph 4 -->
<p>
    The monument looks different at different times of the day. It appears pink in the morning, 
    white in the afternoon, and golden under moonlight, making it a magical experience.
</p>

<h2>Interesting Facts</h2>
<ul>
    <li>✔ Built with white marble</li>
    <li>✔ Took 22 years to complete</li>
    <li>✔ Over 20,000 workers worked on it</li>
    <li>✔ Changes color throughout the day</li>
</ul>

</div>

<footer>
❤️ A Symbol of Eternal Love ❤️
</footer>

</body>
</html>
