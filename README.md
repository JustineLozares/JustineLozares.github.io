<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Events and Blogs</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
        }

        nav {
            background-color: #eee;
            padding: 1em;
        }

        nav a {
            text-decoration: none;
            color: #333;
            margin-right: 1em;
            font-weight: bold;
        }

        section {
            padding: 2em;
        }

        .event-card,
        .blog-post {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1em;
            margin-bottom: 1em;
        }

        .video-container {
            position: relative;
            padding-bottom: 56.25%;
            overflow: hidden;
            border-radius: 8px;
        }

        iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <h1>Your Events and Blogs</h1>
    </header>

    <nav>
        <a href="#events">Events</a>
        <a href="#blogs">Blogs</a>
    </nav>

    <section id="events">
        <h2>Upcoming Events</h2>

        <div class="event-card">
            <h3>Trimex Colleges Happy Kids</h3>
            <p>Date: November 22, 2023</p>
            <p>Location: Binan City Senior High School-San Antonio Campus</p>
            <p>Description: A Feast for Happy Tummies! Chop Suey, a colorful medley of veggies and flavors, paired perfectly with those crispy, golden Chicken Fingers. It wasn’t just a meal; it was a symphony of taste and satisfaction that left smiles on every face.</p>
            <div class="video-container">
                <iframe src="https://www.facebook.com/TrimexCollegesHappyKids/videos/851655926642123" allowfullscreen></iframe>
            </div>
        </div>

        <div class="event-card">
            <h3>Trimex Colleges Happy Kids</h3>
            <p>Date: November 23, 2023</p>
            <p>Location:  Binan City Senior High School-San Antonio Campus</p>
            <p>Description: Together, we can make an even bigger impact! Whether it's through a donation, your time as a volunteer, or simply sharing awareness about this program, YOU can help us ensure no child goes to bed hungry.</p>
            <div class="video-container">
                <iframe src="https://www.facebook.com/reel/220127191106742" allowfullscreen></iframe>
            </div>
        </div>
    </section>

    <section id="blogs">
        <h2>Latest Blog Posts</h2>

        <div class="blog-post">
            <h3>Blog Post Title 1</h3>
            <p>Published on: [Publication Date]</p>
            <p>Author: [Author Name]</p>
            <p>Excerpt: [Brief Blog Post Excerpt]</p>
            <a href="#">Read More</a>
        </div>

        <div class="blog-post">
            <h3>Blog Post Title 2</h3>
            <p>Published on: [Publication Date]</p>
            <p>Author: [Author Name]</p>
            <p>Excerpt: [Brief Blog Post Excerpt]</p>
            <a href="#">Read More</a>
        </div>
    </section>

    <footer>
        &copy; 2023 Your Events and Blogs
    </footer>
</body>

</html>
