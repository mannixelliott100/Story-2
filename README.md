<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Women’s Wrestling Story</title>

<style>
/* RESET AND BODY */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Helvetica Neue', Arial, sans-serif;
    background: #fff;
    color: #222;
    line-height: 1.7;
}

/* TOP BAR */
.top-bar {
    position: fixed;
    top: 10px;
    left: 0;
    width: 100%;
    font-size: 12px;
    font-family: Arial, sans-serif;
    z-index: 9999;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

.top-center img {
    height: 25px;
}

/* SECTIONS */
.section {
    width: 100%;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.section.white { background: #fff; color: #222; }
.section.black { background: #111; color: #fff; }
.section.black p { color: #ddd; }

/* SPLIT LAYOUT */
.split {
    display: flex;
    width: 100%;
    height: 100%;
    flex-wrap: nowrap;
}

.split.reverse { flex-direction: row-reverse; }

.text-side, .visual-side {
    flex: 1 1 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 40px;
}

/* FULL-SIZE VISUALS */
.visual-side {
    width: 100%;
    height: 100%;
}

.visual-side .flourish-embed {
    width: 100% !important;
    height: 100% !important;
    min-height: 80vh;
}

/* HERO TEXT */
.hero-text {
    text-align: center;
    max-width: 900px;
    font-size: 1.2em;
    padding: 60px;
}

/* HEADINGS */
h1, h2 {
    text-align: center;
    margin: 20px 0;
}

h1 { font-size: 3em; }
h2 { font-size: 2em; }

/* REMOVE CONSTRAINTS */
.container {
    max-width: none;
    padding: 0;
}

.visual-box {
    padding: 0;
    margin: 0;
    background: none;
    box-shadow: none;
    border-radius: 0;
}

/* ANIMATION */
.reveal {
    opacity: 0;
    transform: translateY(30px);
    transition: all 0.9s ease;
}

.reveal.visible {
    opacity: 1;
    transform: translateY(0);
}

/* RESPONSIVE */
@media (max-width: 1000px) {
    .split {
        flex-direction: column;
    }
    .text-side, .visual-side {
        width: 100%;
        padding: 20px;
    }
    .visual-side .flourish-embed { min-height: 60vh; }
    h1 { font-size: 2.2em; }
    h2 { font-size: 1.6em; }
}
</style>
</head>

<body>

<!-- TOP BAR -->
<div class="top-bar">
    <div>202226944</div>
    <div class="top-center">
        <a href="https://www.strath.ac.uk" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/en/thumb/2/21/University_of_Strathclyde_Coat_of_Arms.svg/1280px-University_of_Strathclyde_Coat_of_Arms.svg.png" alt="Strathclyde Logo">
        </a>
    </div>
    <div>STORY 2</div>
</div>

<!-- HERO SECTION -->
<div class="section white reveal">
    <div class="hero-text">
        <h1>Story 2 – The Rise of Women’s Wrestling in the 21st Century</h1>
        <p>
Over the last 40 years, professional wrestling has grown into a worldwide phenomenon. Icons like Hulk Hogan, Stone Cold, and The Rock brought wrestling into mainstream popularity, setting the stage for stars like John Cena in the 21st century.
        </p>
        <p>
Female wrestlers were often misrepresented until the 2010s, when an all-female division emerged and eventually led to “The Women’s Revolution” of 2025, valuing talent and character over looks, positioning women as main-event stars.
        </p>
    </div>
</div>

<!-- TIMELINE VISUAL -->
<div class="section white reveal">
    <div class="visual-side full-width">
        <div class="flourish-embed" data-src="visualisation/28024773"></div>
    </div>
</div>

<!-- VISUAL 2 - WHITE -->
<div class="section white reveal">
    <div class="split reverse">
        <div class="visual-side full-width">
            <div class="flourish-embed" data-src="visualisation/27677179"></div>
        </div>
        <div class="text-side">
            <p>
Since the 2015 “Women’s Revolution,” WWE has seen a steadily positive increase in female talent, growing from 39 signed women in 2016 to 67 in 2026 — nearly 79% increase.
            </p>
        </div>
    </div>
</div>

<!-- VISUAL 3 - BLACK -->
<div class="section black reveal">
    <div class="split">
        <div class="text-side">
            <p>
In 2019, AEW was formed to rival WWE’s monopoly, developing its own women’s division which grew from 14 to 56 signed women by 2026 — a 300% increase over 7 years.
            </p>
        </div>
        <div class="visual-side full-width">
            <div class="flourish-embed" data-src="visualisation/28122283"></div>
        </div>
    </div>
</div>

<!-- VISUAL 4 -->
<div class="section white reveal">
    <div class="visual-side full-width">
        <div class="flourish-embed" data-src="visualisation/28085202"></div>
    </div>
</div>

<!-- VISUAL 5 -->
<div class="section white reveal">
    <div class="split">
        <div class="visual-side full-width">
            <div class="flourish-embed" data-src="visualisation/28087074"></div>
        </div>
        <div class="text-side">
            <p>
Athletes like Rhea Ripley became worldwide stars, reflecting a boom in women’s wrestling post-2020. Social media shows 7 of the top-followed wrestlers in 2026 are women.
            </p>
        </div>
    </div>
</div>

<!-- VISUAL 6 - BLACK -->
<div class="section black reveal">
    <div class="split reverse">
        <div class="visual-side full-width">
            <div class="flourish-embed" data-src="visualisation/27918499"></div>
        </div>
        <div class="text-side">
            <p>
Despite growth, inequality persists: only 33% of WWE signed talent are women in 2026.
            </p>
        </div>
    </div>
</div>

<!-- VISUAL 7 - BLACK -->
<div class="section black reveal">
    <div class="split">
        <div class="visual-side full-width">
            <div class="flourish-embed" data-src="visualisation/28122168"></div>
        </div>
        <div class="text-side">
            <p>
AEW shows an even larger divide: only 24% of signed talent are women (52 women vs 163 men) as of 2026.
            </p>
        </div>
    </div>
</div>

<!-- SCRIPT -->
<script src="https://public.flourish.studio/resources/embed.js"></script>
<script>
const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
        if(entry.isIntersecting){
            entry.target.classList.add('visible');
        }
    });
}, { threshold: 0.2 });

document.querySelectorAll('.reveal').forEach(el => observer.observe(el));
</script>

</body>
</html>
