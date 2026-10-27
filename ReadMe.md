<div align="center">
  <img
    src="./assets/header.svg"
    alt="Jamil Alamin Ahmedin — Backend and API Developer, Data Engineering, AI Voice Agents"
    width="100%"
  />

<br/>

<br/>
  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jamil-alamin-ahmedin)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jamil.al.amin1100@gmail.com)
[![DataCamp](https://img.shields.io/badge/Associate_Data_Engineer-03EF62?style=for-the-badge&logo=datacamp&logoColor=black)](https://www.datacamp.com/certificate/DEA0019372604408)

</div>

<img src="./assets/divider.svg" width="100%" alt="" />


## 👋 About Me

I'm an Information Technology graduate (ERP major, University of the Cordilleras, Dec 2025) based in **Jeddah, Saudi Arabia**. I build backend systems and data pipelines that connect reliable APIs, databases, and AI. My current obsession is a real-time **Arabic voice agent** that answers customer calls.

- 🔭 **Building:** an AI Voice Agent Platform with FastAPI, LiveKit, Supabase, and the Google Gemini API
- 🌱 **Learning:** modern data warehousing, advanced cloud data architectures, and SAP S/4HANA Cloud
- 👯 **Collaborating:** open-source data engineering pipelines and complex backend projects
- 🤝 **Looking for help with:** scaling and optimizing real-time voice-streaming workloads
- 💬 **Ask me about:** custom API endpoints, PostgreSQL schemas, AI integrations, and building for Arabic-speaking users

<img src="./assets/divider.svg" width="100%" alt="" />

## 🚀 Featured Project: AI Voice Agent Platform

An AI-powered voice agent that handles **inbound customer calls** in real time. It holds natural **Arabic conversations tailored to the Saudi Najdi dialect**, looks up customers by phone number, and captures leads automatically at the end of each call.

```mermaid
flowchart LR
    C[📞 Caller] -->|real-time audio| L[LiveKit]
    L --> A[FastAPI Agent Service]
    A -->|context + prompt| G[Google Gemini API]
    G -->|Najdi Arabic reply| A
    A <-->|customers · call logs · leads| S[(Supabase / PostgreSQL)]
    A -->|common phrases| M[🔊 Audio cache<br/>23 pre-rendered MP3s]
    M --> L
    A -->|streamed reply| L
    L --> C
```

| | |
| :-- | :-- |
| **Highlights** | 12+ FastAPI REST endpoints for call-session management, CRM lookup by phone number, lead capture, and business knowledge retrieval · pre-rendered audio cache for instant playback of common phrases |
| **Stack** | `Python` `FastAPI` `Next.js` `LiveKit` `Supabase` `Google Gemini API` |
| **Status** | 🟢 In active development |

🔗 **[View the repository →](https://github.com/Ahmedin-Jamil/AI_VoiceAgent?tab=repositories)** <!-- TODO: replace with the direct repo link -->

<img src="./assets/divider.svg" width="100%" alt="" />

## 📌 More Projects

| Project | What it does | Stack |
| :-- | :-- | :-- |
| **🐾 Baguio Pet Boarding System**<br/><sub>Capstone</sub> | Online booking and reservation app for a local pet boarding business. **Adopted by the business for live operations** to organize customer bookings and pet stay schedules. | `React` `Express.js` `PostgreSQL` |
| **🧠 AI Student Support Platform**<br/><sub>Internship @ OSAS</sub> | CBT-based mindset tools, weekly mood tracking, and confidential feedback. Hugging Face sentiment and emotion analysis flags urgent concerns, and context-aware routing sends feedback to the right department. | `Hugging Face` `Supabase` `Python` |
| **📈 Real-Time Data Streaming Pipeline**<br/><sub>Guided technical project</sub> | Automated pipeline pulling live stock quotes via API, streaming them into Snowflake, and transforming raw data into clean analytical tables with dbt for Power BI dashboards. | `Kafka` `Airflow` `Snowflake` `dbt` `Power BI` |

<img src="./assets/divider.svg" width="100%" alt="" />

## 💼 Experience

**AI & Full Stack Developer Intern** · Office of Student Affairs Services, University of the Cordilleras
<sub>Oct 2025 – Dec 2025 · Baguio City, Philippines</sub>

- Built an AI-integrated student support platform end to end, with relational schemas in Supabase (PostgreSQL)
- Integrated Hugging Face APIs for sentiment and emotion analysis with automated alerts for urgent student concerns
- Presented workflow improvement suggestions to department leadership
- 🏅 Received a **Certificate of Appreciation** for contributions to the project

<img src="./assets/divider.svg" width="100%" alt="" />

## 💻 Tech Stack

**Languages**<br/>
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![SAP ABAP](https://img.shields.io/badge/SAP_ABAP-0FAAFF?style=flat-square&logo=sap&logoColor=white)

**Backend & APIs**<br/>
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-404d59?style=flat-square&logo=express&logoColor=white)
![LiveKit](https://img.shields.io/badge/LiveKit-000000?style=flat-square&logo=livekit&logoColor=white)

**Data Engineering**<br/>
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Databases & Cloud**<br/>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0072C6?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure Data Factory](https://img.shields.io/badge/Data_Factory-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure Synapse](https://img.shields.io/badge/Synapse_Analytics-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**AI & Frontend**<br/>
![Google Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)

**Enterprise Systems & Tools**<br/>
![SAP S/4HANA](https://img.shields.io/badge/SAP_S/4HANA-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![SAP Fiori](https://img.shields.io/badge/SAP_Fiori-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-121011?style=flat-square&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

<img src="./assets/divider.svg" width="100%" alt="" />

## 🎓 Education & Certifications

**B.S. Information Technology, Major in Enterprise Resource Planning**<br/>
University of the Cordilleras · Graduated December 2025<br/>
<sub>Coursework: SAP Configuration (Fiori, ABAP), Enterprise Business Process Lifecycles (P2P, O2C, R2R), Database Systems</sub>

| Certification | Issuer | Date |
| :-- | :-- | :-- |
| 🏆 **Associate Data Engineer** | DataCamp | Sep 2026 |
| Building a Modern Data Warehouse Bootcamp | Udemy | Apr 2026 |
| SAP Analytics Cloud Enablement Session | SAP Southeast Asia & ASEAN Foundation | May 2025 |
| Managing Clean Core for SAP S/4HANA Cloud | SAP Learning Hub | Sep 2024 |

<img src="./assets/divider.svg" width="100%" alt="" />

## 🗣️ Languages

| Language | Level |
| :-- | :-- |
| Arabic | Native |
| Tigrinya | Native |
| English | Fluent |
| German | A1 |

<img src="./assets/divider.svg" width="100%" alt="" />

## 📊 What I Write

<div align="center">

<img height="170" src="https://github-readme-stats.shion.dev/api/top-langs/?username=Ahmedin-Jamil&theme=tokyonight&hide_border=true&layout=compact&hide=jupyter%20notebook" alt="Top languages" />

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

<div align="center">

### 📫 Let's build something together

Open to backend, data engineering, and AI integration collaborations.<br/>
**[Message me on LinkedIn](https://linkedin.com/in/jamil-alamin-ahmedin)** or **[send an email](mailto:jamil.al.amin1100@gmail.com)**

</div>
