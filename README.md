# api-test-automation-with-llm
# 🤖 LLM-Powered API Testing with Claude, MCP & Slack
This project automates the testing of website APIs using **Claude** (via **MCP Client**) to reason over API responses and detect logical or data anomalies. Test results are sent in real-time to **Slack** for team visibility and prompt action.

---

## 🔍 Use Case

Ideal for teams needing:
- AI-based testing of API correctness
- Lightweight test automation without full-blown frameworks
- Real-time visibility through Slack integration

---

## 🚀 Features

- ✅ Automated testing of API endpoints
- 🧠 LLM reasoning via Claude (MCP protocol)
- 📊 API response validation based on expected behavior
- 📢 Slack integration for test reports and alerts
- 🔄 Easily extensible with new tests and prompt formats

---

## 🛠️ Tech Stack

| Component      | Description                                 |
|----------------|---------------------------------------------|
| Claude         | Large Language Model for analysis           |
| MCP Client     | Interface to communicate with Claude        |
| Python         | Task orchestration                          |
| REST APIs      | Target endpoints to test                    |
| Slack Webhook  | Notification system                         |

---

## 📁 Project Structure
├── src/
│ ├── test_runner.py # Main script: runs test logic
│ ├── mcp_client.py # Sends prompt to Claude via MCP
│ └── notifier.py # Sends messages to Slack
├── tests/
│ └── sample_test.json # Sample test case (API URL + expectation)
├── prompts/
│ └── response_eval.txt # Prompt template for Claude
├── config/
│ └── slack_webhook.yaml # Webhook & channel setup
├── requirements.txt
└── README.md



