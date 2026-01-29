Step's for running the app 

Step 1:
First run the app using 
uv run uvicorn main:app

Step 2:
Now spinup the ingest server (Only for checking the connection health and other operations if you want)

npx inngest-cli@latest dev -u http://127.0.0.1:8000/api/inngest --no-discovery

Step 3:
Use streamlit to get a UI for uploading the files(We can directly do this from the ingest server by invoking in functions.Streamlit provides a frontend UI interface for our app logic) 

