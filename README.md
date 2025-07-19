<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Letter for Wifey</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;700&family=Montserrat:wght@300;400;600&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background-color: #ffecf1;
            font-family: 'Montserrat', sans-serif;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }
        
        .love-letter {
            background-color: white;
            width: 100%;
            max-width: 600px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            position: relative;
            padding: 40px;
            transform-style: preserve-3d;
        }
        
        .love-letter:before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 10px;
            background: linear-gradient(90deg, #ff6b8b, #ff8e9e);
        }
        
        .letter-header {
            text-align: center;
            margin-bottom: 30px;
        }
        
        h1 {
            font-family: 'Dancing Script', cursive;
            color: #ff6b8b;
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .date {
            font-weight: 300;
            color: #888;
            margin-bottom: 20px;
        }
        
        .letter-content {
            line-height: 1.8;
            font-size: 1rem;
            position: relative;
        }
        
        .letter-content p {
            margin-bottom: 20px;
        }
        
        .highlight {
            color: #ff6b8b;
            font-weight: 600;
        }
        
        .song-container {
            background-color: #fff5f7;
            border-left: 3px solid #ff6b8b;
            padding: 15px;
            margin: 20px 0;
            border-radius: 0 5px 5px 0;
        }
        
        .song-title {
            font-weight: 600;
            margin-bottom: 5px;
        }
        
        .song-artist {
            font-style: italic;
            font-size: 0.9rem;
        }
        
        .signature {
            font-family: 'Dancing Script', cursive;
            font-size: 1.8rem;
            text-align: right;
            margin-top: 30px;
            color: #ff6b8b;
        }
        
        .heart {
            color: #ff6b8b;
            animation: heartbeat 1.5s infinite;
            display: inline-block;
        }
        
        @keyframes heartbeat {
            0% { transform: scale(1); }
            25% { transform: scale(1.1); }
            50% { transform: scale(1); }
            75% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        
        .envelope {
            position: absolute;
            top: -30px;
            right: -30px;
            width: 100px;
            height: 100px;
            background-color: #ff8e9e;
            transform: rotate(45deg);
            border-radius: 0 0 0 10px;
            opacity: 0.3;
            z-index: -1;
        }
        
        @media (max-width: 600px) {
            .love-letter {
                padding: 30px 20px;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="love-letter">
        <div class="envelope"></div>
        <div class="letter-header">
            <h1>My Dearest Wifey</h1>
            <div class="date">Today and Always</div>
        </div>
        
        <div class="letter-content">
            <p>I love you so much <span class="highlight">wifeyyy</span> <span class="heart">❤</span></p>
            
            <p><span class="highlight">Mag aantay ako kahit gano katagal.</span> My favorite song that reminds me of you is:</p>
            
            <div class="song-container">
                <div class="song-title">14</div>
                <div class="song-artist">Silent Sanctuary</div>
            </div>
            
            <p>Pangako ko sa sarili ko na <span class="highlight">aantayin kita</span> and di ko sasayangin yung chance na ibibigay mo. <span class="highlight">Hinding hindi kita pababayaan</span> kasi mahal na mahal kita. Ayoko ng mawala ka pa ulit.</p>
            
            <p><span class="highlight">Mahal na mahal na mahal kita wifeyyy!</span> Can't wait to see you soon <span class="heart">❤</span></p>
        </div>
        
        <div class="signature">
            <p>Mwaaaa <span class="heart">❤</span></p>
            <p>Yours always</p>
        </div>
    </div>
</body>
</html>
