# Portfolio redesign prompt — Praneeth Varma Danthuluri

You are a senior creative developer, interaction designer and technical recruiter. Redesign the existing portfolio in this repository into a distinctive, immersive cyber-inspired data engineering experience. The site is deployed at https://praneethvarmadanthuluri.com and the GitHub repository is Pranuvar/portfolio-site.

## Primary objective
Make the portfolio memorable without sacrificing recruiter usability, accessibility, performance or factual credibility. The audience is European hiring managers and recruiters hiring Data Engineers, Analytics Engineers and BI/Data professionals in Ireland and the Netherlands.

## Creative direction
Create a visual identity that feels like a futuristic data systems observatory / cybernetic infrastructure map:
- Near-black graphite background, electric cyan as the primary signal colour, restrained ultraviolet accents.
- Immersive animated particle network / constellation that evokes connected data systems, not generic sci-fi decoration.
- Precise monospaced micro-labels, oversized editorial typography, fine technical grid, thin borders, subtle scan-line and telemetry motifs.
- Motion should feel intentional, elegant and responsive to pointer movement; avoid excessive glitch effects, noisy HUD clutter, fake terminal output, fake metrics or gaming aesthetics.
- The result must feel premium, original and designed around data engineering specifically.

## Information architecture
1. Hero: “Engineering the path from data to decisions.” Position as Data Engineer / Analytics Engineer. State Dublin, Ireland and openness to Ireland / Netherlands. Clear CTAs: projects, GitHub, recruiter quick view.
2. Systems principles: ingestion → transformation → validation → delivery.
3. About: practical bridge between engineering and business; MSc Artificial Intelligence; data platforms, ELT, modelling, orchestration, quality and analytics.
4. Selected projects:
   - Meridian Freight Platform: Databricks + PySpark rebuild. Link https://github.com/Pranuvar/meridian-freight-platform. Describe only what is evidenced in the repository; do not invent volume, performance or business outcomes.
   - Retail data and reporting platform: professional case study supporting three retail locations, Azure SQL, Microsoft Fabric, Snowflake/dbt, Airflow and Power BI. Keep company data private. Daily refresh and approximately 40% less reporting effort may be stated as user-provided experience; do not imply independently audited metrics.
   - Retail Medallion Pipeline: PostgreSQL, Python, Snowflake, dbt Core, Airflow, watermark incremental extraction, dimensional modelling, SCD Type 2, tests and failure-mode work. Link https://github.com/Pranuvar/retail-medallion-pipeline.
   - Network Intrusion Detection: separate MSc/research category, not the lead engineering project. Link https://github.com/Pranuvar/Network-Intrusion-Detection-System.
5. Experience: JKSR Trading Limited, Data and Operations Analyst, Dublin, May 2023–March 2026; Moksh Creative Studios, Project Service Coordinator, Hyderabad, 2022. Keep claims defensible.
6. Technical toolkit grouped by platform and engineering capability.
7. Education: MSc Artificial Intelligence, National College of Ireland (2023–2025); BTech Computer Science Engineering, Vellore Institute of Technology (2017–2021).
8. Contact: email, LinkedIn and GitHub. Work authorisation can be stated factually as Stamp 1G through June 2027; do not make blanket claims about future sponsorship requirements.

## Interaction and technical requirements
- Responsive from 320px mobile to ultrawide desktop.
- Provide reduced-motion support and a static fallback for the particle scene.
- Keep animations GPU-friendly; throttle pointer/scroll work; no huge 3D dependencies unless they clearly add value.
- Make all navigation keyboard accessible; visible focus states; semantic landmarks; accessible labels; sufficient contrast.
- Add a compact recruiter quick-view overlay with role, platforms, location, strongest project links and contact route.
- Keep project links, LinkedIn, GitHub and email functional.
- SEO title, description, Open Graph metadata, canonical URL and favicon.
- No fabricated live system status, uptime, pipeline runs, client logos, certifications, user counts or production metrics.
- Do not expose private employer data or dashboards.
- Keep dependencies minimal and preserve the existing deployment method unless there is a clear reason to change it.
- Validate every link and check the mobile layout, reduced-motion mode, console errors and loading performance.

## Delivery
First inspect the existing repository and preserve useful verified content. Implement the redesign in the existing site rather than creating an unrelated demo. Keep the site deployable through its current GitHub Pages setup. Document any assumptions and any content that still needs confirmation. Do not publish to the production branch until the owner approves the result.