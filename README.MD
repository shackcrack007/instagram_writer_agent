# setup
`pip install langflow langfuse`

1. get Instagram business account id and access token: https://vdelacou.medium.com/posting-to-instagram-programmatically-cc69bf1effa8

2. Prepare env variables file:
```
LANGFUSE_SECRET_KEY=<LANGFUSE_SECRET_KEY>
LANGFUSE_PUBLIC_KEY=<LANGFUSE_PUBLIC_KEY>
LANGFUSE_HOST="https://cloud.langfuse.com"
DO_NOT_TRACK=true
LANGFLOW_LOG_FILE=langflow.log
```

### Run Instructions
1. run `python -m langflow run --env-file .env`

2. prepare env variables inside langflow settings

3. import .json files flows inside langflow

4. open index.html using your browser