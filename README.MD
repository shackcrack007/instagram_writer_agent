# Instagram Writer Agent

## Demo
[Watch Demo Video](demo.mp4)

## Installation

Install required Python packages:
```bash
pip install langflow langfuse
```

## Configuration

### Instagram Credentials
Obtain your Instagram Business Account ID and Access Token by following [this guide](https://vdelacou.medium.com/posting-to-instagram-programmatically-cc69bf1effa8).

### Environment Variables
Create a `.env` file in the project root directory with the following content:
```env
LANGFUSE_SECRET_KEY=<LANGFUSE_SECRET_KEY>
LANGFUSE_PUBLIC_KEY=<LANGFUSE_PUBLIC_KEY>
LANGFUSE_HOST="https://cloud.langfuse.com"
DO_NOT_TRACK=true
LANGFLOW_LOG_FILE=langflow.log
```

## Usage

1. Start Langflow with the environment variables:
```bash
python -m langflow run --env-file .env
```

2. Configure environment variables within Langflow settings.

3. Import provided `.json` flow files into Langflow.

4. Open `index.html` in your browser to access the application.