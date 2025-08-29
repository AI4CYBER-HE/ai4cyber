# AI4FIX – Vulnerability Fixing  

**AI4FIX** is a fully open-source, end-to-end vulnerability fixing solution supporting **Java**.  

It introduces **automatic unit testing of proposed fixes**, enabling vulnerabilities to be resolved much earlier in the software development lifecycle. By shifting patching upstream, AI4FIX reduces development time, minimizes rework, and improves the security and robustness of applications.  

---

##  Project Structure  

- **Fix Generator/**  
  Creates fixes for detected robustness warnings using **LLMs**.  

- **Test Generator/**  
  Generates tests for the robustness improvements introduced by the fix generator, leveraging **LLMs**.  

- **JIRA Miner + Dataset/**  
  Collector tool for mining JIRA issues and associated GitHub pull requests, producing datasets to support training and evaluation.  

- **Open-source LLM/**  
  Explores the use of LLMs (e.g., **GPT-4o**) for creating code fixes.  

- **Integrated AI4FIX + AI4VULN/**  
  Combines bug finding and fixing in a single pipeline, integrating vulnerability detection with automated patch generation.  

---


## Development 

THis is developed by SLAB

