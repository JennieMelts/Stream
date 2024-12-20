
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stream Schedule Template</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #282c34, #3a3f47);
            margin: 0;
            padding: 0;
            color: white;
        }

        .schedule-container {
            max-width: 900px;
            margin: 30px auto;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(90deg, #39FF14, #BA55D3);
            text-align: center;
            padding: 30px 15px;
        }

        .header h1 {
            margin: 0;
            font-size: 3rem;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
        }

        .schedule {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2px;
            background: linear-gradient(135deg, #444, #555);
        }

        .day, .time-slot {
            background: #2c2c2c;
            background-image: linear-gradient(135deg, rgba(255, 255, 255, 0.1) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.1) 50%, rgba(255, 255, 255, 0.1) 75%, transparent 75%, transparent);
            background-size: 15px 15px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            color: white;
            padding: 20px;
            text-align: center;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
            font-weight: bold;
        }

        .day {
            font-size: 1.3rem;
            background: linear-gradient(135deg, #39FF14, #228B22);
        }

        .time-slot {
            font-size: 1.1rem;
            background: linear-gradient(135deg, #BA55D3, #8A2BE2);
        }

        .footer {
            background: linear-gradient(90deg, #8A2BE2, #39FF14);
            text-align: center;
            padding: 15px;
            font-size: 1rem;
        }

        .footer a {
            color: #39FF14;
            text-decoration: none;
            font-weight: bold;
        }

        .footer a:hover {
            text-decoration: underline;
        }

        @media (max-width: 600px) {
            .schedule {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <div class="schedule-container">
        <div class="header">
            <h1>My Stream Schedule</h1>
        </div>

        <div class="schedule">
            <div class="day">Monday</div>
            <div class="time-slot"> Podcast With The Rinsinator 6:30pm</div>

            <div class="day">Tuesday</div>
            <div class="time-slot">Time: N/A</div>

            <div class="day">Wednesday</div>
            <div class="time-slot">Time: N/A</div>

            <div class="day">Thursday</div>
            <div class="time-slot">Time: N/A</div>

            <div class="day">Friday</div>
            <div class="time-slot">Time: 6 PM - 11 PM</div>

            <div class="day">Saturday</div>
            <div class="time-slot">Time: 6 PM - 11 PM</div>

            <div class="day">Sunday</div>
            <div class="time-slot">Time: Maybe?</div>
        </div>

        <div class="footer">
            <p>Follow me on <a href="https://www.twitch.tv/jenniemelts">Twitch</a> | <a href="https://www.youtube.com/@JennieMelts">YouTube</a> | <a href="https://x.com/MeltsJennie">Twitter</a></p>
        </div>
    </div>

</body>
</html>
