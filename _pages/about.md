---
title: "About"
layout: page
permalink: /about/
---

# About

<!-- Header Card: Photo, Quick Profile & Social Links -->
<div class="section-card">
<div class="pi-card" style="display: flex; gap: 2rem; align-items: center; flex-wrap: wrap;">
<img src="{{ site.photo | prepend: '/images/' | relative_url }}" class="pi-photo" alt="{{ site.name }}" width="150" height="150" style="border-radius: 50%; object-fit: cover;">
<div style="flex: 1; min-width: 260px;">
<h2 class="pi-name" style="margin: 0; font-size: 1.6rem;">{{ site.name }}</h2>
<p style="font-size: 1rem; color: var(--accent-base, #1a7a6d); font-weight: 600; margin: 0.2rem 0 0.5rem 0;">
Economic Researcher &bull; Espacio Público
</p>
<p style="font-size: 0.88rem; color: var(--text-secondary); margin: 0 0 1rem 0; line-height: 1.4;">
Applied Economics &bull; Econometrics &bull; Mineral Economics &bull; Natural Resources &bull; Energy Transition &bull; Mining Value Chains
</p>
<div class="pi-links">
{% if site.email %}<a href="mailto:{{ site.email }}" class="icon-link" title="Email" aria-label="Email">{% include icon.html name="envelope" %}</a>{% endif %}
{% if site.links.cv and site.links.cv != "" %}<a href="{{ site.links.cv | prepend: '/' | relative_url }}" class="icon-link" title="CV" aria-label="CV">{% include icon.html name="cv" %}</a>{% endif %}
{% if site.links.google_scholar and site.links.google_scholar != "" %}<a href="{{ site.links.google_scholar }}" class="icon-link" title="Google Scholar" aria-label="Google Scholar" target="_blank" rel="noopener noreferrer">{% include icon.html name="google-scholar" %}</a>{% endif %}
{% if site.links.github and site.links.github != "" %}<a href="{{ site.links.github }}" class="icon-link" title="GitHub" aria-label="GitHub" target="_blank" rel="noopener noreferrer">{% include icon.html name="github" %}</a>{% endif %}
{% if site.links.researchgate and site.links.researchgate != "" %}<a href="{{ site.links.researchgate }}" class="icon-link" title="ResearchGate" aria-label="ResearchGate" target="_blank" rel="noopener noreferrer">{% include icon.html name="researchgate" %}</a>{% endif %}
{% if site.links.linkedin and site.links.linkedin != "" %}<a href="{{ site.links.linkedin }}" class="icon-link" title="LinkedIn" aria-label="LinkedIn" target="_blank" rel="noopener noreferrer">{% include icon.html name="linkedin" %}</a>{% endif %}
{% if site.links.substack and site.links.substack != "" %}<a href="{{ site.links.substack }}" class="icon-link" title="Substack" aria-label="Substack" target="_blank" rel="noopener noreferrer">{% include icon.html name="substack" %}</a>{% endif %}
</div>
</div>
</div>
</div>

<!-- Bio -->
<div class="section-card" style="margin-top: var(--space-4);">
<h3 style="margin-top: 0; margin-bottom: 1rem;">Bio</h3>
<p style="line-height: 1.7; color: var(--text-primary); margin-bottom: 1.2rem; max-width: 100% !important; width: 100%;">
I am an economist specializing in natural resources, energy transition economics, and industrial policy in Latin America. I hold a B.Sc. in Economics (with a Minor in Macrofinance and Banking) and an M.Sc. in Applied Economics from the School of Economics and Business (FEN) at the University of Chile. My research focuses on empirical and econometric analysis applied to mineral value chains—particularly copper and critical minerals—but also to political violence, combining quantitative modeling, spatial econometrics, and policy evaluation.
</p>
<p style="line-height: 1.7; color: var(--text-primary); margin: 0; max-width: 100% !important; width: 100%;">
Currently, I work as an Economic Researcher at the think tank Espacio Público in the Sustainability & Economic Growth area, where I lead and co-author policy papers on mining issues, from exploration dynamics to value-addition. Concurrently, I serve as a Research Assistant on Fondecyt Project No. 1241625 analyzing institutional violence and political representation. Previously, I served as an Economic Consultant and Intern at the Natural Resources Division of the United Nations ECLAC, conducting technical research on regional foreign direct investment (FDI) in critical minerals, and low-emission hydrogen pathways for the Latin America and the Caribbean (LAC) region.
</p>
</div>

