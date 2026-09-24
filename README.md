# ANDÚRIL RACING — F1 in Schools

**[ANDÚRIL RACING — Official team website](https://andurilracing.com/)**

[My personal commentary and project experience](https://sienarindustries.com/project/f1-in-schools)

Car designs, CAD exports, and supporting models for team ANDÚRIL RACING from Marlborough College Malaysia.

## Start here

These are the two main documents for this project. Read the project portfolio first.

1. [Project portfolio](PROJECT_PORTFOLIO.pdf) — Explains our contributions, design decisions, and build process. It covers the car and the wider team project.
2. [Technical drawings and renders](DRAWINGS_AND_RENDERS.pdf) — Shows the assembled car, dimensioned component drawings, and final renders.

*Louis Gan and Shi Hao Ng produced the project portfolio in Adobe Illustrator.*

---

**Explore the engineering work in our two submodules:**

- **[Anduril Design](https://github.com/Ice-Citron/Anduril-Design)** — Car models, concept sketches, and design history.
- **[Anduril CFD and Manufacturing](https://github.com/Ice-Citron/Anduril-CFD-and-Manufacturing)** — CFD studies, geometry preparation, and files for CNC manufacture and resin production.

---

As a team from Marlborough College Malaysia in the F1 in Schools campaign, Anduril will be a competitor in various competitions around Malaysia such as the Johor State Finals in late June and with the FOBISIA Malaysian Schools in Q4 this year. We will be exposed to thousands of national and international judges and fellow competitors around the country, as well as the sole provider for the track and racing competition for Marlborough College Malaysia for future races.

![Screenshot 2024-08-14 at 10 41 38 PM](https://github.com/user-attachments/assets/8a7f12f1-ed80-4a94-9248-92eb4d7626d2)

## Project overview

This is the main repository for ANDÚRIL RACING’s 2024 F1 in Schools project.

Our work covered the car and the equipment required to test it. We also produced a team website and sponsorship materials.

The project included:

- Car concept art and CAD models.
- Computational fluid dynamics (CFD) studies.
- CNC manufacture and resin components.
- A 20-metre race track.
- A gas launcher and electronic timer.
- A team website and project portfolios.
- Sponsor proposals and external partnerships.

## Explore the project

| Area | Where to look |
|---|---|
| Project decisions and team contributions | [Project portfolio](PROJECT_PORTFOLIO.pdf) |
| Dimensioned drawings and final renders | [Technical drawings and renders](DRAWINGS_AND_RENDERS.pdf) |
| Car design history and original models | [Anduril Design](https://github.com/Ice-Citron/Anduril-Design) |
| Simulation files and manufacture exports | [Anduril CFD and Manufacturing](https://github.com/Ice-Citron/Anduril-CFD-and-Manufacturing) |
| Team website source | [Website Files](<Website Files/>) |
| Sponsor proposals and contribution tiers | [Sponsorship Letters](<Sponsorship Letters/>) |

The two engineering repositories are Git submodules. Each submodule points to a specific commit in its own repository.

## Engineering work

### Car design and manufacture

Our team developed the car through several design versions. Early work began with concept sketches and Blender models.

We prepared geometry for CFD through Fusion 360 and Ansys Discovery. More complex models also required mesh repair in Autodesk Netfabb.

The simulation work helped us examine airflow around the wheels and behind the car. These observations informed changes to the body and rear vanes.

We then prepared separate files for the CNC body and resin wings. The project portfolio explains the design decisions and the manufacture process.

| Car prototypes | Track workshop |
|---|---|
| ![Three 3D-printed car prototypes](<Website Files/assets/img/gallery/car/car1.png>) | ![Metalwork for the race-track project](<Website Files/assets/img/gallery/track/track4.jpg>) |

*Physical car models and workshop work from the team project.*

### Track and test equipment

We built a 20-metre pine track with support from the school’s Estates team. The work included track joints and the assembly of the track on reused tables.

Our electronics engineer developed an Arduino timer with a C++ program. Laser sensors and photoreceptors detected the car at the start and finish.

The gas launcher used a design by TeachingTech, as credited in the project portfolio.

These systems gave the school equipment for future F1 in Schools teams.

[View the track photographs](<Website Files/assets/img/gallery/track/>)

## My contribution and the team

I am Shi Hao Ng. I was the project manager and general engineer for ANDÚRIL RACING.

I led the technical work on CFD and car design. I also coordinated external support and managed the track manufacture work.

The project combined the work of six team members:

| Team member | Main responsibilities |
|---|---|
| Shi Hao Ng | Project management, technical direction for CFD and car design, and track manufacture coordination. |
| Louis Gan | Electronics, the track timer system, and graphic design. |
| Samson Hong | CAD models, car manufacture, and Blender renders and animation. |
| Jolie Teo | The team website, graphics, and support for manufacture and sponsorship. |
| Hengjun Tian | Ansys Fluent studies and track manufacture. |
| Jane Ng | Car concept art and sponsor relations. |

Louis Gan and I produced the project portfolio in Adobe Illustrator.

The [project portfolio](PROJECT_PORTFOLIO.pdf) gives more detail about each role and our work with external partners.

## Team website

The public website presents the team and its work:

**[Visit andurilracing.com](https://andurilracing.com/)**

The source uses HTML, CSS, and JavaScript. It includes:

- A team member carousel.
- Project galleries with images and videos.
- Sponsor information.
- An expandable FAQ section.
- Navigation links to each page section.

### Website files

| File or folder | Purpose |
|---|---|
| [`index.html`](<Website Files/index.html>) | Page content and structure. |
| [`main.css`](<Website Files/main.css>) | Page layout and visual styles. |
| [`menu.js`](<Website Files/menu.js>) | Marks the active navigation link. |
| [`gallery.js`](<Website Files/gallery.js>) | Controls the team member carousel. |
| [`work-gallery.js`](<Website Files/work-gallery.js>) | Controls project galleries and their image and video navigation. |
| [`faq.js`](<Website Files/faq.js>) | Opens and closes FAQ answers. |
| [`assets/img/`](<Website Files/assets/img/>) | Photographs, renders, and graphic assets. |
| [`assets/fonts/`](<Website Files/assets/fonts/>) | Local font files. |

### Preview the website locally

With Python 3 installed, run this command from the repository root:

```bash
python3 -m http.server 8000 --bind 127.0.0.1 --directory "Website Files"
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

Press `Ctrl+C` in the terminal to stop the server.

The website has no package installation or build step. You can preview it without the engineering submodules.

## Sponsorship and partnerships

The [Sponsorship Letters folder](<Sponsorship Letters/>) contains materials from our sponsor outreach:

- [English proposal template](<Sponsorship Letters/Email - English for corporations.docx>) — For companies.
- [Bahasa Melayu proposal template](<Sponsorship Letters/Email - Bahasa Melayu for City Council, Govt Agencies, etc,.docx>) — For councils and government agencies.
- [Sponsorship tiers](<Sponsorship Letters/Sponsorship - Tiers (FINAL for 23_7_2024).xlsx>) — Our proposed contribution levels and sponsor benefits.

The project portfolio records the support we received:

| Organisation | Support |
|---|---|
| Marlborough College Malaysia | Project funds, facilities, and Estates team support for the track. |
| University of Southampton Malaysia | CFD assistance and access to resin print facilities. |
| Nosco Asia | CNC supplier coordination, banner production, and transport support. |
| University of Reading Malaysia | Advice on sponsorship and project management. |

## Get the complete project

To download this repository and both engineering submodules:

```bash
git clone --recurse-submodules https://github.com/Ice-Citron/anduril.git
cd anduril
```

If you already cloned this repository, run this command from its root:

```bash
git submodule update --init --recursive
```

This downloads the submodule commits recorded by the main repository.

Each engineering repository has its own README with details about its files.

## Repository structure

```text
anduril/
├── README.md
├── PROJECT_PORTFOLIO.pdf
├── DRAWINGS_AND_RENDERS.pdf
├── LICENSE
├── .gitmodules
├── Website Files/
│   ├── index.html
│   ├── main.css
│   ├── menu.js
│   ├── gallery.js
│   ├── work-gallery.js
│   ├── faq.js
│   └── assets/
│       ├── fonts/
│       └── img/
├── Sponsorship Letters/
├── Anduril-Design/                    # Git submodule
└── Anduril-CFD-and-Manufacturing/      # Git submodule
```

## Licences

This main repository uses the [Apache License 2.0](LICENSE).

The engineering repositories contain their own licence files:

- [Anduril Design — Apache License 2.0](https://github.com/Ice-Citron/Anduril-Design/blob/main/LICENSE)
- [Anduril CFD and Manufacturing — MIT License](https://github.com/Ice-Citron/Anduril-CFD-and-Manufacturing/blob/main/LICENSE)