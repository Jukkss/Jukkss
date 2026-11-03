<div align="center">

<img src="./assets/header.svg" width="100%" alt="João Victor Soares, Data Integration, Automation and Systems Integration"/>

<p><b>Developer at PUC Minas (GTI)</b></p>

<a href="https://github.com/Jukkss"><img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=18&duration=3200&pause=900&color=8A867F&center=true&vCenter=true&width=720&lines=Building+pipelines+over+data+that+was+never+tracked;Integrating+LMS+APIs%2C+Dataverse+and+legacy+platforms;Making+institutional+data+queryable+and+traceable" alt="Typing summary"/></a>

<br/>

<a href="https://www.linkedin.com/in/jukkss"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://lattes.cnpq.br/1881452950501986"><img src="https://img.shields.io/badge/Lattes-1F4E79?style=flat-square" alt="Lattes"/></a>
<img src="https://img.shields.io/badge/Belo%20Horizonte%2C%20Brazil-555555?style=flat-square" alt="Location"/>

<br/>

<h2>About</h2>

<p>Developer (Analista I) in the IT management team (GTI) at PUC Minas, previously IT Technician in Infrastructure and Automation at IEC.<br/>
I integrate systems that were not designed to communicate: LMS APIs, Dataverse, SharePoint, legacy web platforms and relational databases.</p>

<p>My focus is <b>Data Integration Engineering</b>, supported by automation and DevOps practices.<br/>
AI tools (Claude, Codex) are part of my daily workflow for code, data processing and analytics.</p>

<p>B.S. in Information Systems, PUC Minas (2024 to 2028)<br/>
Technical degree in Electrotechnics, CEFET-MG</p>

<img src="./assets/pipeline.svg" width="88%" alt="Source, Extract, Validate, Store, Expose"/>

<br/>

<h2>Tech Stack</h2>

<p><b>Data and Integration</b></p>
<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="36" title="Python"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="36" title="FastAPI"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="36" title="PostgreSQL"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prisma/prisma-original.svg" width="36" title="Prisma"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/supabase/supabase-original.svg" width="36" title="Supabase"/>&nbsp;
<img src="./assets/icons/powerautomate.svg" width="36" title="Power Automate"/>&nbsp;
<img src="./assets/icons/powerbi.svg" width="36" title="Power BI"/>
</p>
<p><sub>Microsoft Dataverse · SharePoint · Power Apps · AI Builder · Canvas LMS API · REST APIs · pydantic · BeautifulSoup</sub></p>

<p><b>Back-end and Front-end</b></p>
<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="36" title="TypeScript"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="36" title="JavaScript"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="36" title="Node.js"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="36" title="Next.js"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="36" title="React"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" width="36" title="Tailwind CSS"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="36" title="C#"/>
</p>
<p><sub>NextAuth · Zod · TanStack Table · Jest · Playwright · pytest</sub></p>

<p><b>DevOps and Platform</b></p>
<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="36" title="Git"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" width="36" title="GitHub Actions"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vercel/vercel-original.svg" width="36" title="Vercel"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" width="36" title="Azure (in progress)"/>
</p>
<p><sub>CI/CD · self-hosted runners · composite actions · repository_dispatch</sub></p>

<br/>

<h2>Featured Projects</h2>

<h3>Legacy System Data Preservation</h3>
<p><i>ETL pipeline · GTI, PUC Minas</i></p>
<p>Extraction pipeline that preserves the data of a legacy institutional application with no database access, no source code and no API, using only its authenticated web interface.<br/>
A generic, configuration-driven engine maps 58 screens into 8 batches, with integrity guards, count reconciliation, resumable execution and SHA-256 checksums.<br/>
Power Automate triggers each batch through GitHub Actions and stores the results in SharePoint. Covered by 170 tests and a CI that runs the full pipeline against a mock server.</p>
<p><code>Python</code> <code>requests</code> <code>BeautifulSoup</code> <code>pydantic</code> <code>pytest</code> <code>GitHub Actions</code> <code>Power Automate</code> <code>Dataverse</code> <code>SharePoint</code></p>
<p><a href="https://lnkd.in/p/dSnhU7tZ](https://lnkd.in/p/d3_3qQQs">Project post</a></p>

<br/>

<h3>Institutional Evaluation Automation (NPS)</h3>
<p><i>Data integration and analytics · IEC, PUC Minas · in production</i></p>
<p>Automated collection of distance learning course evaluations from the Canvas LMS, replacing a manual and decentralized process.<br/>
Data is structured in a relational model on Dataverse (semesters, courses, subjects, NPS and comments), and a custom AI model classifies student comments by criticality.<br/>
A Python API processes the generated reports and prepares the data for Power BI, with automated backup for historical traceability.</p>
<p><code>Canvas API</code> <code>Power Automate</code> <code>Dataverse</code> <code>AI Builder</code> <code>Python</code> <code>FastAPI</code> <code>SharePoint</code> <code>Power BI</code></p>
<p><a href="https://lnkd.in/p/d3YMU27z">Project post</a> · <a href="https://github.com/Jukkss/API_Canvas-report-ingestor">Report ingestion API</a></p>

<br/>

<h3>IEC IT Inventory</h3>
<p><i>Full-stack web application · CRC/IEC, PUC Minas · in production</i></p>
<p>Asset management platform for IT equipment, developed with the CRC/IEC team, centralizing inventory, allocations and audit history.<br/>
Includes automatic auditing, a management dashboard, global search, PDF reports, role-based authentication and a documented REST API.</p>
<p><code>Next.js</code> <code>React</code> <code>TypeScript</code> <code>Prisma</code> <code>PostgreSQL</code> <code>Supabase</code> <code>NextAuth</code> <code>Jest</code> <code>Playwright</code> <code>GitHub Actions</code></p>
<p><a href="https://lnkd.in/p/diYVpgF7">Project post</a> · <a href="https://github.com/Jukkss/Inventory-IEC">Repository</a></p>

<br/>

<h2>Currently</h2>

<p>Microsoft certification path: <b>DP-700</b> Fabric Data Engineer, <b>AZ-104</b> Azure Administrator, <b>AI-103</b> Azure AI Apps and Agents<br/>
Migrating pipeline execution from GitHub Actions to Azure</p>

<br/>
<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/footer-dark.svg"/><img src="./assets/footer-light.svg" width="100%" alt="João Victor Soares, @jukkss"/></picture>

</div>