<!-- Education -->
<div class="section-card" style="margin-top: var(--space-4);">
<h3 style="margin-top: 0; margin-bottom: 1.5rem;">Education</h3>

<!-- Oxford -->
<div style="display: flex; align-items: flex-start; gap: 1.4rem;">
<div style="width: 64px; flex-shrink: 0; display: flex; justify-content: center;">
<img src="{{ '/images/oxford-logo-DzIWfeXH.svg' | relative_url }}" alt="University of Oxford" style="width: 64px; height: auto; object-fit: contain;">
</div>
<div style="flex-grow: 1;">
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<h4 style="margin: 0; font-size: 1.05rem;">Blavatnik School of Government, University of Oxford</h4>
<span style="font-size: 0.9rem; color: var(--text-secondary); font-weight: 500;">September 2026</span>
</div>
<p style="margin: 0.25rem 0 0 0; color: var(--text-primary); font-size: 0.95rem;">
<strong>Managing Mining, Oil and Gas for National Development</strong> (Executive Programme)
</p>
<p style="margin: 0.35rem 0 0 0; color: var(--text-secondary); font-size: 0.88rem; line-height: 1.5;">
In-person program in Oxford, UK &bull; Awarded full scholarship by the Natural Resource Governance Institute (NRGI)
</p>
</div>
</div>

<hr style="border: 0; border-top: 1px solid var(--border-color); margin: 1.4rem 0;">

<!-- University of Chile -->
<div style="display: flex; align-items: flex-start; gap: 1.4rem;">
<div style="width: 64px; flex-shrink: 0; display: flex; justify-content: center;">
<img src="{{ '/images/escudo-uchile-vertical-color-fondo-transp.png' | relative_url }}" alt="Universidad de Chile" style="width: 60px; height: auto; object-fit: contain;">
</div>
<div style="flex-grow: 1;">
<h4 style="margin: 0 0 0.8rem 0; font-size: 1.05rem;">School of Economics and Business (FEN), University of Chile</h4>

<div style="margin-bottom: 1rem;">
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<p style="margin: 0; font-size: 0.95rem; color: var(--text-primary);">
<strong>Master of Science (M.Sc.) in Applied Economics</strong>
</p>
<span style="font-size: 0.9rem; color: var(--text-secondary); font-weight: 500;">2024 &ndash; 2026</span>
</div>
</div>

<div>
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<p style="margin: 0; font-size: 0.95rem; color: var(--text-primary);">
<strong>Bachelor of Science (B.Sc.) in Economics</strong>
</p>
<span style="font-size: 0.9rem; color: var(--text-secondary); font-weight: 500;">2020 &ndash; 2024</span>
</div>
<p style="margin: 0.2rem 0 0.5rem 0; color: var(--text-secondary); font-size: 0.88rem;">
Minor in Macrofinance and Banking
</p>
<ul style="margin: 0.3rem 0 0 0; padding-left: 1.2rem; color: var(--text-secondary); font-size: 0.88rem; line-height: 1.5;">
<li><strong>Teaching Assistant:</strong> Public Policy Workshop (Prof. Óscar Landerretche &bull; 2024)</li>
<li><strong>Teaching Assistant:</strong> Introductory Microeconomics (Prof. Melanie Saavedra &bull; 2024)</li>
</ul>
</div>

</div>
</div>
</div>

<!-- Experience -->
<div class="section-card" style="margin-top: var(--space-4);">
<h3 style="margin-top: 0; margin-bottom: 1.5rem;">Experience</h3>

<div>
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<h4 style="margin: 0; font-size: 1rem; color: var(--text-primary);">Economic Researcher &bull; Espacio Público</h4>
<span style="font-size: 0.9rem; color: var(--text-secondary); font-weight: 500;">January 2026 &ndash; Present</span>
</div>
<p style="margin: 0.25rem 0 0 0; font-size: 0.88rem; color: var(--text-secondary);">Sustainability & Economic Growth area</p>
</div>

