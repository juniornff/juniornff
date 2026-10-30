# Nehemias Feliz!

## Contact

* **Website:** [https://nehemiasfeliz.com/](https://nehemiasfeliz.com/)
* **Email:** [info@nehemiasfeliz.com](mailto:info@nehemiasfeliz.com)
* **LinkedIn:** [Nehemias Feliz](https://www.linkedin.com/in/nehemias-feliz-ferreras/)

## Bio

I am a **Software Engineer with a Backend and DevOps focus** based in Santo Domingo, Dominican Republic. I specialize in building robust logic, scalable infrastructure and containerized deployments, with a particular focus on **Python** and **Docker**.

Whether I’m optimizing SQL queries or orchestrating multi-container ecosystems, I thrive on turning complex problems into clean, efficient code.

### About Me

* **Education:** Currently pursuing an [**Official Master's Degree in Networks and Cybersecurity (MRC)**](https://www.ceste.es/masteres-oficiales-y-mba/mrc-master-en-redes-y-ciberseguridad/) at CESTE (UWTSD); I hold a B.S. in Software Engineering from APEC University and an Associate's Degree in Software Development (**Cum Laude**) from ITSC.
* **Achievements:** Represented the Dominican Republic in the **Ibero-American Cyber Security Challenge** in Colombia (OAS).
* **Certifications:** Harvard University’s **CS50’s Introduction to Computer Science**.
* **Current Focus:** Level 2 IT operations and application support in production environments, while building containerized projects with CI/CD, deepening Linux skills and specializing in networks and cybersecurity.

## Technical Stack

* **DevOps & Infrastructure:** Docker & Docker Compose, Linux (Debian), Server Management, Reverse Proxy (Caddy), SSL/TLS, CI/CD (GitHub Actions), Git/GitHub.
* **Languages & Logic:** Python (Flask, FastAPI), C#, PHP, OOP.
* **Data Architecture:** SQL Server (T-SQL), MySQL, SQLite, Relational Schema Design.
* **Networking & Security:** RESTful APIs, Networking & Communications, DDNS, MergeFS (Storage Virtualization).

## Featured Projects

#### [Smash Bros. Tournament Engine](https://smash.nehemiasfeliz.com/)

Web application to organize and manage Super Smash Bros Ultimate meetups and tournaments for local/small communities.

* **Backend:** Engineered with **Python/Flask** using complex business logic for bracket management and match validation.
* **Infrastructure:** Orchestrated a multi-container environment via **Docker Compose** with a CI/CD pipeline powered by **GitHub Actions**.
* **Data:** Designed a relational database to manage users, tournaments, and combat statistics.

#### [Scalable Self-Hosted Media Engine](https://media.nehemiasfeliz.com)

A high-availability home server infrastructure focused on efficiency and security. [Blog](https://nehemiasfeliz.com/posts/local-media-server)

* **Containerization:** Deployed a Debian-based ecosystem using **Docker** for services like Jellyfin and qBittorrent.
* **Networking & Security:** Implemented **Caddy** as a Reverse Proxy with automatic SSL and **Cloudflare DDNS** to bypass ISP limitations.
* **Optimization:** Configured **Intel QuickSync** hardware-accelerated transcoding and **MergeFS** for virtual disk pooling.

#### [Wedding Photo Manager](https://github.com/juniornff/wedding-photo-manager)

Web application to manage wedding photos: guests upload, browse and download photos **without signing up**, plus an interactive **Secret Photographer** game (per-table challenges with QR codes) and a full admin panel.

* **Backend:** Engineered with **Python/FastAPI** and async SQLAlchemy, featuring SSE for a live gallery, Google OAuth with anonymous per-device identity, and HEIC-to-JPEG conversion.
* **Frontend:** Built with **React 19 + Vite + TailwindCSS**, including bulk ZIP downloads and a public live dashboard.
* **Infrastructure:** Multi-container deployment via **Docker Compose** with CI/CD on **GitHub Actions** and images published to GHCR; tested with **pytest** (174) and **Vitest** (77).
