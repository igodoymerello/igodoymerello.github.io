---
title: "About"
layout: page
permalink: /about/
---

# About

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

<div class="section-card" style="margin-top: var(--space-4);">
<h3 style="margin-top: 0;">Bio</h3>
<p style="line-height: 1.6; color: var(--text-primary); margin: 0;">
Economist from the University of Chile, holding a Minor in Macrofinance and Banking and an M.Sc. in Applied Economics from the same institution. Currently working as an Economic Researcher at Espacio Público and serving as a Research Assistant. I have developed both analytical and practical thinking, guided by a strong commitment to economic discipline, social responsibility, and collaboration, with extensive experience in academic research, econometric methods, and the evaluation of public policies.
</p>
</div>

<div class="section-card" style="margin-top: var(--space-4);">
<h3 style="margin-top: 0;">Education & Executive Training</h3>

<div style="display: flex; align-items: flex-start; gap: 1.2rem; margin-top: 1.2rem;">
<img src="{{ '/images/oxford-logo-DzIWfeXH.svg' | relative_url }}" alt="University of Oxford" style="width: 44px; height: auto; object-fit: contain; margin-top: 3px;">
<div>
<h4 style="margin: 0; font-size: 1.05rem;">Blavatnik School of Government, University of Oxford</h4>
<p style="margin: 0.2rem 0 0 0; color: var(--text-secondary); font-size: 0.95rem;">
<strong>Executive Education: Managing Mining, Oil and Gas for National Development</strong> &bull; September, 2026
</p>
</div>
</div>

<hr style="border: 0; border-top: 1px solid var(--border-color); margin: 1rem 0;">

<div style="display: flex; align-items: flex-start; gap: 1.2rem;">
<img src="{{ '/images/escudo-uchile-vertical-color-fondo-transp.png' | relative_url }}" alt="Universidad de Chile" style="width: 44px; height: auto; object-fit: contain; margin-top: 3px;">
<div>
<h4 style="margin: 0; font-size: 1.05rem;">School of Economics and Business (FEN), University of Chile</h4>
<p style="margin: 0.2rem 0 0 0; color: var(--text-secondary); font-size: 0.95rem;">
<strong>Master of Science (M.Sc.) in Applied Economics</strong> &bull; 2024 &ndash; 2026
</p>
<p style="margin: 0.4rem 0 0 0; color: var(--text-secondary); font-size: 0.95rem;">
<strong>Bachelor of Science (B.Sc.) in Economics</strong> &bull; 2020 &ndash; 2024<br>
<span style="font-size: 0.9rem; color: var(--text-secondary);">&bull; Minor in Macrofinance and Banking</span>
</p>
</div>
</div>
</div>

<div class="section-card" style="margin-top: var(--space-4);">
<h3 style="margin-top: 0;">Experience</h3>
<ul style="list-style: none; padding-left: 0; margin: 1rem 0 0 0;">
<li style="margin-bottom: 1.2rem;">
<strong style="font-size: 1rem;">Economic Researcher</strong> &bull; <em>Espacio Público</em><br>
<span style="font-size: 0.85rem; color: var(--text-secondary);">Sustainability & Economic Growth &bull; January 2026 &ndash; Present</span>
</li>
<li style="margin-bottom: 1.2rem;">
<strong style="font-size: 1rem;">Economic Research Assistant</strong> &bull; <em>Fondecyt Project No. 1241625</em><br>
<span style="font-size: 0.85rem; color: var(--text-secondary);">"Representation, Quotas, and Violence Against Female Politicians" (Lead: Francisco Pino, Co-lead: Eleonora Guarnieri) &bull; December 2024 &ndash; Present</span>
</li>
<li style="margin-bottom: 1.2rem;">
<strong style="font-size: 1rem;">Economic Consultant & Intern</strong> &bull; <em>United Nations ECLAC</em><br>
<span style="font-size: 0.85rem; color: var(--text-secondary);">Natural Resources Division (Energy Unit & Non-Renewable Resources Unit) &bull; June 2024 &ndash; January 2026</span>
</li>
<li style="margin-bottom: 0;">
<strong style="font-size: 1rem;">Finance Intern</strong> &bull; <em>Itaú Bank</em><br>
<span style="font-size: 0.85rem; color: var(--text-secondary);">Financial Planning and Analysis & Capital Management &bull; January &ndash; February 2024</span>
</li>
</ul>
</div>

<div class="section-card" style="margin-top: var(--space-4);">
<h3 style="margin-top: 0;">Teaching Assistantships</h3>
<ul style="margin: 0.8rem 0 0 0; padding-left: 1.2rem; color: var(--text-secondary); font-size: 0.95rem; line-height: 1.6;">
<li><strong>Public Policy Workshop</strong> &bull; Prof. Óscar Landerretche (Autumn & Spring Semesters, 2024)</li>
<li><strong>Introductory Microeconomics</strong> &bull; Prof. Melanie Saavedra (Summer Semester, 2024)</li>
</ul>
</div>

<div class="section-card" style="margin-top: var(--space-4);">
<h3 style="margin-top: 0;">Skills & Languages</h3>
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 1.5rem; margin-top: 1rem;">
<div>
<h4 style="margin: 0 0 0.5rem 0; font-size: 0.95rem; text-transform: uppercase; letter-spacing: 0.05em; color: var(--accent-base);">Data Management & Statistics</h4>
<p style="margin: 0; color: var(--text-secondary); font-size: 0.92rem; line-height: 1.6;">
R, SQL, STATA, Python, BigQuery, Matlab.
</p>
<h4 style="margin: 1rem 0 0.5rem 0; font-size: 0.95rem; text-transform: uppercase; letter-spacing: 0.05em; color: var(--accent-base);">Productivity & Design</h4>
<p style="margin: 0; color: var(--text-secondary); font-size: 0.92rem; line-height: 1.6;">
LaTeX, Microsoft Office (Excel, Word, PowerPoint), Power BI, Adobe Suite (Photoshop, Premiere Pro, After Effects, Illustrator).
</p>
</div>
<div>
<h4 style="margin: 0 0 0.5rem 0; font-size: 0.95rem; text-transform: uppercase; letter-spacing: 0.05em; color: var(--accent-base);">Languages</h4>
<ul style="margin: 0; padding-left: 1.2rem; color: var(--text-secondary); font-size: 0.92rem; line-height: 1.6;">
<li><strong>Spanish:</strong> Native</li>
<li><strong>English:</strong> Advanced</li>
<li><strong>French:</strong> Advanced</li>
</ul>
</div>
</div>
</div>
