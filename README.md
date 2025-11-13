# AzureFoundry-MCP

This project provides a dynamic chat interface using Chainlit to interact with an Azure AI Agent Service agent configured with MCP (Model Context Protocol).

## Getting Started

### Prerequisites
- Python 3.8+
- pip (Python package installer)

### Installation
1. **Clone the repository**
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

### Environment Variables
Before running the project, set the following environment variable:
- `MCP_GITHUB_TOKEN`: Your GitHub MCP server authentication token

You can set this in your shell or add it to a `.env` file in the project root:
```
MCP_GITHUB_TOKEN=your_github_token_here
```

Other required environment variables may include:
- `PROJECT_ENDPOINT`
- `MODEL_DEPLOYMENT_NAME`
- `MCP_GITHUB_URL`
- `MCP_GITHUB_LABEL`
- `MCP_MSLEARN_URL`
- `MCP_MSLEARN_LABEL`

Refer to the code for more details on these variables.

### Running the Project
Start the chat interface with:
```bash
chainlit run multiMcp.py
```

You can now interact with the Azure AI Agent via the Chainlit web interface.

---

© Microsoft Corporation. Licensed under the MIT License.
