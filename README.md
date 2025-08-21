<!DOCTYPE html>
<html>
<head>
    <title>Mountain Group Festive Introduction</title>
    <style>
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            min-height: 100vh;
            background: linear-gradient(120deg, #ffe3e3 0%, #fffbe8 100%);
            /* Festive confetti background */
            background-image:
            url('https://www.transparenttextures.com/patterns/confetti.png'),
            radial-gradient(circle at 20% 30%, #ffd54f 0%, transparent 60%),
            radial-gradient(circle at 80% 70%, #ff7043 0%, transparent 60%),
            radial-gradient(circle at 50% 90%, #ad1457 0%, transparent 70%);
            background-blend-mode: lighten, normal;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 0 16px;
        }
        .group-header {
            text-align: center;
            margin-top: 40px;
            color: #d84315;
            font-size: 2.7em;
            font-weight: 800;
            letter-spacing: 2px;
            text-shadow: 0 2px 12px rgba(216,67,21,0.18);
            position: relative;
        }
        .group-header::after {
            content: "🎉";
            font-size: 1.2em;
            margin-left: 12px;
            vertical-align: middle;
            animation: bounce 1s infinite alternate;
        }
        @keyframes bounce {
            to { transform: translateY(-8px);}
        }
        .ganpati-img {
            display: block;
            margin: 32px auto 24px auto;
            border-radius: 18px;
            box-shadow: 0 4px 24px rgba(216,67,21,0.18);
            max-width: 340px;
            width: 100%;
            border: 4px solid #ffd54f;
        }
        .glimpse-section {
            margin-top: 48px;
        }
        .glimpse-title {
            font-size: 2em;
            color: #ad1457;
            text-align: center;
            margin-bottom: 24px;
            font-weight: 700;
            letter-spacing: 1px;
            position: relative;
        }
        .glimpse-title::before,
        .glimpse-title::after {
            content: "✨";
            font-size: 1.2em;
            margin: 0 8px;
        }
        .glimpse-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 22px;
        }
        .glimpse-item {
            background: #fff8e1;
            border-radius: 14px;
            box-shadow: 0 2px 16px rgba(216,67,21,0.10);
            overflow: hidden;
            transition: transform 0.18s, box-shadow 0.18s;
            border: 2.5px solid #ffd54f;
            position: relative;
        }
        .glimpse-item::before {
            content: "🎊";
            position: absolute;
            top: 8px;
            left: 8px;
            font-size: 1.1em;
            opacity: 0.7;
        }
        .glimpse-item:hover {
            transform: scale(1.04) rotate(-2deg);
            box-shadow: 0 6px 24px rgba(216,67,21,0.18);
            border-color: #ff7043;
        }
        .glimpse-item img,
        .glimpse-item video {
            width: 100%;
            display: block;
            border-bottom: 1.5px solid #ffe082;
        }
        .glimpse-caption {
            padding: 12px 10px;
            font-size: 1em;
            color: #d84315;
            text-align: center;
            font-weight: 600;
            background: linear-gradient(90deg,#fffde7 60%,#ffe0b2 100%);
            border-radius: 0 0 12px 12px;
        }
        @media (max-width: 600px) {
            .group-header { font-size: 2em; }
            .glimpse-title { font-size: 1.3em; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="group-header">Mountain Group</div>
        <img class="ganpati-img" src="https://images.unsplash.com/photo-1502086223501-7ea6ecd79368?auto=format&fit=crop&w=600&q=80" alt="Ganpati">
        <div class="glimpse-section">
            <div class="glimpse-title">Glimpse of Festive Years</div>
            <div class="glimpse-gallery">
                <div class="glimpse-item">
                    <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=400&q=80" alt="Event 1">
                    <div class="glimpse-caption">Ganpati Celebration 2024 🎈</div>
                </div>
                <div class="glimpse-item">
                    <video controls muted poster="https://images.unsplash.com/photo-1465101046530-73398c7f28ca?auto=format&fit=crop&w=400&q=80">
                        <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
                        Your browser does not support the video tag.
                    </video>
                    <div class="glimpse-caption">Best Festive Clicks 📸</div>
                </div>
                <div class="glimpse-item">
                    <img src="https://images.unsplash.com/photo-1508672019048-805c876b67e2?auto=format&fit=crop&w=400&q=80" alt="Event 2">
                    <div class="glimpse-caption">Mountain Magic 🏔️</div>
                </div>
                <div class="glimpse-item">
                    <video controls muted poster="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80">
                        <source src="https://www.w3schools.com/html/movie.mp4" type="video/mp4">
                        Your browser does not support the video tag.
                    </video>
                    <div class="glimpse-caption">Group Singing Night 🎶</div>
                </div>
                <div class="glimpse-item">
                    <img src="https://images.unsplash.com/photo-1465101178521-c1a4c8a0b3ec?auto=format&fit=crop&w=400&q=80" alt="Event 3">
                    <div class="glimpse-caption">Picnic Fun 2020 🥳</div>
                </div>
                <div class="glimpse-item">
                    <img src="https://images.unsplash.com/photo-1500534314209-a25ddb2bd429?auto=format&fit=crop&w=400&q=80" alt="Event 4">
                    <div class="glimpse-caption">Cultural Night Extravaganza 💃</div>
                </div>
                <div class="glimpse-item"></div>
                    <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9?auto=format&fit=crop&w=400&q=80" alt="Event 5">
                    <div class="glimpse-caption">Dance Performance 2022 💃</div>
                </div>
                <div class="glimpse-item">
                    <img src="https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e?auto=format&fit=crop&w=400&q=80" alt="Event 6">
                    <div class="glimpse-caption">Family Gathering 2023 👨‍👩‍👧‍👦</div>
                </div>
                <div class="glimpse-item">
                    <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=400&q=80" alt="Event 7">
                    <div class="glimpse-caption">Memorable Moments 🌟</div>
                </div>
            </div>
        </div>
    </div>
</body></div>
</html>
<div style="width:100%;text-align:center;margin:48px 0 32px 0;">
    <a href="https://docs.google.com/forms/d/e/1FAIpQLSdl2KTyULymW6zRVk4Xv-ox8Sfe1R9bea6HzHxeh9FsABjt3g/viewform?usp=header"
       target="_blank"
       style="
           display:inline-block;
           background: linear-gradient(90deg,#ffd54f 40%,#ff7043 100%);
           color: #ad1457;
           font-size: 1.35em;
           font-weight: bold;
           padding: 18px 38px;
           border-radius: 32px;
           box-shadow: 0 4px 18px rgba(216,67,21,0.13);
           text-decoration: none;
           letter-spacing: 1px;
           transition: transform 0.18s, box-shadow 0.18s;
           position: relative;
       "
       onmouseover="this.style.transform='scale(1.07) rotate(-2deg)';this.style.boxShadow='0 8px 32px rgba(216,67,21,0.18)';"
       onmouseout="this.style.transform='';this.style.boxShadow='0 4px 18px rgba(216,67,21,0.13)';"
    >
        <span style="font-size:1.2em;vertical-align:middle;">📝</span>
        <span style="margin:0 10px;">Fill Our Festive Feedback Form!</span>
        <span style="font-size:1.2em;vertical-align:middle;">✨</span>
    </a>
</div></div>