<hr style="border: 0; border-top: 1px solid var(--border-color); margin: 1.2rem 0;">

<div>
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<h4 style="margin: 0; font-size: 1rem; color: var(--text-primary);">Economic Research Assistant &bull; Fondecyt Project No. 1241625</h4>
<span style="font-size: 0.9rem; color: var(--text-secondary); font-weight: 500;">December 2024 &ndash; Present</span>
</div>
<p style="margin: 0.25rem 0 0 0; font-size: 0.88rem; color: var(--text-secondary);">
"Representation, Quotas, and Violence Against Female Politicians" &bull; Lead Researcher: Francisco Pino (FEN, U. de Chile), Co-researcher: Eleonora Guarnieri (Univ. of Bristol)
</p>
</div>

<hr style="border: 0; border-top: 1px solid var(--border-color); margin: 1.2rem 0;">

<div>
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<h4 style="margin: 0; font-size: 1rem; color: var(--text-primary);">Economic Consultant &bull; United Nations ECLAC</h4>
<span style="font-size: 0.9rem; color: var(--text-secondary); font-weight: 500;">January 2025 &ndash; January 2026</span>
</div>
<p style="margin: 0.25rem 0 0 0; font-size: 0.88rem; color: var(--text-secondary);">
Natural Resources Division (Energy Unit & Non-Renewable Resources Unit)
</p>
</div>

<hr style="border: 0; border-top: 1px solid var(--border-color); margin: 1.2rem 0;">

<div>
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<h4 style="margin: 0; font-size: 1rem; color: var(--text-primary);">Economic Affairs Intern &bull; United Nations ECLAC</h4>
<span style="font-size: 0.9rem; color: var(--text-secondary); font-weight: 500;">June &ndash; November 2024</span>
</div>
<p style="margin: 0.25rem 0 0 0; font-size: 0.88rem; color: var(--text-secondary);">
Natural Resources Division
</p>
</div>

<hr style="border: 0; border-top: 1px solid var(--border-color); margin: 1.2rem 0;">

<div>
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<h4 style="margin: 0; font-size: 1rem; color: var(--text-primary);">Finance Intern &bull; Itaú Bank</h4>
<span style="font-size: 0.9rem; color: var(--text-secondary); font-weight: 500;">January &ndash; February 2024</span>
</div>
<p style="margin: 0.25rem 0 0 0; font-size: 0.88rem; color: var(--text-secondary);">
Financial Planning and Analysis & Capital Management
</p>
</div>
</div>

<!-- Technical Expertise & Competencies -->
<div class="section-card" style="margin-top: var(--space-4);">
<h3 style="margin-top: 0;">Technical Expertise & Competencies</h3>
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 1.8rem; margin-top: 1.2rem;">
<div>
<h4 style="margin: 0 0 0.5rem 0; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 0.05em; color: var(--accent-base);">Econometric & Data Stack</h4>
<p style="margin: 0; color: var(--text-secondary); font-size: 0.92rem; line-height: 1.6;">
R, SQL, STATA, Python, BigQuery, Matlab.
</p>

<h4 style="margin: 1.2rem 0 0.5rem 0; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 0.05em; color: var(--accent-base);">Workflow & Technical Computing</h4>
<p style="margin: 0; color: var(--text-secondary); font-size: 0.92rem; line-height: 1.6;">
LaTeX, Microsoft Office (Excel, Word, PowerPoint), Power BI, Adobe Creative Suite (Photoshop, Premiere Pro, After Effects, Illustrator).
</p>
</div>
<div>
<h4 style="margin: 0 0 0.5rem 0; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 0.05em; color: var(--accent-base);">Working Languages</h4>
<ul style="margin: 0; padding-left: 1.2rem; color: var(--text-secondary); font-size: 0.92rem; line-height: 1.7;">
<li><strong>Spanish:</strong> Native</li>
<li><strong>English:</strong> Advanced professional proficiency</li>
<li><strong>French:</strong> Advanced professional proficiency</li>
</ul>
</div>
</div>
</div>
