<style>
        /* CSS Variables for Theming */
        :root {
            --bg-color-light: #f8f8f8;
            --text-color-light: #333;
            --link-color-light: #007acc;
            --header-bg-light: #fff;
            --header-text-light: #333;
            --border-color-light: #ddd;
            --code-bg-light: #f0f0f0;
            --code-text-light: #333;

            --bg-color-dark: #1e1e1e;
            --text-color-dark: #f0f0f0;
            --link-color-dark: #61dafb;
            --header-bg-dark: #2a2a2a;
            --header-text-dark: #f0f0f0;
            --border-color-dark: #444;
            --code-bg-dark: #2c2c2c;
            --code-text-dark: #f0f0f0;

            /* Default to light theme */
            --bg-color: var(--bg-color-light);
            --text-color: var(--text-color-light);
            --link-color: var(--link-color-light);
            --header-bg: var(--header-bg-light);
            --header-text: var(--header-text-light);
            --border-color: var(--border-color-light);
            --code-bg: var(--code-bg-light);
            --code-text: var(--code-text-light);
        }

        body.dark-theme {
            --bg-color: var(--bg-color-dark);
            --text-color: var(--text-color-dark);
            --link-color: var(--link-color-dark);
            --header-bg: var(--header-bg-dark);
            --header-text: var(--header-text-dark);
            --border-color: var(--border-color-dark);
            --code-bg: var(--code-bg-dark);
            --code-text: var(--code-text-dark);
        }

        /* General Styles */
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: var(--bg-color);
            color: var(--text-color);
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 0 20px;
        }

        /* Header */
        header {
            background-color: var(--header-bg);
            padding: 20px 0;
            border-bottom: 1px solid var(--border-color);
            text-align: center;
            margin-bottom: 30px;
            transition: background-color 0.3s ease, border-color 0.3s ease;
        }
            position: fixed;
            top: 15px;
            right: 15px;
            padding: 8px 12px;
            background-color: var(--header-bg);
            color: var(--header-text);
            border: 1px solid var(--border-color);
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.9em;
            transition: background-color 0.3s ease, color 0.3s ease, border-color 0.3s ease;
        }

        .theme-switcher:hover {
            opacity: 0.8;
        }


        /* Main Content */
        main {
            display: block; /* For older browsers */
        }

        article {
            margin-bottom: 40px;
            padding-bottom: 20px;
            border-bottom: 1px solid var(--border-color);
            transition: border-color 0.3s ease;
        }

        article:last-child {
            border-bottom: none;
        }

        article h2 {
            margin-top: 0;
            font-size: 2em;
        }

        article h2 a {
            color: var(--text-color);
            text-decoration: none;
            transition: color 0.3s ease;
        }

        article h2 a:hover {
            color: var(--link-color);
        }

        article .meta {
            font-size: 0.9em;
            color: #777; /* This color might need adjustment for dark theme or use a variable */
            margin-bottom: 10px;
        }

        body.dark-theme article .meta {
            color: #aaa;
        }

        article p {
            margin-bottom: 15px;
        }

        a {
            color: var(--link-color);
            text-decoration: none;
            transition: color 0.3s ease;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
            border-top: 1px solid var(--border-color);
            font-size: 0.9em;
            color: #777; /* This color might need adjustment for dark theme or use a variable */
            transition: border-color 0.3s ease;
        }

        body.dark-theme footer {
            color: #aaa;
        }

        /* Code Blocks */
        pre {
            background-color: var(--code-bg);
            color: var(--code-text);
            padding: 15px;
            overflow-x: auto;
            border-radius: 5px;
            font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace;
            font-size: 0.9em;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        code {
            font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace;
            background-color: var(--code-bg);
            color: var(--code-text);
            padding: 2px 4px;
            border-radius: 3px;
            font-size: 0.9em;
        }

        pre code {
            padding: 0;
            background-color: transparent;
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            header h1 {
                font-size: 2em;
            }
            article h2 {
                font-size: 1.7em;
            }
            .container {
                padding: 0 15px;
            }
        }

    </style>
# My First Blog Post

<p class="meta">Published on June 1, 2025 by Author Name</p>

This is the introduction to my first blog post. It's about something interesting and engaging. I hope you enjoy reading it and come back for more content soon!

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
