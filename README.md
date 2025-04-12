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

Set up

create a new .env file

```
GOOGLE_GENAI_USE_VERTEXAI=
GOOGLE_CLOUD_PROJECT=
GOOGLE_CLOUD_LOCATION=
MODEL=
```