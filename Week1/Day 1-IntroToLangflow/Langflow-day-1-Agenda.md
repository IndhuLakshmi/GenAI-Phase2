Quick Cap
Phse 
Week --LLM Basics and Internals

Requirements to builder
Plan and Design
--blue print of the home
--Prototype of the home

Agent anyother LLM applicaton -Prototype of the agent

*Learn Langflow day 1*
1)What is Langflow
drag and drop tool (visualization builder for agents)

2)When the Langflow is used
POC ,Learning and Presenting your ideas as working model

3)Other tools like Langflow
n8n
flowise

4)Tools/Framework in Agent Development
Drag and Drop --n8n,Langflow,Flowise (14 days trial),Langgraph 
(complex agents/amultigents)
Framework --Langchain,llamaindex ,Google ADK (opensource)
Observability (Tracing and monitoring)---Langsmith (commercial),Langfuse(open ource)



6)Langflow 
  --UI Walkthrough
  --Components in langflow
  To run as Chat you need both chatinput and chatoutput components

*Agents creation with Langflow*
1) Create a Testcase Generator chatAgent
   a)Purpose of the agent
   b)Components used in the agent
   c)Walkthrough of the agent
   d)Execution from Langflow Playground
   Import and Export from Langflow
------------------Practice Session--------------------
2) User story reviewer agent from Jira
Fetch the story from Jira
Prompt template
Groq 

1) API Request Component
Url:https://shaneagle21ai3.atlassian.net/rest/api/3/search/jql
Http method:Post
Headers
Authorizartion
Basic 

How to create basic authentication
From Postman collection
shaneagle21ai3@gmail.com:ATATT3xFfGF0SELOe-vBc_ELJpcJ4I4F1lLI2GuLIda38Lm0GawYGMQWkRcT_hgJhk-N_TPgMCuTY-d7fh63GXsXC-bz4aaq6LsW9YLqynYsQ0fBraWWx-3y1adCZq7DRt7_gnTqBx9eEBA3AUqvsYV-OZrXVYs8TfK8DmL8JHJKJD-7GCiotf4=AA229A81

c2hhbmVhZ2xlMjFhaTNAZ21haWwuY29tOkFUQVRUM3hGZkdGMFNFTE9lLXZCY19FTEpwY0o0STRGMWxMSTJHdUxJZGEzOExtMEdhd1lHTVFXa1JjVF9oZ0poay1OX1RQZ01DdVRZLWQ3Zmg2M0dYc1hDLWJ6NGFhcTZMc1c5WUxxeW5Zc1EwZkJyYVdXeC0zeTFhZENacTdEUnQ3X2duVHFCeDllRUJBM0FVcXZzWVYtT1pyWFZZczhUZks4RG1MOEpISktKRC03R0Npb3RmND1BQTIyOUE4MQ==

https://www.base64encode.org/

key = "SCRUM-15"
["key", "summary", "description", "status", "reporter"]

3) Document QA to extract the values from the document.

------------------Practice Session--------------------
 User story reviewer agent from Jira