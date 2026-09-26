<h1 align="center">Hi 👋, I'm Oussema Arfaoui</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&pause=1000&color=2EE6A6&center=true&vCenter=true&width=700&lines=Software+Engineering+Student;Java+%7C+Spring+Boot+%7C+Angular+Developer;Building+Maintainable+Full-Stack+Applications;Exploring+AI-Powered+Software+Solutions" alt="Typing SVG" />
</p>


---

## 👨‍💻 About Me

```java
public class OussemaArfaoui extends Student implements Developer {

    // Academic Profile
    private final String institution =
        "Higher Institute of Computer Science of Ariana (ISI Ariana)";

    private final String specialization =
        "Software Engineering & Information Systems (IDL)";

    // Core Technical Stack (industry-oriented)
    private final String[] technicalFocus = {
        "Java",
        "Spring Boot",
        "Angular",
        "SQL",
        "REST APIs",
        "Git",
        "Docker"
    };

    // Engineering mindset (realistic and professional framing)
    private final String engineeringFocus =
        "Building maintainable, secure, and well-structured enterprise applications using clean architecture principles";

    @Override
    public String[] getInterests() {
        return new String[] {
            "Developing Reliable Full-Stack Web Applications",
            "Backend Development & Software Architecture",
            "Object-Oriented Design & Clean Code Practices",
            "AI Integration in Software Systems"
        };
    }

    @Override
    public void run() {
        while (isCurious()) {
            learn();
            build();
            improve();
        }
    }

    // Optional improvement method for realism (more professional than abstract loops)
    private void improve() {
        refactor();
        writeTests();
        optimize();
    }
    private void writeTests() {
        // ensure reliability and maintainability
    }

    private void optimize() {
        // performance + structure improvements
    }

    public static void main(String[] args) {
        OussemaArfaoui developer = new OussemaArfaoui();
        developer.run();
    }
}
```

---
## 🛠️ Technology Stack

**Main Stack**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-005571?style=flat-square&logo=swagger&logoColor=white)

**Familiar with**

![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)

**Tools & Workflow**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![JUnit & Mockito](https://img.shields.io/badge/JUnit_&_Mockito-CC2927?style=flat-square&logo=junit5&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger%20%2F%20OpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![UML](https://img.shields.io/badge/UML_Modeling-FF6600?style=flat-square)
![Agile/Scrum](https://img.shields.io/badge/Agile%2FScrum-0052CC?style=flat-square)

---

## 🚀 Highlighted Projects

<table width="100%" border="0">
  <tr>
    <td width="50%" valign="top">
      <h4>📋 Plateforme de Gestion RH</h4>
      <p><em>🏢 Stage Professionnel — Office National de Télédiffusion</em></p>
      <p>Modernisation complète de la gestion RH : profils, formations, pointage, paie et demandes administratives, avec automatisation documentaire et notifications email.</p>
      <p><strong>Spring Boot · Angular · JWT · MySQL</strong></p>
    </td>
    <td width="50%" valign="top">
      <h4>🏬 Plateforme B2B de Gestion Commerciale</h4>
      <p><em>🏢 Stage de Fin d'Études — SCSI</em></p>
      <p>Catalogue produits hiérarchique et tarification dynamique pilotée par des règles métier (taxes, dates de validité), avec rôles Admin/Client.</p>
      <p><strong>Angular · ASP.NET Core · SQL Server · Entity Framework Core</strong></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>📚 Diffusion de Travaux Scientifiques</h4>
      <p><em>🎓 Projet Académique</em></p>
      <ul align="left">
        <li>API REST sécurisée (JWT, rôles multiples) avec workflow complet de soumission/révision des publications (statut, visibilité, historique d'audit)</li>
        <li>Chatbot RAG interrogeant les publications par recherche vectorielle + reranking (cross-encoder), avec génération via LLM local (Ollama) et réponses systématiquement sourcées (document + page), pour limiter les hallucinations</li>
        <li>Extraction de mots-clés IA à deux niveaux (Gemini, avec repli sur un extracteur local KeyBERT/spaCy)</li>
        <li>Architecture microservices conteneurisée (Spring Boot + 2 services Python FastAPI) orchestrée via Docker Compose, avec pipeline CI</li>
      </ul>
      <p><strong>Spring Boot · Angular · PostgreSQL/pgvector · Docker · JWT</strong></p>
    </td>
    <td width="50%" valign="top">
      <h4>📅 Réservation de Prestations en Ligne</h4>
      <p><em>🎓 Projet Académique</em></p>
      <p>Système de prise de rendez-vous avec disponibilités en temps réel, messagerie intégrée et tableau de bord de performance, déployé via Docker.</p>
      <p><strong>Java · Spring Boot · Angular · MySQL · Docker</strong></p>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center" valign="top">
      <h4>🎮 Mazelex Arena — Jeu de Labyrinthe de Mots</h4>
      <p><em>Projet Personnel — Algorithmique</em></p>
      <p>Labyrinthe généré procéduralement avec détection de mots, modes solo/multijoueur et calcul de chemin optimal via BFS/DFS/A*. Scoring basé sur l'efficacité du parcours.</p>
      <p><strong>Java · JavaFX</strong></p>
    </td>
  </tr>
</table>

---

## 🔭 Current Explorations

- 🤖 **AI-Backend Integration:** Learning how to seamlessly integrate LLMs and smart APIs directly into web backends to build intelligent web features.
- 💬 **Conversational AI & Workflows:** Exploring **LangChain** to build contextual chatbots and structured automation pipelines inside modern applications.

---

## 📫 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/oussema-arfaoui-0549b7230/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:oussemaarfaoui03@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Gmail" /></a>
</p>

---

