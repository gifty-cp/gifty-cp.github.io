# Chanakarn (Gifty) Punyachai: Data Analyst Portfolio

Live site: **[https://gifty-cp.github.io](https://gifty-cp.github.io)**

Aspiring Data Analyst based in Adelaide, South Australia, combining hospitality experience, a Master of Information Technology (Business Analysis) and an accounting background with hands-on data projects.

---

## What's on the site

| Section | What it shows |
|---|---|
| **Profile sidebar** | Headshot, name, bio, location, and links to LinkedIn, GitHub and email |
| **About me** | My background and why I'm moving into analytics |
| **Technical skills** | Excel, SQL, Python and Power BI, and what I use each one for |
| **Featured projects** | Business question, tools, preview, finding and links for each project |
| **Learning** (separate page) | Excel techniques from my projects, written up step by step |
| **Relevant experience** | Hospitality and Business Analyst internship roles |
| **Professional development** | Current learning, including The Data & AI Institute |
| **Education** | Master of IT (Business Analysis), accounting and leadership qualifications |
| **Connect with me** | LinkedIn, email and work preferences |

## Featured projects

- **[Complaints Dashboard](https://gifty-cp.github.io/commbank-dashboard.html)**: Commonwealth Bank Customer Complaints Register & SLA Performance (2011–2020). An interactive dashboard covering 467 complaints. 94.4% received a timely response, yet 20.6% were still escalated to a formal dispute.
- **[BIG W Sales Dashboard](https://gifty-cp.github.io/projects/bigw-sales-dashboard.pdf)**: Excel dashboard of 4,505 sales (2024–2025). About 72% of the $1.85M in sales came from physical stores, a share that held in every category.
- **Woolworths Dark Store Category Analysis** ([matrix](https://gifty-cp.github.io/projects/woolworths-category-correlation-matrix.html), [floor planner](https://gifty-cp.github.io/projects/woolworths-dark-store-floor-planner.html)): which categories the same customers spend on. Pasta and Pasta Sauce move almost in lockstep (r = 0.96), and the 10 categories group into four aisles.
- **[Netflix Viewing-Pattern Recommender](https://gifty-cp.github.io/projects/netflix-watch-next-matcher.html)**: recommends the next show from shared viewing hours across 2,000 subscribers, revealing four taste groups.

---

## Files

```
index.html               Portfolio page (single file, no build step)
learning.html            Learning page
commbank-dashboard.html  Interactive Complaints Dashboard
projects/                Woolworths and Netflix dashboards, BIG W dashboard PDF
assets/                  Project preview images
  headshot.jpg           Profile photo (add your own; initials show until then)
```

## Preview locally

Double-click `index.html`, or run a local server:

```bash
cd ~/Projects/gifty-cp.github.io
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

## Publish

GitHub Pages serves the `main` branch of this repository at https://gifty-cp.github.io:

```bash
git add index.html learning.html commbank-dashboard.html projects assets README.md
git commit -m "Update portfolio"
git push origin main
```

## Contact

- LinkedIn: [linkedin.com/in/cpunyachai](https://www.linkedin.com/in/cpunyachai/)
- Email: [c.punyachai8@gmail.com](mailto:c.punyachai8@gmail.com)
