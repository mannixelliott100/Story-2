<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>WWE Story</title>

<style>

body {
    margin: 0;
    font-family: 'Helvetica Neue', Arial, sans-serif;
}

/* SECTIONS */
.section {
    width: 100%;
    padding: 80px 0;
}

/* BACKGROUNDS */
.white { background: #fff; }
.black { background: #000; color: #fff; }

/* TITLE */
.title {
    text-align: center;
    font-size: 3em;
    font-weight: 800;
    color: #1e66ff;
}

/* INTRO */
.container {
    max-width: 1000px;
    margin: auto;
    padding: 0 20px;
}

.container p {
    font-size: 1.15em;
    line-height: 1.8;
}

/* SPLIT LAYOUT (FULL WIDTH) */
.split {
    display: flex;
    width: 100%;
    min-height: 600px;
}

.split.reverse {
    flex-direction: row-reverse;
}

.text, .visual {
    flex: 1;
    padding: 80px;
    display: flex;
    align-items: center;
}

/* TEXT */
.text p {
    font-size: 1.2em;
    line-height: 1.8;
    max-width: 600px;
}

/* VISUAL */
.visual {
    justify-content: center;
}

/* FLOURISH */
.flourish-embed,
.flourish-embed iframe {
    width: 100% !important;
    height: 600px !important;
}

/* FULL WIDTH VISUAL */
.full-width {
    width: 100%;
}

/* REMOVE GITHUB LIMITS */
.container-lg,
.markdown-body {
    max-width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
}

/* MOBILE */
@media(max-width: 800px) {
    .split {
        flex-direction: column;
    }

    .text, .visual {
        padding: 40px 20px;
    }
}

</style>
</head>

<body>

<!-- TITLE + INTRO -->
<div class="section white">
    <div class="container">
        <h1 class="title">Story 2 – The Rise of Women’s Wrestling in the 21st Century</h1>

        <p>
        Over the last 40 years, the world of professional wrestling has grown into a worldwide phenomenon which now exists as a significant part of pop culture. Icons throughout the 80’s and 90’s like Hulk Hogan, Stone Cold Steve Austin and The Rock took the industry into the mainstream appeal, being responsible for much of the legendary roots of wrestling. This laid the groundwork for stars like John Cena to take the sport into the 21st century and expand it massively in the digital age.
        </p>

        <p>
        However, as the industry evolved it remained focused on male talent, with women often undermined and misrepresented. Throughout the 90’s and early 2000’s, female wrestlers were frequently objectified and given limited match time. This began to change in the 2010’s, culminating in the “Women’s Revolution,” where female wrestlers became valued for their in-ring ability and character, leading to greater prominence and main event opportunities.
        </p>
    </div>
</div>

<!-- VISUAL 1 FULL -->
<div class="section white">
    <div class="full-width">
        <div class="flourish-embed" data-src="visualisation/28024773"></div>
    </div>
</div>

<!-- VISUAL 2 LEFT / TEXT RIGHT -->
<div class="section white split">
    <div class="visual">
        <div class="flourish-embed" data-src="visualisation/27677179"></div>
    </div>

    <div class="text">
        <p>
        Since the 2015 Women’s Revolution, WWE has seen a steady increase in female talent, growing from 39 wrestlers in 2016 to 67 in 2026 — a 79% increase. This reflects growing demand and a stronger, deeper women’s division.
        </p>
    </div>
</div>

<!-- VISUAL 3 BLACK TEXT LEFT -->
<div class="section black split reverse">
    <div class="visual">
        <div class="flourish-embed" data-src="visualisation/28122283"></div>
    </div>

    <div class="text">
        <p>
        In 2019, AEW was formed, creating competition for WWE and establishing its own women’s division. This grew from 14 wrestlers in 2019 to 56 in 2026 — a 300% increase, reflecting rapid expansion.
        </p>
    </div>
</div>

<!-- VISUAL 4 FULL -->
<div class="section white">
    <div class="full-width">
        <div class="flourish-embed" data-src="visualisation/28085202"></div>
    </div>
</div>

<!-- VISUAL 5 LEFT -->
<div class="section white split">
    <div class="visual">
        <div class="flourish-embed" data-src="visualisation/28087074"></div>
    </div>

    <div class="text">
        <p>
        In the 2020s, stars like Rhea Ripley have reached global audiences. Social media highlights this shift, with women now ranking among the most followed wrestlers, showing their growing influence and popularity.
        </p>
    </div>
</div>

<!-- VISUAL 6 RIGHT -->
<div class="section white split reverse">
    <div class="visual">
        <div class="flourish-embed" data-src="visualisation/27918499"></div>
    </div>

    <div class="text">
        <p>
        Despite growth, inequality remains. Women make up only 33% of WWE’s roster in 2026, showing a significant gender imbalance.
        </p>
    </div>
</div>

<!-- VISUAL 7 BLACK -->
<div class="section black split">
    <div class="visual">
        <div class="flourish-embed" data-src="visualisation/28122168"></div>
    </div>

    <div class="text">
        <p>
        In AEW, the divide is even greater, with women making up just 24% of the roster compared to 163 male wrestlers.
        </p>
    </div>
</div>

<!-- VISUAL 8 -->
<div class="section white split reverse">
    <div class="visual">
        <div class="flourish-embed" data-src="visualisation/28079741"></div>
    </div>

    <div class="text">
        <p>
        Women’s match time and appearances still lag behind men, with percentages across WWE and AEW showing continued disparity in exposure.
        </p>
    </div>
</div>

<!-- VISUAL 9 BLACK -->
<div class="section black split">
    <div class="visual">
        <div class="flourish-embed" data-src="visualisation/28084586"></div>
    </div>

    <div class="text">
        <p>
        Progress has also stalled, with match durations barely increasing between 2022 and 2025, suggesting a slowdown in momentum for women’s wrestling.
        </p>
    </div>
</div>

<script src="https://public.flourish.studio/resources/embed.js"></script>

</body>
</html>
