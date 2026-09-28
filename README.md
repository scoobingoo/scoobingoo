<div align="center">

# Hey there! I'm Son <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>

### `Full-Stack Developer` | `React Native & Laravel` | `RAG & AI Agents`

[![GitHub](https://img.shields.io/badge/GitHub-scoobingoo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/scoobingoo)
[![Gmail](https://img.shields.io/badge/Gmail-soniclee2004-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:soniclee2004@gmail.com)
[![Location](https://img.shields.io/badge/Ho_Chi_Minh_City-6C63FF?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6C63FF&center=true&vCenter=true&random=false&width=650&lines=Shipping+Production+Features+End+to+End;React+Native+%2B+Laravel+%2B+FastAPI;Building+RAG+Systems+%26+AI+Agents" alt="Typing SVG" />

</div>

---

## About Me

* Currently shipping Localis, a Vietnam travel app live on iOS, Android & web from one Expo codebase
* Built the MISA accounting & VAT e-invoice integration behind phuochung.net
* Experienced in RAG systems across FastAPI, Laravel & MariaDB vector search
* B.S. Software Engineering at UEH — GPA 3.62/4.0, High Distinction
* Always exploring the intersection of AI and real-world products

---

## Core Skills

**Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black) ![Expo](https://img.shields.io/badge/Expo_SDK_57-000020?style=flat-square&logo=expo&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Livewire](https://img.shields.io/badge/Livewire_4-FB70A9?style=flat-square&logo=livewire&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**

![Laravel](https://img.shields.io/badge/Laravel_12-FF2D20?style=flat-square&logo=laravel&logoColor=white) ![PHP](https://img.shields.io/badge/PHP_8.2-777BB4?style=flat-square&logo=php&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**AI**

![RAG](https://img.shields.io/badge/RAG_Pipelines-6C63FF?style=flat-square) ![bge-m3](https://img.shields.io/badge/bge--m3_Embeddings-6C63FF?style=flat-square) ![HNSW](https://img.shields.io/badge/HNSW_Vector_Search-6C63FF?style=flat-square) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white) ![SSE](https://img.shields.io/badge/SSE_Streaming-6C63FF?style=flat-square) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)

**Infrastructure**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx_+_systemd-009639?style=flat-square&logo=nginx&logoColor=white) ![EAS](https://img.shields.io/badge/EAS_Build_and_Update-000020?style=flat-square&logo=expo&logoColor=white) ![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)

---

## Work Experience

### <img src="https://img.shields.io/badge/IM_GROUP-6C63FF?style=flat-square" /> Ho Chi Minh City

*Joined as an intern in Oct 2024 and grew into the junior team — two years across hotel operations, market-data systems, trading automation and AI products.*

#### Junior Software Developer &nbsp;`Nov 2025 - Present`

**Localis — travel app on iOS, Android and web** &nbsp;·&nbsp; `Jul 2026 - Present` &nbsp;·&nbsp; 131 commits

- Own the Explore/Nearby map end to end on GrabMaps vector tiles — hero-image markers, GeoJSON radius circle, a 0-50 km slider, category and province filters, and bounding-box queries instead of loading every place
- Fixed the platform bugs that came with it: white screen on both iOS and Android, a WebView reload stall solved by memoising the source, and slider jitter rewritten with PanResponder
- Ship from a single Expo codebase to all three platforms via EAS Update, trunk-based with feature flags

**phuochung.net — e-commerce with MISA accounting integration** &nbsp;·&nbsp; `May 2026 - Sep 2026` &nbsp;·&nbsp; 40 commits

- Built server-side order synchronisation to MISA MShopKeeper, with a manual re-sync action in the admin panel
- Built hourly MISA eShop inventory sync and documented the sync architecture for the team
- Implemented the VAT e-invoice flow at checkout — invoice form, business-name and address splitting, and normalisation of MISA administrative addresses
- Added admin email alerts when a MISA sync fails, and fixed the SePay webhook 500 that broke VAT invoice sync
- Built a secret log viewer console for production debugging: pagination, realtime polling and level tabs

**Localis Platform — RAG travel-advisory system** &nbsp;·&nbsp; `Jun 2026 - Jul 2026` &nbsp;·&nbsp; 19 commits

- Built the Agents CRUD subsystem and a ChatGPT-style chat interface over the retrieval pipeline — server-rendered Jinja2, no SPA
- Rendered streamed model output safely with highlight.js and DOMPurify, and fixed an IME bug that split Vietnamese characters mid-composition
- Tuned generation limits against exact token counting so long retrieved context stopped truncating answers

**Brandtree — AI brand-strategy SaaS** &nbsp;·&nbsp; `Jan 2026 - Mar 2026` &nbsp;·&nbsp; 35 commits

- Built the agent output layer — persisting output for five system agents and syncing it into the UI without a page reload
- Implemented brief-summary generation with versioned prompt migrations and polling for the generated result
- Reworked the popup UX across the app: scroll locking, dismiss-on-outside-click, and reusing the brand-info view to render conversation output

#### Fresher Developer &nbsp;`May 2025 - Oct 2025`

- Built internal CRUD modules and admin panels in Laravel + Filament — users, roles, permissions and content management
- Wrote REST endpoints with form-request validation, plus factories and seeders so QA could reset state on demand
- Added file uploads to S3 and Excel export reporting for internal operations tools
- Handled first-line bug triage across two client projects, from reproduction to fix and regression check

#### Software Development Intern &nbsp;`Oct 2024 - Apr 2025`

- Built internal admin screens in Laravel — forms, tables, filters and pagination — working from the team's existing Figma designs
- Built a small reusable component library and a marketing landing page in React + Tailwind
- Wrote seeders and fixtures so the team could reset demo data, and cleared UI bugs across two internal tools
- Picked up the team's trunk-based workflow: feature branch, pull request, review, merge

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**Localis — travel app with AI agentic chat** | *Jul 2026 - Present*

Live on **iOS, Android and web from one codebase** via EAS Update. **131 commits** across a three-service monorepo.

Built the Explore/Nearby map end to end on **GrabMaps vector tiles**: hero-image markers, GeoJSON radius circle, a 0–50 km slider, category and province filters that follow the user across screens, and bounding-box queries instead of loading every place. Fixed the bugs it shipped with — white screen on both platforms, a WebView reload stall solved by memoising the source, and slider jitter rewritten with PanResponder.

`Expo React Native (SDK 57)` `Laravel 12 + Filament` `Node 22 Fastify + SSE`

[![Live](https://img.shields.io/badge/Live-app.localis.vn-6C63FF?style=flat-square)](https://app.localis.vn)

</td>
<td width="50%" valign="top">

**Localis Platform — RAG travel-advisory system** | *Jun 2026 - Jul 2026*

Built the **Agents CRUD subsystem** and a ChatGPT-style chat interface over the retrieval pipeline — server-rendered Jinja2, no SPA.

Rendered streamed model output safely with highlight.js + DOMPurify, collapsible instructions, and an IME fix so Vietnamese typing stopped splitting characters mid-composition. Tuned generation limits against **exact token counting** (article 1,500, system 1,800) so long retrieved context stopped truncating answers.

`FastAPI` `MariaDB 12.3 VECTOR + HNSW` `bge-m3 (CPU, FP16)` `Gemini Flash` `Jinja2`

[![Live](https://img.shields.io/badge/Live-platform.localis.vn-6C63FF?style=flat-square)](https://platform.localis.vn)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**phuochung.net — e-commerce with MISA accounting integration** | *May 2026 - Sep 2026*

Built the **MISA integration** end to end: server-side order sync to MShopKeeper, hourly eShop inventory sync, an admin-triggered re-sync action, and email alerts to admins when a sync fails.

Implemented the **VAT e-invoice flow** at checkout — invoice form, business-name and address splitting, and normalised MISA administrative addresses. Fixed the SePay webhook 500 that broke invoice sync, and built a secret log viewer console for production debugging.

`Laravel` `MISA MShopKeeper + eShop APIs` `SePay` `Docker`

[![Live](https://img.shields.io/badge/Live-phuochung.net-6C63FF?style=flat-square)](https://phuochung.net)

</td>
<td width="50%" valign="top">

**Brandtree — AI brand-strategy SaaS** | *Jan 2026 - Mar 2026*

Built the **agent output layer** — persisting generated output for five system agents and syncing it into the UI without a page reload.

Implemented brief-summary generation driven by versioned prompt migrations with polling for the result, and reworked the popup UX across the app: scroll locking, dismiss-on-outside-click, and reusing the brand-info view to render conversation output.

`Laravel 12` `Livewire 4` `Stimulus` `Blade`

[![Live](https://img.shields.io/badge/Live-ai.caythuonghieu.com-6C63FF?style=flat-square)](https://ai.caythuonghieu.com)

</td>
</tr>
</table>

---

## GitHub Stats

<div align="center">

<img height="180" src="https://streak-stats.demolab.com/?user=scoobingoo&hide_border=true&background=0D1117&stroke=30363D&ring=6C63FF&fire=6C63FF&currStreakLabel=6C63FF&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E" alt="GitHub streak" />
<img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=scoobingoo&theme=github_dark&utcOffset=7" alt="Commits by hour" />

</div>

---

<div align="center">

[![Email](https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:soniclee2004@gmail.com)

<img src="https://komarev.com/ghpvc/?username=scoobingoo&color=6C63FF&style=flat-square&label=Profile+Views" />

</div>
