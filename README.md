# index.html.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fun Meme Page</title>
    <style>
        /* General styling */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #f9f9f9, #1c1c1c);
            color: #222;
            transition: background 0.5s, color 0.5s;
        }

        header {
            text-align: center;
            padding: 50px 20px;
            background-color: rgba(0, 0, 0, 0.7);
            color: #fff;
        }

        h1 {
            font-size: 3em;
            margin: 0;
        }

        h2 {
            color: #f0c040;
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: 0 auto;
        }

        /* Meme gallery */
        .meme-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .meme-gallery img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
            transition: transform 0.3s, filter 0.3s;
        }

        .meme-gallery img:hover {
            transform: scale(1.05);
            filter: brightness(1.2);
        }

        /* About section */
        .about {
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 40px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: rgba(0,0,0,0.7);
            color: #fff;
        }

        /* Toggle dark/light mode */
        .dark-mode {
            background: linear-gradient(to bottom, #1c1c1c, #f9f9f9);
            color: #f0f0f0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Fun Meme Page!</h1>
        <p>All the memes, all the laughs, all in one place</p>
    </header>

    <section class="about">
        <h2>About Me</h2>
        <p>Hello! I'm just someone who loves memes and having fun on the internet. This page is a collection of my favorite funny moments, silly images, and whatever else makes life a little brighter. Enjoy your stay!</p>
    </section>

    <section>
        <h2>Meme Gallery</h2>
        <div class="meme-gallery">
            <img src="https://i.imgur.com/W3XQZ9U.jpeg" alt="Meme 1">
            <img src="https://i.imgur.com/8Km9tLL.jpeg" alt="Meme 2">
            <img src="https://i.imgur.com/2F4E1zz.jpeg" alt="Meme 3">
            <img src="https://i.imgur.com/XKJQv8q.jpeg" alt="Meme 4">
            <img src="https://i.imgur.com/3Y3f1Uv.jpeg" alt="Meme 5">
        </div>
    </section>

    <footer>
        &copy; 2025 Meme Master. Keep laughing!
    </footer>

    <script>
        // Optional: simple dark/light toggle
        document.body.addEventListener('dblclick', () => {
            document.body.classList.toggle('dark-mode');
        });
    </script>
</body>
</html>
