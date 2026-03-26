Hey, i am Dayana Araujo and today in **QA Shots** i want to share how we transitioned to trusted test automation suite of a sensitive software product

# 📚Rethinking Our Test Automation Strategy for a Legacy and Crucial Software 

For a long time, our team relied on a large automation suite:  
- **1000+ tests** in total  
- **300+ disabled tests**  
- **Execution time over 1h30**  
- Frequent **flaky results**  
- Complex environment setup  
- Heavy focus on **unit tests** in this pipeline instead of integration or end-to-end coverage  

The outcome was predictable: a slow pipeline, low confidence in results, and a team that struggled to trust automation as a safety net.  

It became clear that the suite was not serving its purpose. Instead of accelerating delivery, it was slowing us down.  

---

## 📚 What We Changed  

I led an initiative to rethink our approach:  
- **Prioritization of scenarios**: we focused on the most valuable paths instead of sheer quantity.  
- **Intentional automation**: mocks and automation were introduced with clear purpose, not just for coverage numbers.  
- **API layer focus**: shifted testing strategy to integration and API-level scenarios, where confidence matters most.

Also team have worked on:
- Usage of feature flags dinamically on tests 
-  **Simplified setup**: reduced environment complexity to make tests easier to run and maintain.  

---

## 🚀 🚀 🚀The Results  

- A leaner, faster pipeline. 300+ tests (we call core tests) are running now in 10 minutes.... 
- Increased trust in automation by exercising api coverage x business rules
- Clear visibility into what truly matters for product quality
- Restored team confidence in pipeline and results 
- A foundation that scales without overwhelming the team  

---

 **🚀Automation is not about numbers—it’s about impact**. A thousand tests that nobody trusts are worth less than a hundred that give the team confidence to ship.  

---

