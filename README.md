# Personal website

A personal portfolio website built as a project for the Web Development course at UVA University.

> The entire website is in Portuguese.

## Pages

| File | Section | Description |
|---|---|---|
| `index.html` | Home | Introduction, profile photo, and skills table |
| `sobre.html` | About | Professional experience and academic background |
| `portifolio.html` | Portfolio | AI/ML projects with descriptions and GitHub links |
| `novidades.html` | News | Published Medium articles on voice biometrics and audio processing |
| `contato.html` | Contact | Contact form and LinkedIn integration |
| `referencias.html` | References | Sources used during development |

## Tech Stack

- **HTML5** — semantic structure and page content
- **CSS3** — layout (Flexbox + Grid), CSS custom properties, responsive design
- **Google Fonts** — Cormorant Garamond (headings)

No JavaScript or build tools — fully static site.

## Project Structure

```
website_pessoal/
├── index.html
├── sobre.html
├── portifolio.html
├── novidades.html
├── contato.html
├── referencias.html
├── style.css
└── imagens/
    ├── foto-liz.jpeg
    ├── icone.png
    ├── linkedin-logo.png
    ├── projeto-1.png
    ├── projeto-2.png
    └── projeto-3.PNG
```

## Running Locally

No setup required. Open any `.html` file directly in a browser, or use a local server:

```bash
# Python
python -m http.server 8000

# Node.js (npx)
npx serve .
```

Then navigate to `http://localhost:8000/01-inicio.html`.

## Featured Projects

- **Artemis** — Voice assistant with speech recognition, agenda management, news, notes, and Microsoft Teams integration
- **Audio Anomaly Detection** — Industrial machinery fault detection via audio classification for Smart Factory applications
- **Hybrid RAG System** — Financial document analysis using dense embeddings, BM25, ColBERT reranking, Qdrant, and Gemini
