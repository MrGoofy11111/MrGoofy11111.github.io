<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Some random page i'll nevee update</title>
    <style>
        /* Base Styles & Typography */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
            padding: 20px;
        }
        a {
            color: #0066cc;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }

        /* Layout Container */
        .container {
            max-width: 1100px;
            margin: 0 auto;
        }

        /* Header Section */
        header {
            background-color: #fff;
            padding: 30px;
            text-align: center;
            border-bottom: 3px solid #333;
            margin-bottom: 20px;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        /* Navigation Menu */
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        nav a {
            font-weight: bold;
            color: #555;
        }

        /* Main Workspace: Body split into Main Feed and Sidebar */
        .main-layout {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        /* Blog Posts Area */
        main {
            flex: 3;
        }
        article {
            background-color: #fff;
            padding: 25px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        article h2 {
            margin-bottom: 10px;
        }
        .post-meta {
            font-size: 0.85rem;
            color: #777;
            margin-bottom: 15px;
        }

        /* Sidebar Section */
        aside {
            flex: 1;
            background-color: #fff;
            padding: 25px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            height: fit-content;
        }
        aside h3 {
            margin-bottom: 15px;
            border-bottom: 2px solid #ddd;
            padding-bottom: 5px;
        }
        aside ul {
            list-style: none;
        }
        aside li {
            margin-bottom: 10px;
        }

        /* Footer Section */
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 20px;
            color: #777;
            font-size: 0.9rem;
        }

        /* Responsive Breakpoint for Tablets/Desktops */
        @media (min-width: 768px) {
            .main-layout {
                flex-direction: row;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Blog Header & Nav -->
        <header>
            <h1>The Dev Journal</h1>
            <p>Thoughts on code, design, and web development.</p>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Articles</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </header>

        <!-- Main Structural Wrapper -->
        <div class="main-layout">
            
            <!-- Blog Posts Stream -->
            <main>
                <article>
                    <h2><a href="#">Getting Started with HTML5 Semantic Tags</a></h2>
                    <div class="post-meta">Published on July 27, 2026 by Alex Carter</div>
                    <p>Semantic HTML tags clearly describe their meaning in a human- and machine-readable way. Elements like header, footer, article, and section make your site highly readable to search engine crawlers and screen readers alike...</p>
                    <br>
                    <a href="#" class="read-more">Read More &rarr;</a>
                </article>

                <article>
                    <h2><a href="#">Why I Switched Back to Pure CSS Flexbox</a></h2>
                    <div class="post-meta">Published on July 15, 2026 by Alex Carter</div>
                    <p>While heavy UI frameworks have their place, relying on clean, native CSS Flexbox and Grid allows you to build faster layouts with absolute zero bloat. Let's look at a quick layout implementation strategy...</p>
                    <br>
                    <a href="#" class="read-more">Read More &rarr;</a>
                </article>
            </main>

            <!-- Sidebar -->
            <aside>
                <h3>About Me</h3>
                <p>Hi, I'm Alex. A self-taught frontend developer building lightweight experiences on the web.</p>
                <br>
                <h3>Recent Links</h3>
                <ul>
                    <li><a href="#">MDN Web Docs</a></li>
                    <li><a href="#">CSS-Tricks Layouts</a></li>
                    <li><a href="#">W3Schools Layout Reference</a></li>
                </ul>
            </aside>

        </div>

        <!-- Footer -->
        <footer>
            <p>&copy; 2026 The Dev Journal. Built from scratch with pure HTML & CSS.</p>
        </footer>
    </div>

</body>
</html>
