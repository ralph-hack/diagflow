# Creating a chatbot using DiagFlow
Following these instructions:
https://cloud.google.com/dialogflow/es/docs/quick/build-agent

DiagFlow console can be accessed here: <br/>
https://console.dialogflow.com/api-client/#/agent/a4441a1f-952d-4c3c-90e8-fe2bf5ff6d6a/integrations
https://dialogflow.cloud.google.com/#/agent/a4441a1f-952d-4c3c-90e8-fe2bf5ff6d6a/integrations

Node.js client library for DiagFlow: <br/>
https://cloud.google.com/dialogflow/es/docs/reference/libraries/nodejs
https://cloud.google.com/dialogflow/es/docs/reference/rest/v2-overview

1. Set up a Google Cloud Console Account - already have
2. Select an existing Google Cloud project - done
3. Enable Diagflow API within console.google.cloud.com - done
4. Install google cloud cli
   - install python - done
   - where python3 (to find location and verify install) - done
   - download google cli tar - done
   - move it to raljoach\tools folder - done
   - run install.sh in google cli folder - done
5. In a new terminal window, run 
   gcloud init - done (will redirect to https://cloud.google.com/sdk/auth_success)

6. Setup authentication for REST
   https://cloud.google.com/docs/authentication/rest - done

7. gcloud auth login
8. gcloud auth application-default login
   gcloud auth application-default set-quota-project PROJECT_ID
