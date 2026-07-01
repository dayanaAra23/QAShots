# 📊 Quality Metrics That Matter!

Hello QA Community,  
I’m **Dayana Araujo** and today I want to share insights on a topic that is always crucial in our work as quality assurance professionals: **software quality metrics**.  

There are dozens of indicators out there—so which ones should we rely on?  
Based on my experience, I divide them into two categories: **general metrics** (valid for almost all projects) and **context-specific metrics** (depending on the product, team maturity, and challenges).

---

## 🔹 General Metrics
These are metrics that can and should be analyzed in practically all projects. They provide a solid overview of software health:

- **Defect Leakage / Defect Density**  
  Track the number of bugs in production by functionality and severity.  
  > Example: If critical bugs cluster in a core feature, it may indicate insufficient test coverage or lack of understanding of system integrations.

- **Automated Test Coverage**  
  Measure coverage across different test levels (unit, integration, etc.).  
  > The goal is not just a percentage, but ensuring critical functionalities are automated.

- **Bugs Found During Functional Testing**  
  A key indicator of the tester’s role.  
  > Each bug found is an opportunity to analyze root causes—whether due to misunderstanding, missing refactoring, or gaps in requirements.

---

## 🔹 Context-Specific Metrics
These depend on the main issues your product faces:

- **Number of Hotfixes After Releases**  
  > In one project, we noticed a hotfix after every release. By identifying this pain point, we implemented preventive actions that reduced post-release fixes.

---

## 🤖 Metrics and AI
With integrations like **Confluence** and **Jira**, many of these metrics can be extracted automatically. AI embedded in tools such as Atlassian helps generate dashboards and insights, making tracking more efficient.

---

## ✅ Key Takeaway
I see that we (tech team) commonly focus on development, test and automation and dont look to quality metrics as often as needed  and that's 
why i encorage all of us to start looking into it , baby steps firts and will see some spotlights that can provide more confidence in project decision making.
 
