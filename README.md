# Smart LLM cache
This is a token optimizer and cache proxy for LLM agents dealing with cyber security copilots.

# Problem
You have a team of multiple SOC analysts conversating with a security co-pilot such as the Microsoft Co-Pilot for Defender or any other solutions. You are billed by the amount of total tokens consumed (input+output) by the provider or by GPU instances, your analyst are asking identical or similar questions 80% of the time, with identical or similar outputs. 
Therefore when your team is performing QA on a daily routine they are over spending on your tokens.

# Solution
This is a proxy that optimizes the QA process by using a smart cache system based on the cyber ontologies.
It uses a combination of techniques from simple regexes to complex NLU methods to reduce the number of tokens during the QA process.
It can be installed with any existing conversational agent a'la ChatGPT.

# Stack
Built on a fully open source stack:
* Langchain
* ChromaDB
* Neo4J+NetworkX
* Redis
* HuggingFace
* NLTK+Spacy
* 
# Billing examples:

Microsoft copilot: [page](https://azure.microsoft.com/en-gb/pricing/details/microsoft-copilot-for-security/)
Open AI: [page](https://openai.com/api/pricing/)
  
# Video demo

A recorded session demonstrating usage for threat intelligence on [youtube](https://youtu.be/c5HkWjbEWeo)

# Screenshot

![image](https://github.com/priamai/smartllmcache/assets/57333254/1fb4f6d5-81e7-4ae7-8dc4-0c767334c0a6)

# Join the private Beta
This is only in private beta, register your interest here.

[Apply here](https://airtable.com/appGgOFISLXWsrrKF/shriHMaVDNOrzuhJY)


