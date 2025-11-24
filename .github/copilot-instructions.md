````instructions
# GitHub Profile README - AI Agent Instructions

## Project Overview
This is a **GitHub Profile README** repository (tiagomachadojardim/tiagomachadojardim) that displays on the GitHub profile page. The README showcases professional identity, technical skills, and contact information for Tiago Jardim - CEO of BienTech, focused on health technology solutions.

## Repository Structure
```
tiagomachadojardim/
└── README.md          # Main profile display (renders on github.com/tiagomachadojardim)
```

## Architecture & Patterns

### Content Organization
The README follows a structured markdown format:
1. **Header Section**: Name, professional titles, current roles
2. **Social Links**: LinkedIn, Instagram, BienTech website with shields.io badges
3. **Tech Stack**: DevIcon CDN icons displayed in grid layout
4. **GitHub Statistics**: Stats, top languages, and streak using github-readme-stats and streak-stats
5. **Featured Projects**: Showcase of main projects (PulmoFlow, PulmoScan, BienTech, Portfolio)
6. **Contact Section**: Call-to-action for collaborations

### Icon Standards
- **Social badges**: Use [shields.io](https://shields.io) with `style=for-the-badge`
- **Tech icons**: Use [DevIcon CDN](https://cdn.jsdelivr.net/gh/devicons/devicon/) with 40x40px dimensions
- **GitHub Stats**: Use [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) with tokyonight theme and transparent background (bg_color=0d1117)

### Tech Stack Alignment
Current tech stack reflects actual project usage:
- **Frontend**: Flutter (mobile), React/Next.js/Vue (web)
- **Backend**: Laravel (PHP), Node.js
- **Styling**: Tailwind CSS, Bootstrap, SASS
- **Databases**: MySQL, PostgreSQL, Firebase
- **Languages**: JavaScript, TypeScript, PHP, Dart, Python, C, Java

### Design Principles
- **Professional tone**: Portuguese (pt-BR) for Brazilian audience
- **Visual hierarchy**: Clear sections separated by horizontal rules (`---`)
- **Badge consistency**: All social/tech badges follow uniform styling
- **Responsive**: Markdown renders well on desktop and mobile GitHub

## Development Workflow

### Updating Content

#### Adding New Technologies
Use DevIcon CDN pattern:
```html
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/[tech]/[tech]-original.svg" 
     alt="[Tech Name]" width="40" height="40"/>
```
Browse available icons at [devicon.dev](https://devicon.dev)

#### Adding Social Links
Use shields.io pattern:
```html
<a href="[URL]" target="_blank">
  <img src="https://img.shields.io/badge/[Label]-[Color]?style=for-the-badge&logo=[logo]&logoColor=white" 
       alt="[Alt Text]">
</a>
```

#### Updating GitHub Stats
Stats are enabled with three cards:
```html
<!-- Main stats + Top Languages -->
<img src="https://github-readme-stats.vercel.app/api?username=tiagomachadojardim&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="GitHub Stats" height="180"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tiagomachadojardim&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top Languages" height="180"/>

<!-- Streak stats -->
<img src="https://github-readme-streak-stats.herokuapp.com/?user=tiagomachadojardim&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub Streak"/>
```
Customize with [github-readme-stats options](https://github.com/anuraghazra/github-readme-stats#customization)

### Git Workflow
- **Direct commits to main**: Simple updates pushed directly (no PR workflow for personal profile)
- **Commit messages**: Descriptive, e.g., "Update README.md" or "Add new technology icons"
- **Testing**: Preview changes locally or via GitHub's file editor preview

## Key Information

### Professional Context
- **Current Role**: CEO and Founder of BienTech
- **Focus Area**: Health technology, respiratory physiotherapy, spirometry
- **Tech Stack**: Full Stack development (Mobile + Web), SaaS platforms
- **Education**: ADS graduate (UniCesumar), Computer Engineering student (UNIPAMPA)

### Related Projects (Context Only)
Referenced in workspace but not part of this repo:
- **PulmoFlow Platform**: Laravel SaaS with subscription management (private)
- **PulmoScan**: Laravel admin portal + Flutter multiplatform app for spirometry (private)
- **RespiroScan**: Flutter mobile app for respiratory physiotherapy (private)
- **BienTech Website**: React corporate site at bientech.com.br
- **Personal Portfolio**: Next.js site deployed at meu-portifolio-qtwy.onrender.com
- **API Hub App**: React 19 + TypeScript hub with 8 public API integrations (public)
- **Portal Rick and Morty**: Vue 3 + GraphQL interactive explorer (public)
- **Yu-Gi-Oh! Explorer**: React + TypeScript card search application (public)

## Conventions

### Language
- **Primary**: Portuguese (pt-BR) for all textual content
- **Code**: English for HTML attributes and technical terms

### Formatting
- **Markdown**: GitHub Flavored Markdown (GFM)
- **HTML tags**: Use for precise control (badges, images, links with target="_blank")
- **Alignment**: Use `<p align="center">` for stats, `<p align="left">` for tech icons

### Asset Management
- **External CDNs**: All assets use CDNs (DevIcon, shields.io, github-readme-stats)
- **No local assets**: Repository contains only README.md (clean structure)
- **Image URLs**: Always use HTTPS, ensure high availability

### Featured Projects Format
Each project follows this structure:
```markdown
### [emoji] **Project Name** - Brief Description
Detailed description with key features.
- **Stack**: Technologies used
- **Plataformas/Features**: Key highlights
- 🔗 [Ver online](URL) OR 🔒 Projeto privado
```

**Project Status Indicators**:
- `🔗 [Ver online](URL)`: Public project with live demo
- `🔗 [Visite o site](URL)`: Corporate/production website
- `🔒 Projeto privado`: Private repository or proprietary project

## Quick Edits

### Update Bio
Edit lines 3-6 in README.md (education, role, tech focus)

### Add/Remove Technology
Modify the `<p align="left">` section in the "Tecnologias e Ferramentas" section

### Change Social Links
Update `<a href>` tags in the "Minhas Conexões" section

### Update GitHub Stats
Modify theme, hide specific stats, or change layout in the "Estatísticas GitHub" section

### Add/Update Featured Projects
Add new projects to the "Projetos em Destaque" section following the established format

## Notes
- This README renders **only** on the profile page (github.com/tiagomachadojardim)
- Changes reflect immediately after push (no build process)
- GitHub Stats are dynamically generated - no maintenance required
- Repository links in featured projects point to profile (update with specific repo URLs when public)
- Consider adding: detailed project READMEs, blog posts section, certifications
````