# Karan Mondal - Portfolio Website

Personal portfolio for Karan Mondal, a Data Analyst and Electronics & Telecommunication Engineering student. The site presents analytics work, embedded systems projects, experience, certifications, and contact details in a single responsive page.

Live site: [karanmondal.netlify.app](https://karanmondal.netlify.app)

## Overview

The current portfolio uses a dark, space-inspired interface with gold highlights, animated signal lines, translucent panels, and a large circular profile presentation. It is intentionally built as a lightweight static site so it can be deployed directly to Netlify without a build pipeline.

## Current Features

- Responsive single-page layout for desktop, tablet, and mobile screens
- Fixed navigation with a mobile hamburger menu
- Animated grid, signal-field background, marquee, orbiting social links, and reveal transitions
- Hero actions for exploring work, contacting Karan, and downloading the CV
- About section focused on the connection between data analysis and physical systems
- Skills section with programming, analytics, databases, and embedded/IoT tools
- Interactive skill lab that switches between analytics and engineering profiles
- Experience timeline covering internships and engineering education
- Selected work section with GitHub links for analytics, engineering, and automation projects
- Certificate gallery with click-to-enlarge image previews and Escape-to-close support
- Contact form submitted through Google Forms, with inline submission feedback
- Direct email, LinkedIn, and GitHub contact links

## Page Sections

| Section | Purpose |
| --- | --- |
| Hero | Introduction, profile image, social links, CV download, and primary calls to action |
| About | Background, working philosophy, and focus areas |
| Skills | Tools and technologies used across analytics and embedded engineering |
| Experience | Data analytics internships and B.E. education timeline |
| Work | Selected projects with technology tags and repository links |
| Certificates | Nine certificate images with modal previews |
| Contact | Direct contact links and Google Forms message submission |

## Selected Work

- **E-Commerce & Superstore Sales Analytics Platform** - Python and Pandas ETL with Power BI reporting for transaction, revenue, customer, and delivery analysis.
- **HR Analytics & Attrition Intelligence Dashboard** - Workforce, headcount, salary, tenure, and attrition analysis in Power BI.
- **FNP Orders & Sales Analytics Dashboard** - Interactive KPI and customer-insight dashboard for order and sales data.
- **Credit Card Spending Analytics in India** - Spending-pattern analysis and dashboard-driven insights.
- **Marketing Analytics Dashboard** - Marketing performance and campaign analysis.
- **Social Media Engagement Analytics** - Analysis of platform, content, and publishing-time performance.
- **RL Traffic Control System** - Reinforcement-learning approach to traffic-flow control.
- **ErrorBot** - An automation and debugging-focused project.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts: Manrope and DM Mono
- Icons8 tool icons
- Google Forms for contact submissions
- Netlify for deployment

No framework, package manager, or local build command is required.

## Project Structure

```text
Portfolio-Website/
├── index.html                 # Complete portfolio page, styles, and scripts
├── avatar.jpg                 # Profile image
├── Karan_Mondal.pdf           # Downloadable CV
├── galaxy-bg.mp4              # Background media asset
├── galaxy-preview.jpg         # Background preview asset
├── certificates/              # Certificate images shown in the gallery
├── netlify.toml               # Netlify publish configuration
└── README.md
```

## Run Locally

Because this is a static site, it can be opened directly in a browser. For a local server, run any static file server from the `Portfolio-Website` directory, for example:

```powershell
py -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Deploy

The included `netlify.toml` configures the project root as the Netlify publish directory:

```toml
[build]
	publish = "."
```

Deploy the `Portfolio-Website` directory to Netlify, or connect the repository and use `Portfolio-Website` as the site directory. No build command is needed.

## Contact

- Email: [karanmondal16@gmail.com](mailto:karanmondal16@gmail.com)
- GitHub: [KaranMondal](https://github.com/KaranMondal)
- LinkedIn: [mondal-karan](https://www.linkedin.com/in/mondal-karan)
