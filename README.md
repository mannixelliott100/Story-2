<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Story 2 – Women’s Wrestling in the 21st Century</title>

<style>
body {
    margin: 0;
    font-family: 'Helvetica Neue', Arial, sans-serif;
    background: #fff; /* base page background */
    color: #222;
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
}

.top-left { position: absolute; left: 10px; }
.top-center { text-align: center; width: 100%; }
.top-right { position: absolute; right: 10px; top: 0; }

/* SECTION STYLES */
.section {
    width: 100%;
    display: flex;
    flex-direction: column;
    padding: 60px 0;
    box-sizing: border-box;
}

.section.white { background: #fff; color: #222; }
.section.black { background: #111; color: #fff; }
.section.black p { color: #ddd; }

/* HEADINGS */
h1, h2 {
    margin: 0 0 30px 0;
    text-align: center;
}

h1 { font-size: 3em; font-weight: 700; }
h2 { font-size: 1.8em; margin-bottom: 40px; }

/* TEXT */
p {
    font-size: 1.15em;
    line-height: 1.75;
    max-width: 800px;
    margin: 0 auto 25px auto;
}

/* SPLIT SECTIONS FULL WIDTH VISUALS */
.split {
    display: flex;
    width: 100%;
    flex-wrap: wrap;
}

.split.reverse { flex-direction: row-reverse; }

.text-side {
    flex: 1 1 50%;
    padding: 40px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.visual-side {
    flex: 1 1 50%;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
}

.visual-side .flourish-embed,
.visual-side .visual-box,
.full-visual {
    width: 100%;
    height: 100%;
    max-width: none;
}

/* FULL WIDTH VISUALS */
.full-visual {
    display: flex;
    justify-content: center;
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
@media(max-width: 900px) {
    .split {
        flex-direction: column;
    }
    .text-side, .visual-side {
        flex: 1 1 100%;
        padding: 20px;
    }
}
</style>
</head>

<body>

<div class="top-bar">
    <div class="top-left">202226944</div>
    <div class="top-center">
        <a href="https://www.strath.ac.uk" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/en/thumb/2/21/University_of_Strathclyde_Coat_of_Arms.svg/1280px-University_of_Strathclyde_Coat_of_Arms.svg.png" alt="Strathclyde Logo" style="height: 25px;">
        </a>
    </div>
    <div class="top-right">STORY 2</div>
</div>

<!-- HERO SECTION -->
<div class="section white reveal">
    <h1>Story 2 – The Rise of Women’s Wrestling in the 21st Century</h1>
    <p>
Over the last 40 years, professional wrestling has become a global phenomenon. Icons like Hulk Hogan, Stone Cold Steve Austin, and The Rock brought wrestling into the mainstream, paving the way for stars like John Cena in the 21st century.
    </p>
    <p>
Women’s wrestling remained underrepresented through the 90’s and 2000’s, often objectified and limited in screen time. The early 2010s saw the creation of all-female divisions, culminating in the WWE “Women’s Revolution” of 2025, which finally positioned women as main-event talents.
    </p>
</div>

<!-- VISUAL 1 FULL WIDTH -->
<div class="section white reveal full-visual">
    <div class="flourish-embed flourish-chart" data-src="visualisation/28024773"></div>
</div>

<!-- SPLIT VISUAL 2 LEFT -->
<div class="section white reveal">
    <div class="split">
        <div class="visual-side visual-box">
            <div class="flourish-embed flourish-chart" data-src="visualisation/27677179"></div>
        </div>
        <div class="text-side">
            <p>
Since 2015, WWE female roster increased from 39 to 67 wrestlers by 2026. AEW launched in 2019 with its women’s division increasing from 14 to 56 in 2026.
            </p>
        </div>
    </div>
</div>

<!-- SPLIT VISUAL 3 BLACK RIGHT -->
<div class="section black reveal">
    <div class="split reverse">
        <div class="text-side">
            <p>
Female stars like Trish Stratus, Lita, and Chyna laid the foundations for modern women’s wrestling despite the male-dominated era of the 90s and 2000s.
            </p>
        </div>
        <div class="visual-side visual-box">
            <div class="flourish-embed flourish-chart" data-src="visualisation/28122283"></div>
        </div>
    </div>
</div>

<!-- VISUAL 4 FULL WIDTH WHITE -->
<div class="section white reveal full-visual">
    <div class="flourish-embed flourish-chart" data-src="visualisation/28085202"></div>
</div>

<!-- SPLIT VISUAL 5 LEFT -->
<div class="section white reveal">
    <div class="split reverse">
        <div class="visual-side visual-box">
            <div class="flourish-embed flourish-chart" data-src="visualisation/28087074"></div>
        </div>
        <div class="text-side">
            <p>
Despite growth in women’s wrestling, only 33% of WWE talent is female as of 2026.
            </p>
        </div>
    </div>
</div>

<!-- SPLIT VISUAL 6 RIGHT -->
<div class="section white reveal">
    <div class="split">
        <div class="text-side">
            <p>
Within AEW, women make up only 24% of the roster in 2026, highlighting ongoing inequality.
            </p>
        </div>
        <div class="visual-side visual-box">
            <div class="flourish-embed flourish-chart" data-src="visualisation/27918499"></div>
        </div>
    </div>
</div>

<!-- SPLIT VISUAL 7 BLACK LEFT -->
<div class="section black reveal">
    <div class="split reverse">
        <div class="visual-side visual-box">
            <div class="flourish-embed flourish-chart" data-src="visualisation/28122168"></div>
        </div>
        <div class="text-side">
            <p>
Inequality is evident in match appearances and total screen time for women across WWE and AEW.
            </p>
        </div>
    </div>
</div>

<!-- SPLIT VISUAL 8 RIGHT -->
<div class="section white reveal">
    <div class="split reverse">
        <div class="visual-side visual-box">
            <div class="flourish-embed flourish-chart" data-src="visualisation/28079741"></div>
        </div>
        <div class="text-side">
            <p>
AEW shows stagnation in women’s ring time, with minimal growth from 2022 to 2025.
            </p>
        </div>
    </div>
</div>

<!-- SPLIT VISUAL 9 BLACK RIGHT -->
<div class="section black reveal">
    <div class="split">
        <div class="text-side">
            <p>
Women’s match times remain largely unchanged, reflecting slow progress in AEW.
            </p>
        </div>
        <div class="visual-side visual-box">
            <div class="flourish-embed flourish-chart" data-src="visualisation/28084586"></div>
        </div>
    </div>
</div>

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
