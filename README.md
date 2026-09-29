<div align="center">

# Karan Kumar Singh

### Senior Software Engineer · Backend & Distributed Systems

Building reliable backend systems and investigating how software security techniques apply to AI-enabled applications.

<p>
  <img src="https://img.shields.io/badge/Java%20%26%20Spring%20Boot-Backend-376D8C?style=flat-square" alt="Java and Spring Boot backend" />
  <img src="https://img.shields.io/badge/Kafka%20%26%20Data-Distributed%20Systems-7356A8?style=flat-square" alt="Distributed systems" />
  <img src="https://img.shields.io/badge/Program%20Analysis-AI%20Security-1C8C81?style=flat-square" alt="Program analysis and AI security" />
</p>

<table>
  <tr>
    <td align="center" width="33%">
      <a href="mailto:singh.3101karan@gmail.com">
        <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Karan" />
      </a>
    </td>
    <td align="center" width="33%">
      <a href="https://www.linkedin.com/in/karankumarsingh">
        <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Karan on LinkedIn" />
      </a>
    </td>
    <td align="center" width="33%">
      <a href="https://leetcode.com/u/Karan_1999/">
        <img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="Karan on LeetCode" />
      </a>
    </td>
  </tr>
</table>

</div>

---

## Engineering focus

I work on backend architecture, APIs, asynchronous processing, caching, and data systems. My independent projects extend that engineering perspective into **workload-shift evaluation** and **static analysis for LLM data security**.

| Backend systems | Reliability & evaluation | Software security |
| :---: | :---: | :---: |
| Java, Spring Boot, APIs, messaging, persistence | Reproducible experiments, policy comparison, failure scenarios | Data-flow analysis, sensitive-data tracing, policy evaluation |

## Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Karansingh1999/CloudShift-RL">CloudShift-RL ↗</a></h3>
      <p><strong>Resource allocation under changing workloads</strong></p>
      <p>A reproducible Gymnasium benchmark that compares heuristic schedulers with a limited-compute DQN baseline across steady traffic, bursts, memory shifts, and node failures.</p>
      <p><code>Python</code> · <code>Gymnasium</code> · <code>Stable-Baselines3</code> · <code>Experimental evaluation</code></p>
      <p><a href="https://github.com/Karansingh1999/CloudShift-RL">Repository</a> · <a href="https://github.com/Karansingh1999/CloudShift-RL/tree/main/results/v0.2.0">Results</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Karansingh1999/PIIFlow">PIIFlow ↗</a></h3>
      <p><strong>Static analysis for sensitive data in LLM applications</strong></p>
      <p>A Python analyzer that traces sensitive data from its source to LLM API calls, then evaluates detected flows against provider, trust-zone, and sanitizer policies.</p>
      <p><code>Python AST</code> · <code>Taint analysis</code> · <code>YAML policy</code> · <code>AI security</code></p>
      <p><a href="https://github.com/Karansingh1999/PIIFlow">Repository</a> · <a href="https://github.com/Karansingh1999/PIIFlow/blob/main/benchmarks/results/report.md">Benchmark report</a></p>
    </td>
  </tr>
</table>

<details>
<summary><strong>What the evaluations show</strong></summary>
<br />

- **CloudShift-RL:** The repository reports results for four synthetic workload scenarios using matched evaluation seeds. Under its fixed 5,000-step training budget, the DQN baseline was sensitive to training seed and did not outperform the strongest heuristic in that setup. The project is a research simulator, not a production scheduler.
- **PIIFlow:** Its published synthetic flow benchmark contains 90 cases and reports **0.894 overall F1** for the full analyzer. The result describes that benchmark, not a guarantee of detection in arbitrary applications.

</details>

## More implementations

| Area | Repository | What it covers |
| :--- | :--- | :--- |
| **Object design** | [ToDoListLowLevelDesign](https://github.com/Karansingh1999/ToDoListLowLevelDesign) | Java modeling of users, tasks, subtasks, priorities, due dates, status, and progress. |
| **Android · navigation** | [Sharda-Map](https://github.com/Karansingh1999/Sharda-Map) | Campus route-finding application with Firebase-backed information. |
| **Android · content** | [News-App](https://github.com/Karansingh1999/News-App) | News application exploring text summarization and mobile presentation. |
| **Android · media** | [Music-App](https://github.com/Karansingh1999/Music-App) | Music player organized around albums, songs, and listening preferences. |
| **Android · API integration** | [Covid-Android-App](https://github.com/Karansingh1999/Covid-Android-App) | COVID tracking application using external API data. |

## Technical stack

<table>
  <tr>
    <th align="left" width="33%">Backend engineering</th>
    <th align="left" width="33%">Messaging & data</th>
    <th align="left" width="34%">Analysis & tooling</th>
  </tr>
  <tr>
    <td valign="top">Java · Spring Boot · REST APIs · Spring Security · Maven</td>
    <td valign="top">Kafka · Redis · SQL · DynamoDB · Elasticsearch</td>
    <td valign="top">Python · AST analysis · Gymnasium · Docker · Git</td>
  </tr>
</table>

---

<div align="center">

**Explore the code and experimental results:**  
[CloudShift-RL](https://github.com/Karansingh1999/CloudShift-RL) · [PIIFlow](https://github.com/Karansingh1999/PIIFlow) · [All repositories](https://github.com/Karansingh1999?tab=repositories)

</div>
