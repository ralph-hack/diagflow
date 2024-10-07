# Creating a chatbot using DiagFlow
Following these instructions:
https://cloud.google.com/dialogflow/es/docs/quick/build-agent

DiagFlow console can be accessed here: <br/>
[DiagFlow Console](https://dialogflow.cloud.google.com/)

Node.js client library for DiagFlow: <br/>
https://cloud.google.com/dialogflow/es/docs/reference/libraries/nodejs
https://cloud.google.com/dialogflow/es/docs/reference/rest/v2-overview

DiagFlow basics: <br/>
https://cloud.google.com/dialogflow/es/docs/basics

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
8. gcloud auth application-default login <br/>
   gcloud auth application-default set-quota-project PROJECT_ID


Follow: <br/>
https://cloud.google.com/dialogflow/es/docs/quick/build-agent

9. [Diagflow console](https://dialogflow.cloud.google.com/) -> Create an Agent
10. [Import Example File to Your Agent)[https://cloud.google.com/dialogflow/es/docs/quick/build-agent#import-the-example-file-to-your-agent]
