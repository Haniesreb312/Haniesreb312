<!-- ==================== HEADER ==================== -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:164E63,100:2563EB&height=220&section=header&text=Hani%20Esreb&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineering%20%7C%20Data%20Science%20%7C%20AI&descAlignY=60&descSize=17" alt="Hani Esreb - Developer Profile"/>

<a href="https://github.com/Haniesreb312">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=38BDF8&center=true&vCenter=true&width=650&lines=MSc+Data+Science+%40+TU+Wien;Computer+Science+Engineer;Building+Software+%26+Intelligent+Systems;Turning+Data+Into+Meaningful+Insights;Always+Learning.+Always+Building." alt="Software Engineering, Data Science and AI"/>
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hani-esreb-b76b412a4)
[![Email](https://img.shields.io/badge/Email-Contact_Me-0078D4?style=for-the-badge&logoColor=white)](mailto:haniassreb@hotmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Haniesreb312)

![Location](https://img.shields.io/badge/Location-Vienna%2C_Austria-DC2626?style=flat-square)
![Status](https://img.shields.io/badge/Status-Open_to_Work-22C55E?style=flat-square)
![Education](https://img.shields.io/badge/MSc-TU_Wien-2563EB?style=flat-square)

</div>

<!-- ==================== ABOUT ==================== -->

## 👨‍💻 A Little About Me

I'm a Computer Science Engineer currently pursuing my Master's in Data Science at TU Wien, Austria.

I enjoy working at the intersection of software engineering, artificial intelligence and data science — building applications, exploring data and figuring out how technology can solve practical problems.

My background also includes hands-on IT support, full-stack development and working in Agile teams.

```python
class HaniEsreb:

    def __init__(self):
        self.location = "Vienna, Austria"

        self.education = {
            "MSc": "Data Science @ TU Wien",
            "BSc": "Computer Science Engineering",
            "GPA": "4.53 / 5.00"
        }

        self.languages = ["Arabic", "English"]

        self.interests = [
            "Software Engineering",
            "Artificial Intelligence",
            "Data Science",
            "Backend Development"
        ]

        self.open_to_work = True

    def current_mission(self):
        return "Learn. Build. Improve. Repeat."


developer = HaniEsreb()
print(developer.current_mission())
```

<!-- ==================== TECH STACK ==================== -->

## 🛠️ Technical Arsenal

<div align="center">

### Programming Languages

<a href="https://dev.java/">
  <img src="https://skillicons.dev/icons?i=java" width="48" alt="Java"/>
</a>
<a href="https://www.python.org/">
  <img src="https://skillicons.dev/icons?i=python" width="48" alt="Python"/>
</a>
<a href="https://www.r-project.org/">
  <img src="https://skillicons.dev/icons?i=r" width="48" alt="R"/>
</a>
<a href="https://www.typescriptlang.org/">
  <img src="https://skillicons.dev/icons?i=ts" width="48" alt="TypeScript"/>
</a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">
  <img src="https://skillicons.dev/icons?i=js" width="48" alt="JavaScript"/>
</a>
<a href="https://www.mathworks.com/products/matlab.html">
  <img src="https://skillicons.dev/icons?i=matlab" width="48" alt="MATLAB"/>
</a>

### Frontend Development

<img src="https://skillicons.dev/icons?i=react,html,css,bootstrap,tailwind,vite" alt="Frontend technologies"/>

### Backend Development

<img src="https://skillicons.dev/icons?i=spring,nodejs,java" alt="Backend technologies"/>

### Databases & Infrastructure

<img src="https://skillicons.dev/icons?i=postgres,docker,git,github" alt="Databases and infrastructure"/>

### Development Environment

<img src="https://skillicons.dev/icons?i=idea,vscode,pycharm" alt="Development tools"/>

### Data Science & Artificial Intelligence

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![LLMs](https://img.shields.io/badge/Large_Language_Models-6366F1?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-0891B2?style=for-the-badge)
![ML](https://img.shields.io/badge/Machine_Learning-F59E0B?style=for-the-badge)
![ggplot2](https://img.shields.io/badge/ggplot2-276DC3?style=for-the-badge&logo=r&logoColor=white)

</div>

<!-- ==================== PROJECTS ==================== -->

## 🚀 Selected Projects

### 🩺 HealthAI — AI-Powered Symptom Checker

A full-stack healthcare research application exploring how artificial intelligence and retrieval-augmented generation can support symptom assessment.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<details>
<summary><b>🔍 Explore the architecture</b></summary>

<br/>

```mermaid
flowchart TD
    A[User Interface - React] --> B[Spring Boot REST API]
    B --> C[Spring AI]
    C --> D[Vector Similarity Search]
    D <--> E[(PostgreSQL + pgvector)]
    D --> F[Retrieved Context]
    F --> G[Ollama Language Model]
    G --> H[Generated Response]
    H --> B
    B --> A
```

**Technical highlights**

- Retrieval-Augmented Generation architecture
- Local large language model integration
- Vector embeddings and similarity search
- RESTful backend services
- OAuth 2.0 and Keycloak authentication
- Containerized infrastructure with Docker
- Responsive TypeScript frontend

</details>

[📄 Read my bachelor's thesis](https://hdl.handle.net/2437/404358)

> Academic research project — not intended to replace professional medical advice.

---

### 🌍 TerraScope — AI-Powered Country Explorer

An interactive platform combining artificial intelligence and external APIs to provide country profiles, comparisons and real-time information.

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-886FBF?style=flat-square&logo=googlegemini&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

<details>
<summary><b>🔍 Explore project features</b></summary>

<br/>

- AI-generated country insights
- Interactive maps
- Economic data visualization
- Real-time weather information
- Currency conversion
- News aggregation
- Multilingual country profiles
- Responsive user interface

</details>

---

### 📈 WealthWise — Financial Planning Platform

A collaborative web application designed to help users manage budgets, investment portfolios and retirement planning.

![Frontend](https://img.shields.io/badge/Frontend_Development-2563EB?style=flat-square)
![UI](https://img.shields.io/badge/UI_Design-8B5CF6?style=flat-square)
![Agile](https://img.shields.io/badge/Agile_Scrum-22C55E?style=flat-square)

<details>
<summary><b>🔍 Explore my contributions</b></summary>

<br/>

- Frontend development and UI design
- User stories and requirements definition
- Sprint planning and backlog refinement
- Cross-functional team collaboration
- Sprint reviews and retrospectives
- Iterative development based on feedback

</details>

<div align="center">

[![Explore Repositories](https://img.shields.io/badge/Explore_All_Repositories-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Haniesreb312?tab=repositories)

</div>

<!-- ==================== EDUCATION ==================== -->

## 🎓 Education & Professional Background

| Institution | Qualification | Period |
|---|---|---|
| 🇦🇹 **TU Wien** | MSc Data Science | 2026 – Present |
| 🇭🇺 **University of Debrecen** | BSc Computer Science Engineering | Graduated 2026 |

**Bachelor's GPA:** 4.53 / 5.00 — Excellent

<details>
<summary><b>🏅 Certifications</b></summary>

<br/>

- IBM — Data Fundamentals
- IBM — Generative AI Essentials: Using LLMs to Work with Data
- IT Specialist — Databases
- IT Specialist — Networking
- IT Specialist — JavaScript
- IT Specialist — HTML and CSS
- IT Specialist — HTML5 Application and Development
- IT Specialist — Device Configuration and Management

</details>

<details>
<summary><b>💼 Professional experience</b></summary>

<br/>

**IT Support Assistant — SYSTEM Ceramic & Marble**

Remote | June 2024 – Present

- Hardware and software troubleshooting
- Company email account management
- Remote employee technical support
- Data organization and daily IT operations

**IT Specialist Intern — CFI Global Talent**

Budapest, Hungary | April 2025 – July 2025

- Employee technical support
- Computer hardware installation and maintenance
- Assistance with data management

</details>

<!-- ==================== CURRENT WORK ==================== -->

## 🔬 Currently Exploring

```yaml
current_focus:
  university: TU Wien
  programme: MSc Data Science

  learning:
    - Statistical Modelling
    - Machine Learning
    - Data Visualization
    - Knowledge Representation
    - Intelligent Systems

  building:
    - Full-stack applications
    - Data analysis projects
    - AI-powered solutions

  career:
    location: Vienna, Austria
    available_for:
      - Working Student Positions
      - Internships
      - Junior Engineering Roles
      - Research Opportunities
```

<!-- ==================== STATISTICS ==================== -->

## 📊 GitHub Analytics

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Haniesreb312&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github"/>
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=Haniesreb312&show_icons=true&theme=default&hide_border=true&rank_icon=github" alt="GitHub statistics"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Haniesreb312&layout=compact&theme=tokyonight&hide_border=true"/>
  <img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Haniesreb312&layout=compact&theme=default&hide_border=true" alt="Most used languages"/>
</picture>

<br/><br/>

<img width="70%" src="https://streak-stats.demolab.com?user=Haniesreb312&theme=transparent&hide_border=true" alt="GitHub contribution streak"/>

<details>
<summary><b>📈 Contribution activity</b></summary>

<br/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=Haniesreb312&theme=github-compact&hide_border=true&area=true" alt="Contribution activity graph"/>

</details>

</div>

<!-- ==================== CONTACT ==================== -->

## 🤝 Let's Build Something

I'm currently open to professional opportunities in Vienna, particularly in software engineering, data science, AI and technical operations.

Whether it's a research project, an engineering challenge or an interesting collaboration, I'm always happy to connect.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hani-esreb-b76b412a4)
[![Email](https://img.shields.io/badge/Get_In_Touch-0078D4?style=for-the-badge)](mailto:haniassreb@hotmail.com)

**English — C1 | Arabic — Native**

<br/>

<sub>Curiosity drives learning. Consistency drives progress.</sub>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:164E63,100:2563EB&height=120&section=footer" alt="Footer"/>

</div>
