*Agenda Langflow day2*
--Recap of Langflow day1 with Quiz
*Learning Langflow API*
1)Langflow Workflow APIs are used to run your Langflow visual workflows from outside Langflow.
You build the flow visually in Langflow, then expose it as an API so Froneend or Postman and trigger it.
  *How to ?*
   --Extract Endpoint,api request body from LangflowUI
   --Generate Langflow api key
   --Execute in Postman
    Using Langflow API
    http://localhost:7860/api/v1/run/6eacd943-b7fc-477c-977d-c1208eb0822e
    Runs only on my machine
    Deploy that VM --testing environt ,UAT --
    http://domain-name/api/v1/run/6eacd943-b7fc-477c-977d-c1208eb0822e
  ----Classroom Session-----------
   --Apply Dynamic values/Customize the API Request to the langflow API'S
  -------Classroom Session-----------
*Common mistakes*
1)Workflow url used is incorrect ,curl and copy your workflow as per steps (using the workflow in shared postman collection and giving your langflow key)
2)In the query parameters disable stream=false
3)In the Langflow workflow UI --Set the max token limit as 4096 for Groq Component.
4)Langflow Key is not set in the header 

  *Reference Documents*
  https://docs.langflow.org/
  https://docs.langflow.org/api-reference-api-examples
  https://docs.langflow.org/concepts-publish
  https://docs.langflow.org/api-keys-and-authentication
  https://docs.langflow.org/api
