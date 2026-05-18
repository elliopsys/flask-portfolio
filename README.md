# Personal Portfolio — Flask & PythonAnywhere

A personal portfolio website built with Python and Flask, hosted on PythonAnywhere. This is the live site behind [elliyani.pythonanywhere.com](https://elliyani.pythonanywhere.com).

---

## What it is

A clean, custom-designed portfolio page that introduces who I am, what I do, and what I've built — without relying on a generic template. Built as a practical Flask project and a real professional presence in one.

The site includes:

- An About Me section with my background and professional bio
- A skills section covering DevOps, cloud, and operations tooling
- A projects section linking to real work on GitHub
- Links to GitHub, LinkedIn, and contact

---

## Why Flask

I chose Flask deliberately rather than a static site builder. It gives me full control over routing, templating, and future features like contact forms or dynamic project feeds — and it keeps my Python skills active while building something genuinely useful.

---

## Tech stack

| Layer | Technology |
|---|---|
| Language | Python 3 |
| Web framework | Flask |
| Templating | Jinja2 (HTML templates) |
| Styling | Custom CSS — no frameworks |
| Hosting | PythonAnywhere |
| Version control | Git + GitHub |

---

## Project structure

```
flask-portfolio/
├── flask_app.py          # Flask app and route definitions
├── templates/
│   ├── about.html        # Portfolio homepage
│   └── login_page.html   # Login page (legacy)
└── .gitignore
```

---

## Running it locally

If you want to run this on your own machine:

```bash
# Clone the repo
git clone https://github.com/elliopsys/flask-portfolio.git
cd flask-portfolio

# Create a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install flask

# Run the app
python flask_app.py
```

Then open your browser at `http://localhost:5000`.

---

## Deployment

The app is hosted on PythonAnywhere. To deploy an update:

```bash
# Make your changes locally, then:
git add .
git commit -m "Your change description"
git push origin main
```

Then in the PythonAnywhere Bash console:

```bash
cd mysite
git pull origin main
```

Finally, go to the **Web tab** on PythonAnywhere and click **Reload**.

> This manual process is intentional for now — a CI/CD pipeline to automate deployment is in progress as a separate project. ee [flask-aks-demo](https://github.com/elliopsys/flask-aks-demo).
 
---
 
## Design decisions
 
**No CSS framework.** Bootstrap and Tailwind produce recognisable, template-like results. The styling here is written from scratch to give the site a distinct editorial feel — a serif display font for the headline, a monospace typeface for labels and navigation, and a restrained teal accent used sparingly throughout.
 
**No JavaScript.** The page is pure HTML and CSS. Fast, accessible, no dependencies.
 
**Honest project descriptions.** The projects section links to real repositories with accurate descriptions of what was actually built and learned — not marketing copy.
 
---
 
## What's next
 
- Connect a custom domain
- Add a CI/CD pipeline to automate deployment (currently being built in [flask-aks-demo](https://github.com/elliopsys/flask-aks-demo))
- Add a contact form
- Expand the projects section as new work is completed
---
 
## Author
 
**Elli** — DevOps engineer with 10+ years of operations and content leadership, now focused on cloud, automation, and DevOps delivery.
 
[GitHub](https://github.com/elliopsys) · [Live site](https://elliyani.pythonanywhere.com)
