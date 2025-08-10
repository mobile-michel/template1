Goal: build a one-page portfolio website.

Tech: Nue v1.0.0-RC.4 with Bun

Doc: https://nuejs.org/docs/

Content: Markdown files

Layout: HTML files in /@global or /@library

Styling: plain CSS files in /@global or /@library

Scripting: plain JavaScript files in /@global or /@library

Do not put css or js inside content or layout files.

Files & folders:

- /@global/layout.html (header & footer slots)
- /@global/style.css (basic stylesheet)
- /@library
- /images/favicon.png
- /404.md
- /about.md
- /index.md
- /netlify.toml
- /package.json
- /README.md (this file)
- /site.yaml

Flow: main page with hero and image example.

Main navigation: inside /site.yaml with the \<navi/> extension.

Deploy to Netlify.
