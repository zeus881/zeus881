<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Sanjay Kumar — Software Engineer. Backend, real-time IoT, cloud and AI automation."/>

<p>
<a href="https://zeus881.github.io"><img src="https://img.shields.io/badge/Interactive%203D%20Portfolio-Open-7F77DD?style=for-the-badge&logo=githubpages&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/sanjay-kumar-7689531b5/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://sanjaykumar-potfolio.netlify.app"><img src="https://img.shields.io/badge/Portfolio-Visit-1D9E75?style=for-the-badge&logo=netlify&logoColor=white"/></a>
<a href="mailto:sanjaykumarr99009@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<img src="https://komarev.com/ghpvc/?username=zeus881&color=7F77DD&style=flat-square&label=PROFILE+VIEWS"/>
<img src="https://img.shields.io/github/followers/zeus881?style=flat-square&color=7F77DD&label=FOLLOWERS"/>

</div>

<br/>

<div align="center">
<img src="./assets/terminal.svg" width="88%" alt="Terminal intro: whoami, focus, MQTT sync to 100+ shelf labels, defence projects"/>
</div>

## About me

I build **systems that run in the real world** — live IoT fleets, secure containerised platforms, defence-grade algorithms, and AI tools that help businesses decide faster.

- 🔭 **Now:** real-time retail automation at **Rebhu Computing** with Elixir/Phoenix, MQTT, Docker and local LLMs
- 🛡️ **Before:** led **defence software projects with the Ministry of Defence** at Yottec System
- 🧩 **I care about:** clean architecture, fault tolerance, and security by default
- 🌱 **Exploring:** distributed Elixir/OTP, event-driven architecture, local LLMs in production
- 🤝 **Open to:** backend, platform and IoT engineering roles and collaborations

## Experience & impact

<table>
<tr>
<td width="50%" valign="top">

### Rebhu Computing Pvt. Ltd.
**Software Engineer** · *Feb 2026 – Present*

- ⚡ Architected **real-time price & barcode sync for 100+ Electronic Shelf Labels** over MQTT with Elixir/Phoenix, removing manual shelf updates
- 🔐 Shipped **secure containerised services** on Docker & Podman behind **Keycloak OAuth2 + RBAC**
- 🤖 Built an **AI client targeting & ranking engine** with Python, Ollama and Streamlit that keeps data on-prem

</td>
<td width="50%" valign="top">

### Yottec System LLP
**Junior Engineer – Project Coordinator** · *Jan 2025 – Feb 2026*

- 🛡️ Led **defence software projects with the Ministry of Defence**
- 🧮 Designed **real-time algorithms** for mission-critical workflows
- ☁️ Built **Python + AWS automation tools** to cut repetitive manual work
- 📋 Ran **Agile/Scrum** ceremonies and implementation planning

<sub>Defence work details are confidential.</sub>

</td>
</tr>
</table>

## How I build: real-time ESL pipeline

```mermaid
flowchart LR
    A[Retail backend / POS] -->|price & barcode updates| B[Phoenix app<br/>Elixir/OTP]
    B -->|publish| C[(MQTT broker)]
    C -->|subscribe| D1[ESL device 1]
    C --> D2[ESL device 2]
    C --> D3[100+ devices]
    B --> E[Keycloak<br/>OAuth2 + RBAC]
    B --> F[(PostgreSQL)]
    subgraph Docker / Podman
      B
      E
      F
    end
```

## Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,elixir,js,ts,html,css,phoenix,react,nodejs,django,tailwind&perline=11&theme=dark" />
<br/><br/>
<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,linux,git,postgres,mysql,mongodb&perline=11&theme=dark" />
<br/><br/>
<img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white"/>
<img src="https://img.shields.io/badge/Podman-892CA0?style=for-the-badge&logo=podman&logoColor=white"/>
<img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>

</div>

| Area | What I do |
|---|---|
| 🏗️ **Solution architecture** | Microservices, event-driven design, distributed systems |
| ⚙️ **Backend engineering** | REST APIs, real-time IoT, system integration |
| ☁️ **Cloud** | AWS: EC2, Lambda, S3, DynamoDB, API Gateway, IAM |
| 🤖 **AI & automation** | Local LLMs, NLP, hybrid web crawling |
| 🔒 **Security** | OAuth2, RBAC, Keycloak, container hardening |
| 📋 **Delivery** | Agile/Scrum, technical documentation, DSA |

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🏷️ Retail ESL automation
Real-time price & barcode sync across **100+ IoT shelf labels** on Elixir's fault-tolerant OTP.

`Elixir` `Phoenix` `MQTT` `Docker`

</td>
<td width="50%" valign="top">

### 🎯 AI client targeting
LLM-powered client ranking that runs **fully local** with Ollama, so private data never leaves the network.

`Python` `Ollama` `Streamlit`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛒 [Cubboard4u.com](https://cubboard4u.com)
Interactive e-commerce platform with a clean UI and smooth shopping flow.

`React` `Node.js` `MongoDB` `Tailwind`

</td>
<td width="50%" valign="top">

### 🎨 AI art generator
Cloud-based AI art creator with NFT integration.

`Python` `AWS` `AI APIs`

</td>
</tr>
</table>

## Contributions in 3D

<div align="center">

<img src="./profile-3d-contrib/profile-night-rainbow.svg" width="100%" alt="3D contribution graph"/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=zeus881&theme=tokyonight" height="165px"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=zeus881&theme=tokyonight" height="165px"/>

<img src="https://streak-stats.demolab.com?user=zeus881&theme=tokyonight&hide_border=true" width="70%"/>

</div>

## Certifications & education

<table>
<tr>
<td width="50%" valign="top">

- 🏅 Full Stack Web Development — *Internshala*
- 🏅 Python Programming — *Mapping Skills Institute*
- 🏅 AWS Cloud Computing — *IIIT Institute*

</td>
<td width="50%" valign="top">

🎓 **B.Tech, Computer Science & Engineering**
Shambhunath Institute of Engineering and Technology, Prayagraj
*2021 – 2024*

</td>
</tr>
</table>

<div align="center">

### Let's build something that scales

<a href="https://zeus881.github.io"><img src="https://img.shields.io/badge/3D%20Portfolio-7F77DD?style=for-the-badge&logo=githubpages&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/sanjay-kumar-7689531b5/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://sanjaykumar-potfolio.netlify.app"><img src="https://img.shields.io/badge/Portfolio-1D9E75?style=for-the-badge&logo=netlify&logoColor=white"/></a>
<a href="mailto:sanjaykumarr99009@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

*"Building systems that don't just work — they scale, secure, and last."*

</div>
