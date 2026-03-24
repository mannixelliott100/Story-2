<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>UFC Story</title>

<style>

body {
    margin: 0;
    font-family: 'Helvetica Neue', Arial, sans-serif;
    background: #f5f5f5;
}

/* SECTIONS */
.section {
    width: 100%;
    padding: 70px 0;
}

.container {
    max-width: 1200px;
    margin: auto;
    padding: 0 20px;
}

/* BACKGROUNDS */
.white { background: #fff; }
.red {
    background: #d60000;
    color: #fff;
}

/* TITLE */
.title {
    text-align: center;
    font-size: 3em;
    font-weight: 800;
    color: #d60000;
    text-shadow: 2px 2px 0 #8b0000, 4px 4px 10px rgba(0,0,0,0.4);
}

/* TEXT */
p {
    font-size: 1.15em;
    line-height: 1.8;
}

/* SPLIT LAYOUT */
.split {
    display: flex;
    align-items: center;
    gap: 40px;
}

.split.reverse {
    flex-direction: row-reverse;
}

.text, .visual {
    flex: 1;
}

.visual-box {
    background: #fff;
    padding: 15px;
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
}

/* FULL WIDTH */
.full-width {
    width: 100%;
}

/* EXPLAINER HEADINGS */
.explainer h3 {
    color: #d60000;
    border: 2px solid #d60000;
    padding: 8px 12px;
    display: inline-block;
    margin-top: 30px;
}

/* ANIMATION */
.reveal {
    opacity: 0;
    transform: translateY(40px);
    transition: 0.8s ease;
}

.reveal.visible {
    opacity: 1;
    transform: translateY(0);
}

/* RESPONSIVE */
@media(max-width: 800px) {
    .split {
        flex-direction: column;
    }
}

/* === ADDED HEADER STYLES === */
.top-bar {
    position: fixed;
    top: 10px;
    left: 0;
    width: 100%;
    font-size: 12px;
    font-family: Arial, sans-serif;
    z-index: 9999;
}

.top-left {
    position: absolute;
    left: 10px;
}

.top-center {
    text-align: center;
    width: 100%;
}

.top-right {
    position: absolute;
    right: 10px;
    top: 0;
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

<div class="section white reveal">
    <div class="container">
        <h1 class="title">
            STORY 1: THE RISE OF THE UFC AND MIXED MARTIAL ARTS IN GLASGOW
        </h1>
    </div>
</div>


<div class="section white reveal">
    <div class="container split">

        <div class="text">
            <p>
Since the early 90’s individual martial arts have grown greatly within sport to become more prominent in the mainstream media, international events like the Olympics, and developing into their very own Box Office attractions. The sport of Mixed Martial Arts (MMA) is no exception in this matter, growing from small and struggling unsanctioned contests with no rules, to the fastest rising combat sport today. The Ultimate fighting Championship (UFC) is responsible to bringing MMA directly into the mainstream, facing early struggles in the 1990’s nearly leading to its closure entirely.
            </p>
        </div>

        <div class="visual visual-box">
            <div class="flourish-embed" data-src="visualisation/27293352"></div>
        </div>

    </div>
</div>


<div class="section white reveal explainer">
    <div class="container">

        <h3>What is Mixed Martial Arts?</h3>
        <p>
Mixed Martial Arts is a combat sport based around what is known as “The Art of 8 Limbs” utilising every aspect of fighting. This means that kicking, punching, knees, elbows and grappling are all legal within its ruleset, making it the most fundamentally demanding combat sport. Its ruleset would be much less limiting to the likes of boxing, wrestling and kickboxing, instead combining them all under one roof to create the most realistic simulation of fighting.
        </p>

        <h3>What are the rules?</h3>
        <p>
The ruleset primarily within the mainstream MMA bodies such as the UFC are full contact contests consisting of 3-5, 5-minute rounds. 3 round fights are often for lower ranking contenders while 5 rounds are often reserved for champions or main event spots. You can win via TKO, Submission and Decision from the 3 Judges’ scorecards. Prohibited attacks are knee of foot strikes to the head of a grounded opponent, eye poking, below the belt attacks, biting and gouging.
        </p>

        <h3>What is the UFC?</h3>
        <p>
The Ultimate Fighting Championship is the world’s leading MMA organisation. Starting from a no rules “anything goes” contest The UFC faced much controversy and difficulty developing as a brand, with political backlash from senators like John McCain nearly leading to the outright ban to the sport. In the early 2000’s the ruleset we know today would be developed and would lead to MMA’s sanctioning as a legitimate sport. Still facing financial struggle, the UFC would dive into reality TV, creating the show The Ultimate Fighter, which was a tournament style episodic show following to the day to day lives of the fighters competing against each other as they live in a shared space. This show would become widely popular and save the organisation from effectively dying, sparking now over 30 seasons of the show.
        </p>

        <h3>How has it effected Glasgow?</h3>
        <p>
The UFC’s significant global growth has influenced the development of Mixed Martial Arts (MMA) in Glasgow. Dedicated MMA gyms such as the Griphouse, founded 5 years after the UFC’s sanctioning would emerge, producing fighters who would eventually compete in the UFC and drive-up interest in the sport. This would lead to major MMA events in Glasgow after the UFC’s inaugural 2015 Fight Night show in the OVO Hydro showing Scotland’s interest and marketability. MMA Gyms like the Griphouse would develop fighters like Robert Whiteford, emerging as Scotland’s first ever UFC fighter during the sport’s 2014 boom. This would inspire later Glasgow talents like Paul Craig and Joanne Wood to enter the sport and continue to drive further interest towards Glasgow’s untapped potential.
        </p>

    </div>
</div>


<div class="section white reveal">
    <iframe class="full-width" src="https://uploads.knightlab.com/storymapjs/5f7f3c309f2b408b860e120e651e105c/mma/index.html" height="800"></iframe>
</div>


<div class="section red reveal">
    <div class="container split reverse">

        <div class="text">
            <p>
From 1993 until 2025 there has been a significant growth for the UFC’s capacity to put out events. With a combination of demand, interest and budget the UFC had a small growth from the 90’s to the mid 2000’s before its popularity began to skyrocket past 2005, going from 3-5 yearly shows to 43 by 2014. (Per Wikipedia) 
            </p>
        </div>

        <div class="visual visual-box">
            <div class="flourish-embed" data-src="visualisation/27772716"></div>
        </div>

    </div>
</div>


<div class="section white reveal">
    <div class="container split">

        <div class="visual visual-box">
            <div class="flourish-embed" data-src="visualisation/27910112"></div>
        </div>

        <div class="text">
            <p>
  This increase has had a strong effect on events taking place across the world including Glasgow resulting in the city receiving its very own UFC events in 2015 and 2017. These events both brought in over 10,000 spectators and approximately £1.5 million in their gate earnings alone, showcasing the marketability Glasgow has for largescale combat sports events. This is important as it has resulted in an increase in major MMA events from other large organisations like PFL and Cage Warriors, making Glasgow a much more frequent city to host. Cage Warriors events have become more frequent in Glasgow in the past few years hosting multiple events in 2024, and now having more scheduled for 2026. This info comes from the sporting news, Wikipedia, Cage Warriors and PFL. 
          </p>
        </div>

    </div>
</div>


<div class="section red reveal">
    <div class="container split reverse">

        <div class="text">
            <p>
 What’s most interesting about Glasgow’s MMA growth is its developing infrastructure. As Glasgow’s Martial Arts economy continuous to develop its important to note that it is still very much grassroots. Interestingly, Glasgow’s independence in the martial arts seen is impressive as out of its 65 registered martial arts schools, 51 of these are single-owner operations which is 78% of all martial arts schools in Glasgow. These statistics from Rentechdigital find as of October 15, 2025, 14 martial arts schools in Glasgow belong to larger chain brands which is only 21.54%. Glasgow’s youthful growth in the MMA scene is even more significant when looking their average gym age of 5 years and 7 months. This staggering figure helps us understand how the UFC’s recent impact on the city has continued to support its growth, with new schools springing up frequently.  
           </p>
        </div>

        <div class="visual visual-box">
            <div class="flourish-embed" data-src="visualisation/27604280"></div>
        </div>

    </div>
</div>


<div class="section white reveal">
    <div class="container split">

        <div class="visual visual-box">
            <div class="flourish-embed" data-src="visualisation/27604010"></div>
        </div>

        <div class="text">
            <p>
These gyms across Glasgow have had a 2.94% increase from 2023 as more quickly begin to open and more events take place. Its development of the Scottish Mixed Martial Arts Federation (SCOT-MMAF) in 2017 has greatly encouraged this growth as it allows for a much greater opportunity for sanctioned competition to take place within Scotland. MMA organisations like BMF have been able to operate within Scotland and give spotlight to its talent, while local athletes from Glasgow and other Scottish cities something to work towards. Lastly this has opened the opportunity to develop being an MMA Trainer or Fighter as a possible career option, as the economy becomes recognised more and more a s a legitimate sport, athletes and trainers can dedicate much more of their time in developing their skills.  
            </p>
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
