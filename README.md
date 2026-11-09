<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sam & Brian's Wedding Details</title>
    <style>
        :root {
            --bg-color: #121212;
            --card-bg: #1e1e1e;
            --accent-color: #ffffff;
            --text-color: #e0e0e0;
            --muted-text: #a0a0a0;
            --border-color: #333333;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 600px;
            margin: 40px auto;
            background: var(--card-bg);
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            border: 1px solid var(--border-color);
        }

        header {
            text-align: center;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 30px;
            margin-bottom: 30px;
        }

        h1 {
            font-size: 2.2rem;
            color: var(--accent-color);
            margin: 0 0 10px 0;
            font-weight: 300;
            letter-spacing: 1px;
        }

        h2 {
            font-size: 1.2rem;
            color: var(--accent-color);
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-top: 30px;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 5px;
        }

        .date-location {
            font-size: 1.1rem;
            color: var(--muted-text);
            margin: 0;
        }

        .heart {
            color: #ff4b4b;
            font-size: 1.2rem;
        }

        .timeline {
            list-style: none;
            padding: 0;
        }

        .timeline-item {
            margin-bottom: 15px;
            padding-left: 15px;
            border-left: 2px solid var(--accent-color);
        }

        .timeline-time {
            font-weight: bold;
            color: var(--accent-color);
        }

        ul {
            padding-left: 20px;
        }

        li {
            margin-bottom: 8px;
        }

        .alert-box {
            background-color: rgba(255, 255, 255, 0.05);
            border-radius: 6px;
            padding: 15px;
            margin: 15px 0;
            font-size: 0.95rem;
        }

        .dress-code {
            border: 1px dashed var(--muted-text);
            padding: 15px;
            margin-top: 20px;
            border-radius: 6px;
            background-color: #0a0a0a;
        }

        a {
            color: var(--accent-color);
            text-decoration: underline;
        }

        a:hover {
            opacity: 0.8;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-top: 15px;
        }

        .contact-card {
            background: rgba(255, 255, 255, 0.03);
            padding: 15px;
            border-radius: 6px;
            text-align: center;
            border: 1px solid var(--border-color);
        }

        .footer-note {
            text-align: center;
            font-size: 0.85rem;
            color: var(--muted-text);
            margin-top: 40px;
            border-top: 1px solid var(--border-color);
            padding-top: 20px;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Sam & Brian</h1>
            <p class="date-location">Thursday, December 31, 2026</p>
            <p class="date-location">Apache Lake, Arizona</p>
            <p style="margin-top: 15px; font-style: italic;">Come watch us say "I do" at dusk, and celebrate with us into 2027! <span class="heart">&lt;3</span></p>
        </header>

        <section>
            <h2>The Night</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <span class="timeline-time">Dusk</span> — Small hike to the ceremony. Jake will be officiating!
                </div>
                <div class="timeline-item">
                    <span class="timeline-time">Evening</span> — Dinner and bonfire. Laid-back, come as you are.
                </div>
                <div class="timeline-item">
                    <span class="timeline-time">Midnight & Beyond</span> — Party straight into 2027!
                </div>
            </div>
        </section>

        <section>
            <h2>Getting There</h2>
            <p>Our favorite way in is the <strong>Tortilla Flat side</strong>. This is an incredibly beautiful drive, but <strong>4WD is highly recommended</strong>. You can make it without if you drive really, really slow and the road isn't washed out... but you can also arrive from the <strong>Roosevelt Lake side</strong> if needed.</p>
            
            <ul>
                <li><a href="https://apachelake.com/" target="_blank">Apache Lake Marina & Resort Website</a></li>
                <li><strong>Meeting Point / Campsite Map Pin:</strong> Coming soon</li>
                <li><strong>Best Time to Arrive:</strong> Coming soon</li>
            </ul>

            <div class="alert-box">
                <strong>Carpooling Highly Advised!</strong> I created a group chat so that everyone can coordinate and offer or ask for rides. <br>
                <em>Link coming soon.</em>
            </div>
        </section>

        <section>
            <h2>Camping & Lodging</h2>
            <p>We're camping on the beach, so plan to stay the night! It's a relaxed, party-friendly spot with a bar, restaurant, and convenience store right next door. They also have an RV Park and hotel rooms for rent. Whatever you want to do is fine with us!</p>
            <p><em>Note: Desert nights in late December get very cold, so please make a solid plan!</em></p>
            
            <h3>What to bring:</h3>
            <ul>
                <li>Warm layers for the bonfire</li>
                <li>Shoes you can walk/dance in on sand and dirt</li>
                <li>Headlamp, flashlight, or a fully charged phone</li>
                <li>Camp chair</li>
            </ul>

            <div class="dress-code">
                <strong>Ceremony & Photos Dress Code:</strong><br>
                "We kindly invite you to wear black or very dark clothing to help us curate a formal, monochromatic look."<br>
                <small style="color: var(--muted-text);">Suit rental/purchase link coming soon.</small>
            </div>
        </section>

        <section>
            <h2>RSVP</h2>
            <p>Let us know if you're coming by... December? Feel free to invite whoever; we will try to accommodate as many people as possible.</p>
            <p>I am sorry this is not a lot of notice, so absolutely no hard feelings if you can't make it! <span class="heart">&lt;3</span></p>
            <p style="font-size: 0.9rem; font-style: italic; color: var(--muted-text);">(...Unless you are Jordan Glidewell...)</p>
        </section>

        <section>
            <h2>Questions?</h2>
            <p>Text or call Sam or Brian with any questions. (Probably Brian if you want a quicker response... 😅😂)</p>
            
            <div class="contact-grid">
                <div class="contact-card">
                    <strong>Brian</strong><br>
                    <a href="tel:4805995066">480-599-5066</a>
                </div>
                <div class="contact-card">
                    <strong>Sam</strong><br>
                    <a href="tel:6024781743">602-478-1743</a>
                </div>
            </div>
        </section>

        <div class="footer-note">
            This page will be updated as plans come together — check back soon!
        </div>
    </div>

</body>
</html>
