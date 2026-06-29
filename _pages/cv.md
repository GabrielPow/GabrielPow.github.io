---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
### **BSc in Data Science and Artificial Intelligence**
**Ibmec Faria Lima** | São Paulo, Brazil *(August 2023 – July 2027)*
* **GPA (CR Geral):** 8.3 / 10
* **Relevant Coursework:** Programming for Data Analysis, Computational Modeling, Data Engineering, Data Structures, Statistical Inference, Big Data, Machine Learning, Reinforcement Learning.

Work Experience & Leadership
======
### **Teaching Assistant (Monitoria) — Computational Modeling & Data Structures**
**Ibmec Faria Lima** |  São Paulo, Brazil *(March 2025 – November 2025)*
* Served as an academic mentor for Data Structures and Computational Modeling courses.
* Assisted students with complex programmatic and mathematical concepts, contributing to an average **1.5-point grade increase** among regularly tutored students.

### **Class Representative**
**Ibmec Faria Lima** |  São Paulo, Brazil *(February 2025 – November 2025)* 
*  Represented the student body in official alignment meetings with the academic board and department heads.
*  Monitored curriculum compliance to ensure all courses adhered strictly to public syllabi and program standards.

### **Work Shadowing Program — Cybersecurity**
**Vivo** |  São Paulo, Brazil *(June 2022 – July 2022)* 
*  Observed enterprise cybersecurity operations during the rollout of critical data protection and security management systems.
*  Developed a foundational understanding of cross-functional team dynamics and deployment Lead Time metrics.

Skills
======
*  **Languages:** English (Native), Portuguese (Native).
*  **Programming Languages:** Python, C, C++, Java, SQL.
*  **Frameworks & Libraries:** React, Pandas, Node.js, Spring, FastAPI, Flask, LangChain.
*  **Tools & Platforms:** PowerBI, PowerQuery, Git, Microsoft Office Suite (Excel, PowerPoint).

<!--->
Publications
======
{% if site.publications %}
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% else %}
  <p>Available upon request or visible in the Portfolio tab.</p>
{% endif %}
  
Talks
======
{% if site.talks %}
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
{% else %}
  <p>Available upon request.</p>
{% endif %}
  
Teaching
======
{% if site.teaching %}
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% else %}
  <p>Details regarding Teaching Assistant roles are listed above under Experience.</p>
{% endif %}
