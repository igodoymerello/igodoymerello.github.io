---
title: "About"
layout: page
permalink: /about/
---

# About

<!-- Header Card: Photo, Basic Info, Social Links -->
<div class="section-card">
<div class="pi-card">
<img src="{{ site.photo | prepend: '/images/' | relative_url }}" class="pi-photo" alt="{{ site.name }}" width="160" height="160">
<div>
<h2 class="pi-name">{{ site.name }}</h2>
<p style="font-style: italic; color: var(--text-secondary); margin-bottom: var(--space-2);">{{ site.title }}, {{ site.institution }}</p>
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

<!-- Short Bio -->
<div class="section-card" style="margin-top: var(--space-4);">
<h3 style="margin-top: 0;">Bio</h3>
<p style="line-height: 1.6; color: var(--text-primary); margin: 0;">
Economist from the University of Chile, holding a Minor in Macrofinance and Banking and an M.Sc. in Applied Economics from the same institution. Currently working as an Economic Researcher at Espacio Público and serving as a Research Assistant. I have developed both analytical and practical thinking, guided by a strong commitment to economic discipline, social responsibility, and collaboration, with extensive experience in academic research, econometric methods, and public policy evaluation.
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
<strong>Managing Mining, Oil and Gas for National Development</strong> (Executive Education)
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

<!-- Master -->
<div style="margin-bottom: 1rem;">
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<p style="margin: 0; font-size: 0.95rem; color: var(--text-primary);">
<strong>Master of Science (M.Sc.) in Applied Economics</strong>
</p>
<span style="font-size: 0.9rem; color: var(--text-secondary); font-weight: 500;">2024 &ndash; 2026</span>
</div>
</div>

<!-- Bachelor -->
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
<h3 style="margin-top: 0; margin-bottom: 1.2rem;">Experience</h3>

<div style="margin-bottom: 1.3rem;">
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<strong style="font-size: 1rem; color: var(--text-primary);">Economic Researcher &bull; Espacio Público</strong>
<span style="font-size: 0.88rem; color: var(--text-secondary); font-weight: 500;">January 2026 &ndash; Present</span>
</div>
<span style="font-size: 0.88rem; color: var(--text-secondary);">Sustainability & Economic Growth</span>
</div>

<div style="margin-bottom: 1.3rem;">
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<strong style="font-size: 1rem; color: var(--text-primary);">Economic Research Assistant &bull; Fondecyt Project No. 1241625</strong>
<span style="font-size: 0.88rem; color: var(--text-secondary); font-weight: 500;">December 2024 &ndash; Present</span>
</div>
<span style="font-size: 0.88rem; color: var(--text-secondary);">"Representation, Quotas, and Violence Against Female Politicians" (Lead: Francisco Pino, Co-lead: Eleonora Guarnieri)</span>
</div>

<div style="margin-bottom: 1.3rem;">
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<strong style="font-size: 1rem; color: var(--text-primary);">Economic Consultant & Intern &bull; United Nations ECLAC</strong>
<span style="font-size: 0.88rem; color: var(--text-secondary); font-weight: 500;">June 2024 &ndash; January 2026</span>
</div>
<span style="font-size: 0.88rem; color: var(--text-secondary);">Natural Resources Division (Energy Unit & Non-Renewable Resources Unit)</span>
</div>

<div>
<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
<strong style="font-size: 1rem; color: var(--text-primary);">Finance Intern &bull; Itaú Bank</strong>
<span style="font-size: 0.88rem; color: var(--text-secondary); font-weight: 500;">January &ndash; February 2024</span>
</div>
<span style="font-size: 0.88rem; color: var(--text-secondary);">Financial Planning and Analysis & Capital Management</span>
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
