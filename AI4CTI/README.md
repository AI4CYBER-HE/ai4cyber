
# AI4AICTI – Cyber Threat Intelligence Improvement

AI4AICTI is an advanced solution that delivers the latest **AI-powered Cyber Threat Intelligence (CTI)** to enhance detection systems and threat simulation tools, improving their efficiency and resilience.  

The platform integrates intelligence on both **Adversarial Machine Learning (AML) attacks** and **AI-boosted cyberattacks**, enabling organizations to anticipate evolving threats and strengthen their defenses.  

By leveraging state-of-the-art AI models and modular processing pipelines, AI4AICTI ensures that CTI data is efficiently ingested, aggregated, assessed, and transformed into actionable insights for cybersecurity providers, SOC teams, and research institutions.  

---

## Project Structure

The repository is organized as follows:

- **CTI_Ingest/**  
 Open CTI ingestion module

- **CTI_Aggregation/**  
  Module that produces augmented (enriched) CTI about advanced attacks where the attack TTPs are ordered and proposed mitigations too. 

- **CTI_assessment/**  
  Module that verifies the consistency of the processed CTI across the different sources ingested and proposes the order of TTPs. 

- **CTI_frontend/**  
  Interfaces for visualizing CTI insights, user interaction, and system monitoring.

- **Graph_processing/**  
  Attack graph processing to extract the flow of attack steps. 

- **Open-source-LLM/**  
 LLM - Llama 3.1-70B for analysing CTI reports.

- **Structured_data_processing/**  
 Module for the extraction of structured data from the ingested CTI sources. 

- **Unstructured_data_processing/**  
 Module for natural language processing of ingested Open CTI sources. 

## Development
This tool has been developed by TECHNALIA

