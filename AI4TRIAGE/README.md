
# AI4TRIAGE – Incident Triage  

**AI4TRIAGE** is an AI-powered solution for **incident triage and root cause analysis**, designed to prioritize security events and improve response efficiency.  

By combining advanced causal factor identification, similarity-based analysis, and automated alert categorization, AI4TRIAGE enables SOC teams to focus on the most critical incidents first, reducing response time and improving resilience against complex attacks.  

---

##  Project Structure  

- **Data Collector**  
  Normalizes logs and alerts into a unified key-value format for post-processing within AI4TRIAGE.  

- **Identification of Causal Factors**  
  Detects and stores causal factors in the AI4TRIAGE database. Linked with **AI4CTI** to help identify TTPs (Tactics, Techniques, Procedures) of complex attacks.  

- **Identification of Root Causes**  
  Determines the root causes of alerts using **similarity analysis** with KNN-based models.  

- **Categorization and Triage of Alerts**  
  Classifies alerts according to their root cause and categorizes them by **criticality**, enabling prioritization of incident response.  

---

## 🔗 Repository  

Access AI4TRIAGE here:  
👉 [AI4TRIAGE on GitHub](https://github.com/Montimage/ai4triage)  

