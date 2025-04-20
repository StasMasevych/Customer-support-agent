# Customer Support Agents

A Python-based autonomous agent system designed to automate customer support interactions for engineering and energy companies. Built with CrewAI, this project demonstrates how two AI agents collaborate to answer customer inquiries and ensure high-quality support.

## 🚀 Features

- **Agentic Customer Support**: Two specialized agents handle customer inquiries and assure response quality.
- **Conversational AI**: Simulates realistic customer conversations, including company introductions and detailed answers.
- **Quality Assurance**: A dedicated agent reviews and ensures the quality and completeness of support responses.
- **Customizable Inputs**: Easily modify the customer, person, and inquiry for different scenarios.
- **Modular Design**: Add or update agents in `utils.py` for new support tasks or industries.
- **Environment Configurable**: API keys and settings via `.env` file.

## 🧩 Main Agents

- **Support Agent**: Acts as a Senior Support Representative, receives and processes the customer's inquiry, and provides friendly, complete, and accurate responses.
- **Support Quality Assurance Agent**: Reviews the Support Agent's response to ensure it meets high standards of helpfulness, accuracy, and completeness before delivering it to the customer.

## 🏗️ How It Works

1. **Setup**: Add your OpenAI API key and other settings to the `.env` file.
2. **Run the App**: Execute `main.py` to start the agent workflow.
3. **Agent Collaboration**: The Support Agent drafts a response, and the Support Quality Assurance Agent reviews and approves it.
4. **Output**: The system prints the AI-generated, quality-assured reply to the customer's question.

## 📦 Installation

```bash
git clone <repo-url>
cd customer-support-agents
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## ⚙️ Usage

1. Set up your `.env` file with required API keys.
2. Run the main script:
   ```bash
   python main.py
   ```
3. Modify the `inputs` dictionary in `main.py` to simulate different customer scenarios.

## 📝 Example

```
$ python main.py
[SupportAgent] Received inquiry from Peter at Company X...
[SupportQualityAssuranceAgent] Reviewing response for helpfulness and completeness...
AI-generated response:
Hello Peter, thank you for your interest in our company. We have developed several solar power plants in the USA, including...
```

## 🛠️ Customization

- Add new agent logic in `utils.py` or separate files.
- Integrate with external APIs for real-time project data.
- Adapt for other industries or customer support scenarios.

## 📚 Dependencies

- Python 3.8+
- CrewAI (or your agent framework)
- Requests, dotenv, and other packages in `requirements.txt`

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss your ideas.
