<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Umilog | Journal</title>
    <style>
        :root {
            --bg-color: #fcfbf9;
            --text-color: #1a1a1a;
            --accent-color: #5a625a;
            --border-color: #e6e4e0;
            --date-color: #8c8882;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Georgia, serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.7;
            margin: 0;
            padding: 40px 20px;
        }

        .container {
            max-width: 650px;
            margin: 0 auto;
        }

        header {
            border-bottom: 2px solid var(--text-color);
            padding-bottom: 20px;
            margin-bottom: 60px;
            display: flex;
            justify-content: space-between;
            align-items: flex-end;
        }

        header h1 {
            font-family: Georgia, serif;
            font-size: 2.2rem;
            font-weight: 700;
            margin: 0;
            letter-spacing: -0.5px;
        }

        .subtitle {
            font-size: 0.9rem;
            color: var(--accent-color);
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-top: 5px;
        }

        .log-entry {
            margin-bottom: 50px;
            padding-bottom: 40px;
            border-bottom: 1px dashed var(--border-color);
        }

        .log-entry:last-child {
            border-bottom: none;
        }

        .meta {
            font-size: 0.85rem;
            color: var(--date-color);
            font-family: monospace;
            margin-bottom: 15px;
            display: flex;
            gap: 15px;
        }

        .log-title {
            font-family: Georgia, serif;
            font-size: 1.4rem;
            font-weight: 600;
            margin: 0 0 15px 0;
        }

        .log-title a {
            color: var(--text-color);
            text-decoration: none;
        }

        .log-title a:hover {
            color: var(--accent-color);
            text-decoration: underline;
        }

        p {
            font-size: 1.05rem;
            margin: 0 0 20px 0;
        }

        footer {
            margin-top: 100px;
            font-size: 0.8rem;
            text-align: center;
            color: var(--date-color);
            font-family: monospace;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <div>
                <h1>Umilog</h1>
                <div class="subtitle">The Genius Biographical Log</div>
            </div>
        </header>

        <main>
            <!-- Entry 1 -->
            <article class="log-entry">
                <div class="meta">
                    <span>[ LOG_001 ]</span>
                    <span>2026-11-05</span>
                </div>
                <h2 class="log-title"><a href="log-001.html">The First Entry: Initiating the Log Base</a></h2>
                <p>Setting up the primary deployment structure for the publication on GitHub Pages. This space will serve as the browser-native terminal for tracking profiles, insights, and structural developments.</p>
            </article>
        </main>

        <footer>
            &copy; 2026 Umilog. Secure Web3 Journal.
        </footer>
    </div>

</body>
</html>
