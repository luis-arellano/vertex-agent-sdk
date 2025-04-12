Athentication:

```
gcloud auth application-default login
```

Create a virtual Env
```
python -m venv .adk_venv
source .adk_venv/bin/activate
```


Install Google's ADK

```
pip3 install google-adk==0.1.0
```


# Rename as .env and fill your value

# Choose Model Backend: 0 -> ML Dev, 1 -> Vertex AI
GOOGLE_GENAI_USE_VERTEXAI=1

# Vertex AI backend config, uncomment and use
#GOOGLE_CLOUD_PROJECT=FILL_YOUR_PROJECT_ID
#GOOGLE_CLOUD_LOCATION=FILL_YOUR_LOCATION

# ML Dev backend config, uncomment and use
#GOOGLE_API_KEY=YOUR_AISTUDIO_API_KEY

MODEL=FILL_THE_DEFAULT_MODEL